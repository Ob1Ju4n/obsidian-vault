#### El Campamento Aislado

— Cual era la mision de [[Ulhe]]? — le pregunto a [[Gethin]] rompiendo el sonido de los cascos de los caballos mientras pisan el suelo mojado. 
— Se unio a los leñadores como infiltrado. Queriamos saber si alguien le esta haciendo más facil el trabajo a los sureños y ahora resulta que se lo han llevado. —
— Y de verdad planean seguirlo? —
— Sabia de los riesgos y no tenemos hombres disponibles, aunque estoy seguro de que [[Eos]] no lo abandonara a su suerte. — 

Tras una pausa, dice:
— Va siendo hora de que prendas una antorcha —

Han pasado alrededor de 2 horas desde que salimos del aserradero en la ribera. El viento sopla debilmente y combinado con la llovizna se siente un frío punzante en la piel que hace resentir mis heridas. 

Al cabo de un rato, el panorama se vuelve algo mas sombrío dando paso a una leve lluvia. [[Gethin]] decide que es un momento oportuno para acampar. Al mirar en dirección norte, apenas se perciben las luces del campamento que dejamos atras. Nos alejamos un poco del río buscando una abertura natural o un claro con arbustos.

Encontramos una pequeña formación rocosa bajo un frondoso arbol y alli acomodamos a los caballos junto con nuestras cosas.

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=3 adds=0 stat=1 vs1=2 vs2=6
}
```
- _Focus: +1 Momentum_

Aunque mojados, logramos pasar una noche tranquila y tan pronto como el cielo cambiaba de color en el horizonte, retomamos el camino.

- _Alguien nota la carreta?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="No" roll=9
```
- _Hay sobrevivientes?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Yes" roll=67
```
- _Que ha sucedido con los soldados?
```iron-vault-mechanics
oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Fortify" roll=75
oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Tool" roll=23

```

El camino avanza al son de una conversacion mundana. Tambien tomamos un par de raciones cuando el sol empieza a calentar el día disipando las nubes mañaneras. Al cabo de unas 5 horas y habiendo entrado en una zona mayormente rocosa, [[Gethin]] reduce el ritmo mientras lanza algunos silbidos:
— Algo no esta bien. No hay ningun soldado montando guardia y ya puedo ver las tiendas del campamento —

El aserradero aislado se extiende por la ribera oeste del río. Hay un promontorio en el centro del lugar sobre el que se levanta una gran cabaña. Al este de la estructura, sobresalen los techos de una docena de tiendas. Del lado opuesto, sobre el promontorio hay otras dos cabañas mas pequeñas y destruidas. Apenas se ven unas estructuras en piedra, probablemente chimeneas. Un siniestro silencio se cierne sobre el sitio y hasta donde se puede observar, no vemos a nadie.

[[Gethin]] se baja del caballo y me entrega sus riendas mientras susurra un plan:
— Me acercare a la cabaña principal, tu busca un sitio para los caballos y la carreta — 

Mientras se dirige sigilosamente hacia el lugar yo me acerco a uno de los arboles mas cercanos.

- _Están los [[Najeźdźca|bandidos]] en las inmediaciones del campamento?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="Si" roll=77
```
- _Que están haciendo?
```iron-vault-mechanics
oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Take" roll=59
oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Relationship" roll=96

```

Logro acercarme sin mayor problema a un árbol donde dejo amarrados los caballos. Tomo el arco y las flechas y empiezo a caminar en la dirección de [[Gethin]] quien ya viene de vuelta.

- _Logró estudiar el lugar sin ser detectado?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Si" roll=99
```

— Alcance a contar seis. Dos estan en la hoguera entre las tiendas cercanas al río, otro estaba entre los arboles. Uno mas esta pescando. En la cabaña principal uno duerme en una silla mientras el otro patrulla por la entrada —
— Pueden haber mas dentro de la cabaña —
— Por eso es que vamos a ir por el que patrulla y lo haremos cantar. Sabes usar el arco? —
— Si — 
— Entonces manos a la obra —

Es un curso de acción más directo de lo que habia pensado. Me recuerda a [[Veloghurst]] quien tampoco suele darle muchas vueltas a una decisión.

Mientras [[Gethin]] vuelve sigilosamente hacia la cabaña yo lo sigo manteniendo una distancia prudente.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=2 adds=0 stat=3 vs1=10 vs2=8
}
```

