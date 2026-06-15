# Core Pipeline Specification

This document defines the core data pipeline for processing actual play TTRPG episodes. All agents running in this project must adhere to this architecture and file flow.

## Data Flow Diagram

```text
episode-journal.md
       │
       ▼
1. Campaign Curator (loremaster)
       │
       ├── updated-campaign-canon.json
       └── updated-campaign-memory.json
                │
                ▼
        2. Narrative Analyst (narrative-analyst)
                │
                ▼
        episode-analysis.json
                │
      ┌─────────┴─────────┐
      ▼                   ▼
3. Cover Art Agent   4. Suno Agent (sound-art)
   (visual-art)           │
      │                   ▼
      ▼              suno-package.json
cover-prompts.json
      │
      ▼
5. Image Generator
      │
      ▼
4 Cover Images
      │
      ▼
6. Blog Publisher (publicist) [Optional]
      │
      ▼
blog-post.md
```

---

## Agent Specifications

### 1. Campaign Curator Agent
* **Skill Prompt:** [loremaster/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/loremaster/skill.md)
* **Purpose:** Maintains long-term campaign continuity.
* **Inputs:** 
  - `campaign-canon.json`
  - `campaign-memory.json`
  - `episode-journal.md`
* **Outputs:** 
  - `updated-campaign-canon.json` (overwrites existing `campaign-canon.json`)
  - `updated-campaign-memory.json` (overwrites existing `campaign-memory.json`)
  - `campaign-changelog.md`

### 2. Narrative Analyst Agent
* **Skill Prompt:** [narrative-analyst/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/narrative-analyst/skill.md)
* **Purpose:** Transforms a journal entry into structured narrative intelligence (themes, emotional arc, visual hooks).
* **Inputs:** 
  - `episode-journal.md`
  - `campaign-canon.json`
  - `campaign-memory.json`
* **Outputs:** 
  - `episode-analysis.json`

### 3. Cover Art Prompt Agent
* **Skill Prompt:** [visual-art/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/visual-art/skill.md)
* **Purpose:** Creates 4 distinct cover art style concepts and image prompts.
* **Inputs:** 
  - `episode-analysis.json`
  - `campaign-memory.json`
* **Outputs:** 
  - `cover-prompts.json`

### 4. Suno Music Agent
* **Skill Prompt:** [sound-art/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/sound-art/skill.md)
* **Purpose:** Creates soundtrack concepts and Suno style prompt packaging.
* **Inputs:** 
  - `episode-analysis.json`
  - `campaign-memory.json`
* **Outputs:** 
  - `suno-package.json`

### 5. Image Generation Agent
* **Purpose:** Generates cover images from prompts.
* **Inputs:** 
  - `cover-prompts.json`
* **Outputs:** 
  - Rendered cover images.

### 6. Blog Publisher Agent (Optional)
* **Skill Prompt:** [publicist/skill.md](file:///Users/juan.pablo.ortiz/Documents/Ironsworn/Ironsworn/.agents/skills/publicist/skill.md)
* **Purpose:** Formats the final markdown blog post combining the story, meta elements, cover image, and soundtrack recommendations.
* **Inputs:** 
  - `episode-journal.md`
  - `episode-analysis.json`
  - Featured image
  - Featured song
* **Outputs:** 
  - `blog-post.md`
