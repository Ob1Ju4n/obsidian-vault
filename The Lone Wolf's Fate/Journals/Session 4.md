#### Caos y desolación

El relinchar del caballo me pone en alerta y tambien a mis captores. El hachero aun tiene su mano en mi espalda pero noto que su foco ha cambiado a intentar discernir la dirección del pesado trote que se acerca desde la negra noche. Y luego, de frente, las zarpas en el aire de un oso.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=5 adds=0 stat=2 vs1=1 vs2=7
}
```

Apenas puedo reaccionar y evitar la embestida del oso que logra hacer daño con sus garras, no son cortes profundos pero he perdido mucha sangre. Tengo que buscar una forma de que se enfoque en mis captores.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=5 adds=0 stat=2 vs1=9 vs2=8
}
```

Intento reposicionarme pero las piernas me fallan, pierdo el equilibrio y me desplomo.

- Los captores atacan al oso de inmediato (almost certain)
- Los captores mantienen su distancia

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Almost Certain](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.almost_certain)" result="No" roll=10
```

Cautelosamente, el oso se acerca y muerde una de mis piernas moviendola de un lado al otro, es un dolor impresionante.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=3 adds=0 stat=1 vs1=5 vs2=7
}
```

Parece que mis gritos de dolor hacen eco en la carroza pues se escuchan gemidos y lloriqueos. Mis captores no parecen interesados en involucrarse y el oso continua arrastrandome en su intento por separarme de mis captores.

- El oso percibe las personas dentro de la carroza e intenta disuadir a los escoltas para huir del lugar (likely)
- El oso ignora las personas dentro de la carroza y se aleja con mi cuerpo mas allá de la carroza

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Almost Certain](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.almost_certain)" result="Yes" roll=96
```

El oso se detiene al lado de la carreta y siento que me suelta para olfatearla. Las personas adentro gritan. Este movimiento pone en acción a mis captores. 

Oigo una flecha que cruza por el campo mientras los pasos del hachero avanzan hacia el animal. 

El oso responde a los ataques enfocandose en la amenaza mas cercana, mientras el arquero continua disparando. Siento la adrenalina correr y me vuelco sobre mi estomago buscando distanciarme del oso.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Shadow" action=5 adds=0 stat=1 vs1=6 vs2=7
}
oracle name="[Pay the Price \/ Pay the Price](datasworn:move.oracle_rollable:classic\/fate\/pay_the_price.pay_the_price)" result="You are separated from something or someone" roll=10

```

Desafortunadamente el oso obliga al hachero a reposicionarse hasta mi posición evitando mi intento de salir de su zona de peligro. Soy su presa y no piensa dejarme ir. Si es así, decido morir luchando.

```iron-vault-mechanics
track name="[[The Lone Wolf's Fate\/Progress\/Ash Bear.md|Ash Bear]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Wits" action=5 adds=0 stat=3 vs1=1 vs2=9
}

```

Con mis manos atadas logro incorporarme. Veo que el oso esta...

```iron-vault-mechanics
oracle name="[Character \/ Character First Look](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Sinister" roll=94
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Observing" roll=79
oracle name="[Character \/ Character Details](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Wild" roll=44
```

... preparandose para atacar. No percibo que tenga miedo de quienes estamos aqui, definitivamente tendremos que lastimarlo mas para que nos deje en paz. Lanza dos zarpazos mientras ruge, uno en mi dirección y el otro hacia el hachero.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=4 adds=0 stat=2 vs1=3 vs2=6
}
```


Esta vez sus garras no me alcanzan, sin embargo me siento con muy poca energía y sigo atado de pies y manos. Salir de esta situación es un desafío que tal vez no pueda superar.

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=5 vs2=3
}
```

Trato de safar mis amarres pero estan muy ajustados y no puedo concentrarme con los rugidos y embates de la bestia. El oso ...

```iron-vault-mechanics
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Threatening" roll=85
```

... se alza amenazante en 2 patas para caer con todo su peso, derribando el hachero quien parece haberlo enfurecido. Luego, avanza amenazante hacia el arquero, primero dando unos pasos y luego impulsandose velozmente, arrollando a su objetivo. 

