# Core Pipeline Specification

This document defines the core data pipeline for processing actual play TTRPG episodes. All agents running in this project must adhere to this architecture and file flow.

## Directory Structure

Each session has a dedicated folder under `Journals/s{number}/`:
```text
Journals/
└── s{number}/                       # e.g., s0, s1, s2...
    ├── episode-journal.md           # Raw journal entry (Input)
    ├── cover-images/                # Cover concepts, prompts, and final assets
    │   ├── s{number}.md             # Contains narrative analysis & cover prompts
    │   └── [Generated Cover Images] # Cinematic, Illustration, Symbolic, Mythic
    ├── music/                       # Soundtrack concepts and playlist packages
    │   └── suno-package.json        # Suno style prompts & musical motifs
    └── blog-post.md                 # [Optional] Compiled markdown blog post
```

---

## Data Flow Diagram

```text
Journals/s{number}/episode-journal.md
       │
       ▼
1. Campaign Curator (loremaster)
       │
       ├── Updates: Lore/campaign-canon.json
       └── Updates: Lore/campaign-memory.json
                │
                ▼
        2. Narrative Analyst (narrative-analyst)
                │
                ▼
        Appended to: Journals/s{number}/cover-images/s{number}.md
                │
      ┌─────────┴─────────┐
      ▼                   ▼
3. Cover Art Agent   4. Suno Agent (sound-art)
   (visual-art)           │
      │                   ▼
      ▼              Journals/s{number}/music/suno-package.json
Appended to:
Journals/s{number}/cover-images/s{number}.md
      │
      ▼
5. Image Generator (generate_image)
      │
      ▼
Journals/s{number}/cover-images/[4 images].png
      │
      ▼
6. Blog Publisher (publicist) [Optional]
      │
      ▼
Journals/s{number}/blog-post.md
```

---

## Agent Specifications

### 1. Campaign Curator Agent
* **Skill Prompt:** [loremaster/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/loremaster/skill.md)
* **Purpose:** Maintains long-term campaign continuity.
* **Inputs:** 
  - `Journals/s{number}/episode-journal.md`
  - `Lore/campaign-canon.json`
  - `Lore/campaign-memory.json`
* **Outputs:** 
  - Overwrites: `Lore/campaign-canon.json`
  - Overwrites: `Lore/campaign-memory.json`
  - Overwrites: `Lore/campaign-changelog.md`

### 2. Narrative Analyst Agent
* **Skill Prompt:** [narrative-analyst/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/narrative-analyst/skill.md)
* **Purpose:** Transforms a journal entry into structured narrative intelligence (themes, emotional arc, visual hooks).
* **Inputs:** 
  - `Journals/s{number}/episode-journal.md`
  - `Lore/campaign-canon.json`
  - `Lore/campaign-memory.json`
* **Outputs:** 
  - Written to: `Journals/s{number}/cover-images/s{number}.md` (as `# Analysis`)

### 3. Cover Art Prompt Agent
* **Skill Prompt:** [visual-art/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/visual-art/skill.md)
* **Purpose:** Creates 4 distinct cover art style concepts and image prompts.
* **Inputs:** 
  - Analysis from `Journals/s{number}/cover-images/s{number}.md`
  - `Lore/campaign-memory.json`
* **Outputs:** 
  - Appended to: `Journals/s{number}/cover-images/s{number}.md` (as `# Prompt`)

### 4. Suno Music Agent
* **Skill Prompt:** [sound-art/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/sound-art/skill.md)
* **Purpose:** Creates soundtrack concepts and Suno style prompt packaging.
* **Inputs:** 
  - Analysis from `Journals/s{number}/cover-images/s{number}.md`
  - `Lore/campaign-memory.json`
* **Outputs:** 
  - Written to: `Journals/s{number}/music/suno-package.json`

### 5. Image Generation Agent
* **Purpose:** Generates cover images from prompts.
* **Inputs:** 
  - Prompts from `Journals/s{number}/cover-images/s{number}.md`
* **Outputs:** 
  - `Journals/s{number}/cover-images/` (saved as PNGs matching the 4 style concepts)

### 6. Blog Publisher Agent (Optional)
* **Skill Prompt:** [publicist/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/publicist/skill.md)
* **Purpose:** Formats the final markdown blog post combining the story, meta elements, cover image, and soundtrack recommendations.
* **Inputs:** 
  - `Journals/s{number}/episode-journal.md`
  - Analysis from `Journals/s{number}/cover-images/s{number}.md`
  - Featured image from `Journals/s{number}/cover-images/`
  - Featured song details from `Journals/s{number}/music/suno-package.json`
* **Outputs:** 
  - `Journals/s{number}/blog-post.md`