Pero entonces y sin previo aviso veo que un bandido camina por la parte trasera de la cabaña. Si no hago algo para detenerlo, [[Gethin]] estara en desventaja enfrentandose a 3 hombres a la vez.

```iron-vault-mechanics
track name="[[The Lone Wolf's Fate\/Progress\/Raiders at the Secluded Camp.md|Raiders at the Secluded Camp]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Shadow" action=1 adds=0 stat=1 vs1=7 vs2=7
}

```

Preparo la primera flecha pero las manos aun me tiemblan. Este no es mi arco y tensar la cuerda me resulta endiabladamente dificil y doloroso. El resultado es un tiro totalmente desviado de mi objetivo que desgraciadamente termina alertando al bandido. Este chifla de inmediato acabando con la sorpresa con la que contabamos.
```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Spirit" action=4 adds=0 stat=2 vs1=10 vs2=6
}
```
- _-1 Spirit, -1 Momentum_

El guerrero se acerca corriendo ya con su hacha en la mano, deslizandose por la pequeña pendiente y acortando la distancia en un instante. Se prepara para atacar.


```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Wits" action=5 adds=0 stat=3 vs1=5 vs2=2
}
```

Aprovechando la velocidad con la que se acerca y viendo que le cuesta controlar sus pasos por el suelo resbaladizo, intento recibirlo con un golpe del arco.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Iron" action=3 adds=0 stat=1 vs1=3 vs2=3
}
```

Doy un paso atras tomando el arco por el mango. Flexiono mis rodillas mientras giro levemente mi cadera hacia la derecha y en el instante preciso, traslado toda la energía del golpe hacia mi torso y mis brazos. 

El golpe es seco y contundente. Escucho un crujido y veo como el cuerpo de mi atacante se desploma desgonzado por el suelo. Pienso en deshacerme del arco roto, pero esta en perfectas condiciones, lo que crujió fue el craneo de mi contrincante.

Avanzo hacia la parte mas alta de la pendiente, cuando escucho que [[Gethin]] suelta un rugido.

- _Pudo [[Gethin]] vencer a los bandidos de la entrada?_
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="No" roll=16
```

Al asomarme por la esquina, advierto que se encuentra rodeado por dos individuos.  Otros cuatro se aproximan rápidamente desde un banco de arena, cercano a la orilla del río donde se encuentran las tiendas, varias de ellas por el suelo. Nuestras probabilidades de vencer disminuiran considerablemente si permito que lleguen.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=5 adds=0 stat=2 vs1=2 vs2=1
}
```

Habiendo experimentado el dolor de tensar el arco y sabiendo bien que debo estar concentrado, respiro profundamente, busco apoyo contra la pared de la cabaña y comienzo a disparar. 

Alcanzo a lanzar tres flechas sintiendo el dolor cada vez que jalo la cuerda, pero tomar aire en el momento adecuado ayuda considerablemente. La primera atraviesa el cuello del que lideraba la carga, quien continua dando unos pasos mas antes de caer. La segunda se clava en la pierna de otro que venia tras el, deteniendolo casi que en seco y transformando sus gritos de guerra en alaridos de dolor. El tercero se percata de las saetas y aunque intentó zigzaguear hacia mi, fue más predecible que una liebre y recibio la flecha de lleno en el plexo, cayendo de costado y retorciendose de dolor en el suelo. 

Pero hubo un cuarto que he perdido de vista.

- _Ha sido victorioso [[Gethin]]?_
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Almost Certain](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.almost_certain)" result="Yes" roll=42
```

Tomo una bocanada de aire y mientras preparo el arco para mi siguiente ataque, un cuerpo sale dando tumbos frente a mí. Tras el aparece cubierto de sangre [[Gethin]] arrastrando un cadaver con su brazo izquierdo mientras empuña una lanza en su mano derecha. 

