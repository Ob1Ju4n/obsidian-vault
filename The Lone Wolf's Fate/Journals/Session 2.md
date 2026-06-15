#### Al Límite

##### *"You're in the hunt of a dangerous beast"

Mientras me despierto de mi letargo, siento como unas cuantas gotas de agua se deslizan por mi rostro. Poco a poco vuelven a mi fragmentos de los acontecimientos recientes. 

Un bello rostro, 
Una mirada de compasión, 
Un dolor infernal... 

Estoy acostado en el suelo cubierto por musgo. Mis ojos no demoran en adaptarse a la oscuridad. No hay árboles cubriendo los alrededores, pero reconozco el lugar. Estoy a las afueras del bosque en una noche fría, silenciosa y sin luna .

Entre tanto, me concentro en la espalda y muevo mi mano esperando palpar una herida, pero no encuentro nada. Lo único que queda de la supuesta lesion es un recuerdo vivido y aun así, mi cuerpo se siente sin energía y magullado.

Me toma un rato mas recobrar la lucidez. Con ella mis recuerdos se vuelven mas claros y punzantes a la vez que pensamientos intrusivos me asaltan en el silencio. He fallado en mi cometido de encontrar información, una deshonra a la vez que una perdida de tiempo. 

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Spirit" action=5 adds=0 stat=3 vs1=6 vs2=3
}
```

Aunque no tengo ni animo ni fuerzas, encuentro algo de calma en la soledad. Tomare lo que resta de la noche para reflexionar y hacer duelo sobre mi fallida misión. Ahora comprendo que eran esas gotas de agua. Eran lagrimas de impotencia, de rabia y desolación. Mi incapacidad no solo me ha despojado del honor sino que seguramente ha condenado a la aldea a morir. Lo unico que me queda, como bien sugirio la elfa, es volver y enfrentar con gallardia mi destino y el de los míos.

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=3 adds=0 stat=5 vs1=8 vs2=8
}
```

Sin embargo, mientras preparo el campamento una sensación familiar pone en alerta mis sentidos. Algo se mueve silenciosamente en la oscuridad. Tomo el arco y preparo una flecha, preguntandome que es lo que me acecha...

- Es un horror?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="No" roll=38
```
- O tal vez una bestia de los antiguos mitos?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="Yes" roll=98
```

No tengo tiempo de pensar. Un gruñido gutural me estremece y hace temblar mis rodillas. El ataque se aproxima y la adrenalina agudiza mis sentidos...

```iron-vault-mechanics
track name="[[The Lone Wolf's Fate\/Progress\/Green Wyvern.md|Green Wyvern ]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Wits" action=2 adds=0 stat=3 vs1=9 vs2=8
}

```

Lo siguiente que percibo es ...

- Un latigazo desde una dirección inesperada que golpea de costado, lanzandome por los aires. He soltado el arco con el golpe.
- El zumbido de unas alas desplegandose y luego el Wyvern abalanzandose sobre mi a toda velocidad. He caido bajo sus fuertes patas y el abrazo de sus garras es muy fuerte. (likely)
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Yes" roll=45
```

... un golpe en mi torso que me impulsa hacia el suelo. Siento un peso que presiona fuerte mi pecho y me deja sin aire. Mientras, intento recuperar el aliento veo a la bestia abriendo sus fauces que despiden un hedor nauseaubundo.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=6 adds=0 stat=1 vs1=2 vs2=1
}
```

Apenas consiente, apuesto que la bestia esta por cerrar su mandíbula sobre mi cuello. Empuño la flecha de mi mano derecha como un puñal y espero tener la destreza para asestar un golpe que me de una oportunidad.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=2 adds=0 stat=3 vs1=8 vs2=7
}
```

- Mi movimiento es torpe y la bestia lo nota. Sus fauces se cierran sobre mi brazo.
- Su cola como un latigo quiebra, la fecha. Se abalanza sobre mi cuello. (likely)

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Yes" roll=33
```

Pero el destino esta en mi contra. En el momento en que muevo la muñeca, el Wyvern mueve su cola y de un latigazo destroza la flecha. En ese mismo instante su mandibula, se cierra sobre mi cuello.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=1 adds=0 stat=2 vs1=4 vs2=10
}
```

Intento poner el brazo pero reacciono demasiado tarde y siento como sus filosos dientes atraviesan el abrigo y la armadura de cuero.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=5 adds=0 stat=1 vs1=10 vs2=7
}
```