La sacerdotiza que estaba a su lado ha tomado algo de distancia. El hachero se reincorpora y vuelve a la batalla mientras yo por mi parte solo puedo ver como mi plan se desmorona. No estoy logrando tener el tiempo necesario para liberarme de mis ataduras

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=2 vs2=6
}
```

Me siento impotente pero trato de buscar un poco de calma en esta situación, el oso ...

```iron-vault-mechanics
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Defending" roll=61
```

... se defiende de los ataques del hachero dandole una oportunidad al arquero para ponerse de pie, sin embargo, el animal se reposiciona entre mi y mis captores logrando así, finalmente, separarme del grupo. 

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=1 adds=0 stat=5 vs1=8 vs2=9
}
move "[Face a Setback](datasworn:move:classic\/suffer\/face_a_setback)"

```

En este momento, siento que estoy a merced la naturaleza salvaje. Creo que cometí un grave error al intentar atraer una bestia a este lugar. No solo fue un movimiento muy arriesgado sino que tambien puse en peligro a la pobre gente que fue capturada. 

```iron-vault-mechanics
move "[Turn the Tide](datasworn:move:classic\/combat\/turn_the_tide)"
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "turn the tide"
    roll "Wits" action=3 adds=1 stat=3 vs1=10 vs2=8
}

```

Intento desesperadamente hacer un poco de espacio en mis ataduras pero ya no me quedan fuerzas y no puedo pensar con claridad. Todo ha salido mal, no he logrado salvar a unos pocos aldeanos, no logre ayudar a mis hermanos y mucho menos pude dar caza al mal que nos acecha. Tan desafortunadas fueron mis acciones que incluso creo que mi gente morira hoy por mi propio actuar.

```iron-vault-mechanics
move "[Face Desolation](datasworn:move:classic\/suffer\/face_desolation)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=2 vs2=2
}
```

La lucha continua pero yo solo pienso en darme por vencido. Es en ese instante cuando escucho el relinchar del caballo y me muevo en su dirección mientras la lucha continua. Es este tal vez un llamado a la otra vida?

Camino pesadamente. El oso por su parte ...

```iron-vault-mechanics
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Guarding" roll=1
```

... esta totalmente concentrado en esquivar los ataques y mis captores lo asedian desde frentes distintos. 

Logro llegar hasta donde el caballo y durante un momento apoyo mi mejilla en su crin. Su respiración es agitada. Entonces pongo mis manos ensangrentadas para darle una caricia e intentar calmarlo, sin dejar de mirar a los luchadores. En cualquier momento el oso se percatara de mi movimiento y ahi quedara sellado mi destino.

```iron-vault-mechanics
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Distracting" roll=69
```

Pero por ahora permanece distraido mordiendo al arquero, mientras se reposiciona para evitar los ataques del otro escolta. No puedo evitar sentir algo de esperanza aunque seguramente es mi instinto de supervivencia.

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=2 vs2=6
}
```

Con cuidado libero al caballo de los arbustos a los que estaba sujeto y como en un acto de agradecimiento inclina su lomo y patas delanteras. Con lo que me resta de energía y seguro de que en cualquier momento que el oso acabara conmigo, recojo la cuerda y me subo en su lomo de la manera mas torpe, mas como un bulto que como jinete.

Quedo mirando la carreta. Tal vez lo mas digno seria no huir, pero el instinto me ha obligado a aferrarme a esta, tal vez la última chance de este estúpido ardid. De mis ojos corren lagrimas de impotencia. En cuanto siento que estoy balanceado, el corcel comienza a galopar suavemente, dejando atrás los arbustos, los esclavistas y a aquellos que no pude liberar. El oso jadeando y al trote aparece en una esquina de mi campo de visión. Viene tras de mí aunque le cuesta aumentar el ritmo. Entonces, grito con todas mis fuerzas obligando a que el equino pase de un suave trote a un galope brusco pero constante.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=6 adds=0 stat=2 vs1=5 vs2=10
}
```

La bestia nos persigue pero la batalla seguramente le ha costado mucha energía, por lo que al cabo de un minuto o una eternidad, desiste de su persecución. 

He huido.
He fallado.

El golpeteo de los cascos retumba en mi cabeza. Siento el roce del viento en mi piel y mis heridas abiertas se resienten por el galope. Aun siento la sangre brotar y poco a poco mi vista se nubla. Cierro los ojos entre lagrimas mientras el sonido incesante de los sollozos y suplicas de las personas de la carroza me acompaña a la vez que mi consciencia me abandona.

```iron-vault-mechanics
move "[Forsake Your Vow](datasworn:move:classic\/quest\/forsake_your_vow)"
```

- *He perdido la oportunidad de liberar a mis hermanos ~~([[Free the Slaves from the Transport]])
- _Slayer is no longer available as a path_