El sujeto se apoya en una rodilla y se levanta con una mirada fiera, llena de adrenalina, buscando el equilibrio en el piso inclinado. 

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=3 adds=0 stat=2 vs1=4 vs2=1
}
```

 [[Ghetin]] deja caer el cadaver al suelo y hace girar el asta con ambas manos y mucha maestría lanzando un corte amplio desde la izquierda que con la punta corta la garganta de su oponente, quien por un instante perdio la concentracion al verme de pie.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll name="[[The Lone Wolf's Fate\/Progress\/Raiders at the Secluded Camp.md|Raiders at the Secluded Camp]]" score=9 vs1=9 vs2=5
}
```
- _You victory is short-lived: (el fugitivo espera una oportunidad para atacar)

```iron-vault-mechanics
move "[Reach a Milestone](datasworn:move:classic\/quest\/reach_a_milestone)"
```
- _[[Help Eos to Prepare Her Village Against The Raiders]]: Hemos encontrado guerreros con vida y eliminado a los asaltantes_


La batalla termina. 

Reviso el perimetro como un centinela intentando dar con el fugitivo pero mas allá de los gritos del bandido que recibio la flecha en su pierna, no noto nada mas. Por su parte [[Gethin]] toca la puerta logrando hablar con  los ocupantes. Al parecer son los soldados que se atrincheraron en la cabaña principal.

— [[Gethin]], este sigue con vida — digo mientras le señalo al sujeto que ahora esta a unos cuantos pies de mi posición y que tiene la rodilla hecha añicos por el impacto de la flecha. 

No recibo respuesta.

- _Esta herido [[Gethin]]?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="No" roll=29
```

Vuelvo la mirada y veo que de la cabaña salen 2 sujetos que sueltan palos y otras herramientas  para intercambiarlos por las armas de los muertos. [[Gethin]] sale despues y se acerca a mi. 
— Prepara la carreta. Necesito que vuelvas a [[The Lone Wolf's Fate/Locations/Greenwark]] tan rápido como sea posible. Uno de los soldados esta herido de gravedad — 
— Seguro. Quiza quieras conversar con este — reitero señalando al hombre que se retuerce de dolor en el suelo
— Yo me encargo —

No toma mucho preparar todo. Junto a tres guerreros nos encargamos de cargar los suministros de la lista que [[The Lone Wolf's Fate/NPCs/Tibor]] entregó a [[Gethin]]. no se bien cuando pero los aullidos de dolor del otro bandido cesan de repente. Cuando la carreta esta llena de herramientas y otros elementos, [[Gethin]] y los hombres acomodan con cuidado el cuerpo maltrecho de un hombre, vendado e inconsciente. Parece haber sufrido varios cortes y tiene una perforación en un costado. Me recuerda a mi hace unos días. 

- _El herido es [[Ulhe]]?
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="No" roll=19
```

- _El herido tiene información relevante sobre la situación de [[Ulhe]] o de los otros prisioneros?_
```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="Yes" roll=80
```


— Vete ahora. A buen ritmo estaras de vuelta en el campamento de la ribera antes de la medianoche —
— Ya mismo —

Pone su brazo en mi hombro y con una expresión muy seria me dice:
— [[Ralfghar]]. No dejes que [[Haleem]] muera. Creo que tiene información vital sobre [[Ulhe]] y los demas prisioneros. —
— Juro que hare todo lo que este a mi alcance — le digo mientras acerco mi cuchillo al pecho en un gesto solemne. 

El asiente con sinceridad y dice:
— Nos vemos pronto —

```iron-vault-mechanics
move "[Swear an Iron Vow](datasworn:move:classic\/quest\/swear_an_iron_vow)" {
    track name="[[The Lone Wolf's Fate\/Progress\/Make sure Haleem survives.md|Make sure Haleem survives]]" status="added"
    roll "Heart" action=6 adds=0 stat=2 vs1=8 vs2=1
}

```

- _Es un voto problemático pues el camino de vuelta ya es conocido por Rhalfgar_

A medida que me alejo, veo que [[Gethin]] y sus hombres preparan sierras y unas largas estacas mientras agrupan a los cadaveres en un mismo sitio. 

Se disponen a erigir una macabra advertencia.