Siento el calor de la sangre que brota bajo la ropa. Mis dedos comienzan a enfriarse y siento que cada vez tengo menos energía. La bestia presiona con mas fuerza mi torso.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=6 adds=0 stat=1 vs1=9 vs2=1
}
```

Ante toda probabilidad sigo consiente, aunque me embarga un sentimiento de ansiedad. Contra mi voluntad luchadora, deseo que todo termine.

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Iron" action=5 adds=0 stat=2 vs1=4 vs2=4
}
oracle name="[Turning Point Oracles \/ Major Plot Twist](datasworn:oracle_rollable:classic\/turning_point\/major_plot_twist)" result="The true enemy is revealed." roll=65

```

Depronto, un silbido tras otro se escucha en la noche. 

- Golpean las flechas (likely)

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Yes" roll=61
```


Acto seguido siento como la bestia reacciona reposicionandose y aunque en primera instancia no me suelta, abre su mandibula pera rugir hacia la oscuridad  luego de que varias flechas impactan en sus alas y costado.

Malherido, pero con una esperanza renovada, comienzo a buscar rapidamente como alejarme de la bestia buscando evitar su campo de visión y la dirección del viento.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=1 adds=0 stat=3 vs1=1 vs2=2
}
```

La lluvia de flechas me permite tomar un poco de aliento y evaluar mi ruta de escape. Oigo tambien aullidos que se acercan de varias direcciones o tal vez es un efecto de la perdida de sangre? No tengo tiempo para pensar en ello, mi prioridad es huir evitando atraer la atención de la criatura.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "Advtg."
    roll "Wits" action=1 adds=1 stat=3 vs1=4 vs2=10
}
```

Los gruñidos del Wyvern se escuchan un poco mas lejos y el efecto de la adrenalina que me impulsaba comienza a desvanecer. Cada paso me cuesta mas que el anterior. Me duele la cabeza, tengo mucho frío y mis brazos y piernas estan encalambrados. El dolor de la mordida se hace mas intenso.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=1 adds=0 stat=1 vs1=9 vs2=10
}
oracle name="[Endure Harm \/ Endure Harm](datasworn:move.oracle_rollable:classic\/suffer\/endure_harm.endure_harm)" result="You are battered but still standing." roll=93
move "[Face a Setback](datasworn:move:classic\/suffer\/face_a_setback)"

```

Caigo de rodillas. No hay manera de que avance mucho mas si no controlo la perdida de sangre asi que me recuesto entre los primeros arbustos que encuentro e intento atender mis heridas.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=2 adds=0 stat=3 vs1=3 vs2=1
}
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    add 1 "Advtg."
    roll "Iron" action=5 adds=1 stat=1 vs1=5 vs2=4
}
```


Con mucho cuidado y recordando algunas escaramuzas de mi pasado logro cerrar con éxito las heridas del torso. Esos instantes de concetración tambien me permiten recobrar paulatinamente el aliento. El pecho me duele y aun me cuesta respirar. Intuyo que gracias a la armadura lo unico roto es mi orgullo y hombría.

Pasa mas tiempo mientras intento concentrarme en escuchar al Wyvern o los cazadores pero no logro oir nada mas que la danza de las hojas al paso del viento y algunos insectos revoloteando alrededor. Aunque estoy exhausto, siento que el dolor de mi cabeza es cada vez mas punzante. Esto puede deberse a la deshidratación por lo que busco agua y provisiones en mi mochila.

```iron-vault-mechanics
move "[Check Your Gear](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Supply" action=6 adds=0 stat=4 vs1=6 vs2=6
}
oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Locate" roll=86
oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Desolation" roll=86

```

Definitivamente los alimentos me ayudan a recuperar poco a poco la energía perdida. Puedo pensar con mas claridad. Asumo que todavía falta algo de tiempo para el amanecer pero es claro que deambular por la oscuridad en el estado en que me encuentro es un riesgo. Por fortuna, encuentro un pequeño barranco, seco y con espacio suficiente para cubrirme por lo que queda de la noche. 







