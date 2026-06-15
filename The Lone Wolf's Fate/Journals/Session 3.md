#### Destinos inesperados

##### *"You're in the hunt of a dangerous beast"

Tan pronto los primeros rayos iluminan las nubes, me dispongo a retomar el camino hacia [[Thornhall]], pero la oscuridad y el frenezi de la huida ademas de las heridas me han obligado a desviarme de terreno conocido.

```iron-vault-mechanics
track name="[[The Lone Wolf's Fate\/Progress\/Find my way back to Thornhall.md|Find my way back to Thornhall]]" status="added"
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=1 adds=0 stat=3 vs1=6 vs2=9
}
move "[Pay the Price](datasworn:move:classic\/fate\/pay_the_price)"
```

Es evidente que el paisaje no me es familiar. La nieve no deja de caer y no puedo ver mas allá de unos cientos de píes. Apenas distingo los helechos que adornan la espesa alfombra blanca creada por el clima de los últimos días. Perdido y con las heridas frescas, tengo que encontrar el rumbo pronto. Decido ubicar un punto alto para darme una idea de hacia donde esta la costa, pero al cabo de un par de horas el viento se vuelve mas intenso y comienza a nevar con mas fuerza. Nuevamente, la situación es peligrosa.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Wits" action=6 adds=0 stat=3 vs1=8 vs2=2
}
```

Intuyendo que se avecina una nevada, busco rápidamente una esquina que me proteja del viento y logro encender un pequeño fuego.

Mientras la nieve golpea con fuerza, mi mente le da vueltas a varias preguntas. Quienes eran los cazadores que atacaron al Wyvern? Que fue lo que hizo esta elfa en mi espalda? Quien era? Realmente había pasado algo en el bosque o fue una alucinación?

La tormenta amaina un poco, miro alrededor para encontrar un punto alto que me permita tener un  mejor panorama. 

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=6 adds=0 stat=3 vs1=9 vs2=7
}
oracle name="Action" result="Avoid" roll=40
oracle name="Descriptor" result="Hidden" roll=85
oracle name="Focus" result="Transport" roll=46
```


Desde este punto no veo mucho mas que el mismo terreno blanco y llano, pero el clima aun impide ubicar un punto de referencia. Lo que logro notar en medio de la nieve que aun cae es el sonido de una carreta y algunos pasos. Tal vez esta sea mi oportunidad de encontrar refugio o una pista que me permita avanzar. 

Manteniendo mi distancia trato de ubicarme paralelo a su dirección. Mi objetivo es determinar que llevan en la carreta y que tipo de hombres escoltan el transporte.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=1 adds=0 stat=3 vs1=2 vs2=4
}
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=1 adds=0 stat=3 vs1=9 vs2=8
}
oracle name="[Pay the Price \/ Pay the Price](datasworn:move.oracle_rollable:classic\/fate\/pay_the_price.pay_the_price)" result="A new danger or foe is revealed." roll=47

```

Veo a 3 hombres. Uno maneja la carreta y otros dos lo escoltan posicionandose adelante y atrás respectivamente. Del transporte cuelga un cuerpo maltrecho que lastimosamente logro identificar y me rompe el corazón. Es el cadaver del viejo [[Morel]]. La plataforma de carga tambien parece tener mas cuerpos que debo asumir como aldeanos de [[Thornhall]], pero tambien hay personas aun vivas, posiblemente antiguos vecinos, algunos de ellos niños. A los hombres no los reconozco pero no es muy difícil asumir que son comerciantes de esclavos.

Me lleno de conjeturas. Pudo ser que luego del ataque de la sombra la villa fuera saqueada por batidores, pero que habria pasado entonces con [[Veloghurst]] y los demas hombres que deje atras? Habran muerto todos? 

Necesito respuestas pero en mi situación actual no seria prudente un ataque frontal. En cualquier caso, juro ante los Dioses que encontrare la manera de liberar a esos aldeanos.

```iron-vault-mechanics
track name="[[The Lone Wolf's Fate\/Progress\/Free the Slaves from the Transport.md|Free the Slaves from the Transport]]" status="added"
move "[Swear an Iron Vow](datasworn:move:classic\/quest\/swear_an_iron_vow)" {
    add 1 "The people of Thornhall"
    roll "Heart" action=1 adds=1 stat=2 vs1=8 vs2=4
}

```

Aunque mi espiritu esta encendido por el deber, mi cuerpo aún esta demasiado debíl y me cuesta seguir el paso del transporte. Mis heridas empiezan a sangrar de nuevo por lo que me veo obligado a detenerme para atenderlas.

```iron-vault-mechanics
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Iron" action=6 adds=0 stat=1 vs1=8 vs2=1
}
```

El tiempo avanza y logro reemplazar el vendaje y ajustarlo de mejor manera. Ahora me dispongo a seguir las marcas de la carreta.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1 "The people of Thornhall"
    roll "Wits" action=1 adds=1 stat=3 vs1=8 vs2=8
}
oracle name="[Pay the Price \/ Pay the Price](datasworn:move.oracle_rollable:classic\/fate\/pay_the_price.pay_the_price)" result="Something of value is lost or destroyed" roll=31

```

Sigo las huellas y en el camino veo harapos, piezas de ropa que tal vez pertenecian al cuerpo que arrastraba la carreta. 

Mas adelante veo algunos lobos que se dan un festín con un cuerpo. 

He de suponer que es el cadaver de [[Morel]] y aunque me afecta ver como los animales dan cuenta de lo que queda de su carne, no tengo mas opción que abandonarlo. Esperar no es una opción, no cuando debo salvar a alguien.

Mientras avanzo, reflexiono sobre las consecuencias de mi decisión. Muy *seguramente, las filas de los horrores de la noche reclamen lo que quede de su cuerpo y alma pues no pude darle el descanso merecido. Es un terror mas que me acompañara hasta la tumba.

La nieve que continua cayendo me dificulta aun mas dar con la carreta. Al menos mis heridas no se han abierto, aunque me intranquiliza que las marcas en el suelo se vuelven mas tenues hasta un punto que ya no estoy seguro de la dirección. Solo me resta consultar con las llamas y tomar un breve descanso aunque eso signifique tener que moverme en la noche.

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=2 adds=0 stat=3 vs1=8 vs2=8
}
```
- Los traficantes notan el brillo de mi pequeña hoguera. 2 de ellos son enviados a asesinarme/capturarme. (likely)
- Llega la noche y con ella los horrores. Soy atacado por muertos vivientes.

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Yes" roll=54
```

La temperatura cae abruptamente. Siento el peso de la travesía y los días sin descanso. Las heridas se recienten y me cuesta entablar una conexión con el fuego. La llama es muy tenue ya que el viento ha tomado mas fuerza. Tengo que persistir o de lo contrario no habra servido de nada desviarme tras la promesa de liberar a mis hermanos. 

[[Trafficker 1]]:
```iron-vault-mechanics
oracle name="[Character \/ Character First Look](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Inhuman" roll=92
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Threatening" roll=86
oracle name="[Character \/ Character Disposition](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Friendly" roll=10

```

Con mi vista anclada en la pequeña fogata, quedo pasmado cuando de una respiración pesada, entre voz y gruñido me dicen:
— Humano. Que buscas en la tormenta lejos de los tuyos??? —
Su voz no carece de hostilidad, así que he de recobrar la compostura y pensar en una buena respuesta.
— He salido a cazar y me he extraviado. Quien eres? —
Me doy la vuelta lentamente.
Veo la figura de un hombre robusto, cubierto por pieles hasta la mitad del rostro y un sombrero de invierno. Solo se ven sus ojos, vacíos y pálidos. No se si son los ojos de un ciego o de un muerto.

```iron-vault-mechanics
move "[Reach a Milestone - He encontrado a uno de los escoltas del transporte](datasworn:move:classic\/quest\/reach_a_milestone)"


```

— Soy un... cazador. Cual es tu presa? —, continua con su voz ronca.
Vacilo ante su respuesta. No creo que sea del todo cierta.
— En realidad, no sé mucho. Solo se que no se puede ver y que ataca a los más débiles... — 
Me doy cuenta de lo ingenuo que fui al salir sin mas pistas o mas información sobre lo que amenaza a mi pueblo. — Te suena familiar? —, pregunto

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Almost Certain](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.almost_certain)" result="Yes" roll=53
```

La respiración pesada continua, pero no responde de inmediato. 
Al cabo de un momento dice.
— No, pero tal vez alguien que conozco tenga una idea —

No esperaba esta respuesta. En realidad estaba sopesando la probabilidad de preparar un arma o huir pero a la luz de esta nueva información, bien valdría la pena morder el anzuelo.
— Seria de gran ayuda cualquier información que pueda conseguir —

Nuevamente, un silencio y la respiración pesada.
— Comprendo. Te guiare hasta mi campamento. Allí tus dudas seran resueltas —

Hay algo muy extraño en este sujeto. Cada vez que habla es como si no comprendiera de inmediato lo que digo y al instante da una respuesta con una voz que no parece suya. 

Deshago la hoguera y en el acto guardo el cuchillo entre los vendajes de mis brazos. Luego, hechamos a andar hombro a hombro. Mi curiosidad me impulsa a continuar la conversación.
— Si no es inoportuna la pregunta, de donde vienes? —

```iron-vault-mechanics
oracle name="[Place Oracles \/ Location Descriptor](datasworn:oracle_rollable:classic\/place\/descriptor)" result="Deep" roll=11
oracle name="Place Oracles \/ Location Focus" result="Vault" roll=12
```

Noto un leve espasmo y veo como se detiene en seco por un momento, pero esta vez con la voz entrecortada.
— Pro. Profundidad. Cripta —
Veo que levanta sus manos enguantadas, como si no las reconociera y de nuevo otro violento espasmo. Despues continua con cierta dificultad:
— Una disculpa. Vengo... Vengo de... — se detiene — Vengo de una mina en las  [[Tempest Hills|Colinas de las Tempestades]] —
— Es una región muy lejana. Que aventuras te han traído hasta este sitio? — 

No responde pero continua su andar y yo le sigo el paso, aunque me abstengo de pronunciar palabra. En cambio opto por concentrarme en mi siguiente movimiento. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=1 adds=0 stat=2 vs1=4 vs2=1
}
```

No hay señales de la carreta, tampoco hay ninguna fuente de luz. Mi arco esta a mis espaldas y en esta situación mi mejor oportunidad es el cuchillo. Debo tenerlo listo en caso de ser necesario.

La criatura se detiene.
— Aquí — dice con su voz grave a la vez que desenfunda un hacha. 

De las sombras emergen otras dos figuras.

[[Trafficker 2]]
```iron-vault-mechanics
oracle name="[Character \/ Character First Look](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Mystical" roll=5
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Inspecting" roll=98
oracle name="[Character \/ Character Disposition](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Suspicious" roll=38

```

La primera se mueve de manera irregular y pausada, como si cojeara. Esta tambien esta toda cubierta de pieles aunque se nota que es de menor estatura. Apunta con un arco en mi dirección. No logro distinguir sus rasgos faciales.

[[Valadena]]
```iron-vault-mechanics
oracle name="[Character \/ Character First Look](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Uncanny" roll=99
oracle name="[Character \/ Character Activity](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Controlling" roll=77
oracle name="[Character \/ Character Disposition](datasworn:oracle_rollable:classic\/character\/descriptor)" result="Hostile" roll=97

```

Pero la última figura es la que captura mi atención por su aura amenazante. Viste pieles y una túnica. A diferencia de los demás no parece estar armada pero lleva una especie de cadenas rotas que cuelgan de sus manos.

— Arrodillate — señala con la voz gutural el humanoide con el hacha.
— Debi suponerlo — menciono mientras escupo al suelo — tendras la decencia al menos de honrar tu palabra y contestar mi pregunta?

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=3 vs2=2
}
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1 "Compel strong hit"
    roll "Wits" action=2 adds=1 stat=3 vs1=3 vs2=2
}

```


Permanece estático con el hacha en su mano. Sin embargo, la respuesta viene de la figura con las cadenas. Es una voz melodiosa y controlada, aunque algo aguda. Sin duda es una mujer.

— Responder tu pregunta me obligara a cortarte la lengua, cazador y de momento no necesito mas carne para mi ejercito. —

De inmediato me surgen aún mas preguntas. Como supo de mi conversación con este sujeto? Cual ejercito? Carne? Es ese el objetivo con el que capturaron a los habitantes de [[Thornhall]]? 

— Es un precio que estoy dispuesto a aceptar. Incluso si he de ir con los Dioses, prefiero hacerlo con mis dudas resueltas. —

— Vaya. Esa es una sensación con la que me identifico plenamente — replica.

Mientras exhala, noto que por un momento baja sus brazos. Los habia mantenido palmas arriba sosteniendo las cadenas, pero en ese instante los dos sujetos bajan la guardia.

Mientras inhala, comienza a acercarse lentamente hacia mi a la vez que sube los brazos. Los dos sujetos nuevamente entran en guardia. 
— Si yo estuviera por morir, tambien estaria ansiosa por encontrar todas las respuestas a los misterios de la vida y la muerte. — 

Mueve su mano y depronto siento un golpe en las piernas.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=6 adds=0 stat=4 vs1=2 vs2=7
}
```


— Como puedes ver, suelo ser un poco impaciente con los esclavos cuando ignoran mis instrucciones —

Comprendo el mensaje y me arrodillo.
— Sera mejor que mantengas la frente en el suelo, pero ten la tranquilidad de que resolveré tus dudas. —

En cuanto pongo mi frente en la nieve, siento la presion de una bota sobre mi cabeza. En el acto pierdo mi equipo y mi arco, salvo mi cuchillo que sigue entre los vendajes de mis manos. Luego me levantan para registrar bajo mi ropa. Trato de esconder un gesto de dolor cuando pasan por mi torso pero tal vez lo han notado.

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="No" roll=33
```

O tal vez no.

Acto seguido me atan pies y manos con la cuerda de mi equipo y con la escolta a mis espaldas, comenzamos a caminar en dirección a unos pequeños arbustos.

— Mencionabas que la criatura que buscas se mueve en forma de niebla y que solo ataca a los mas débiles. Asumo que no han encontrado un rastro de aquellos que son abducidos, verdad? —

— Ninguno — respondo interesado y muy atento.

— Eso.— Continua inmersa en sus pensamientos. — Eso es una entidad fascinante. Por lo que he logrado estudiar, tiene la habilidad de materializarse y desmaterializarse del plano físico, pero eso implica un gasto de energía muy alto. Por ello es que prefiere objetivos que no opongan resistencia. —

Aunque los detalles son importantes, lo mas intrigante es entender como es que ha podido estudiar a esa cosa.

Entre los arbustos noto una tenue luz que me distrae momentaneamente de la conversación. Logro distinguir la carreta y se escuchan algunos sollozos y personas tosiendo.

Ella prosigue interesada:
— Me encantaria tener la oportunidad de experimentar con una entidad de esas, pero es un desafio atraparla. Si demuestras ser un esclavo obediente, hasta te permita ir tras ella. — 

Entonces pregunto mientras avanzamos hacia la luz:
— Como sabes tanto de esa cosa? —

```iron-vault-mechanics
oracle name="Clue" result="Connects to a previosuly unrelated mystery or quest" roll=8
oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Evade" roll=16
oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Momentum" roll=71

```

— Porque en nuestra búsqueda nos hemos topado con cosas ajenas a nuestra realidad. Tomamos nota de la mayoría, en especial de aquellas que nos son útiles y resulta que una de ellas es ese espectro que buscas.  Hace poco lo seguimos hacia una aldea cercana a los bosques — hace una pausa — una aldea vulnerable, desconcertada y con miedo — 

Eso último lo dijo con un sonrisa de satisfacción. 
— Estos asentamientos proveen la materia prima que nos permite continuar con nuestra labor apenas afectando las filas de nuestro ejercito — y señala hacia una serie de monticulos que apenas se ven en la nieve. Allí en el suelo asoman algunos de los cadaveres que venian en el transporte. Su voz continua a mis espaldas mientras estamos a unos metros de la carreta cuya carpa se encuentra sellada con cadenas.

— Creo que me he emocionado con la conversación. Mi escolta ya no tiene nada interesante que aportar y me hacia falta una plática, aunque fuera breve —

```iron-vault-mechanics
move "[Reach a Milestone - He descubierto información relevante a la criatura que azota Thornhall](datasworn:move:classic\/quest\/reach_a_milestone)"
```

Mi situación es precaria pero estoy convencido de que estos aldeanos vienen de [[Thornhall]]. Aunque varias de mis dudas se esclarecen, aún necesito saber como seguían al espectro, pero dudo que la sacerdotisa responda otra de mis preguntas. Por otro lado, para luchar debo liberarme de mis ataduras y hacerme con el cuchillo. Si apenas tengo una oportunidad contra un guerrero normal, los 3 que me rodean me destrozarian en segundos. No. Debo tratar de negociar una salida mientras pienso en un plan para salir de esta.

— Voy a atraverme a pedir que no acabemos esta conversacion de forma prematura. Despues de lo que me has revelado, tengo aun mas dudas. — 
Mostrando mis manos atadas, continuo. 
— Tampoco es que sea una amenaza —

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=1 vs2=4
}
```


— Es una propuesta razonable — dice luego de pensarlo por un momento, tomando asiento en un tocón aun con las palmas arriba. 
— Bueno, que otra duda te aqueja? —

— Me intriga saber como lo siguen —
— No es muy distinto a como lo harías tu si tuvieras que cazar un oso. Usamos una carnada adecuada. —
— Carnada? —
— Si. De seguro habras notado la carreta. —

Es una macabra revelación y la respondió con total displicencia.
— Lo noté pero creí que eran esclavos, no comida —.
— Prefiero verlos por lo que son. Infelices sufriendo incansablemente en una tierra desolada hasta que llegue su hora. Carecen de talento y oportunidades e incluso con ellas no llegarían muy lejos. Mírate —

Me hierve la sangre pues sus palabras hacen eco en mis recientes fallos. Ella nota mi gesto de desaprobación y continua: 
— Lamento que te ofenda la realidad de las cosas pero esos son los hechos. Puede que sean útiles o diestros en diferentes labores, pero el destino nos trajo a este lugar y lo que hacen durante sus vidas nunca sera tan trascendental como su sacrificio.—
— Como es eso? — 
— No vale la pena entrar en detalles, aunque como lo he dicho antes, estamos reclutando un ejercito pues se avecina la guerra final —
— Cual guerra? Contra que enemigo? —
Me mira con pesar.
— La guerra que todos debemos librar. Desde que ocupamos estas tierras hemos sido asediados por los terrores nocturnos. Siempre en desventaja y siempre sumando números a los rangos del enemigo. El [[Lord]] y su orden de caballeros encontraron la manera de hacerles frente. Puede que todo esto suene confuso y despiadado pero te garantizo cazador que tu sacrificio y el de los demás no sera en vano —
— Estoy abrumado. Creo que necesito vomitar —
— Puedes hacerlo aquí, no me molesta. Tampoco es lo mas desagradable que he visto. —

Nuevamente me pongo de rodillas y mientras hago arcadas, pienso en como generar el caos. Es la única forma de generar una oportunidad para salir de esta.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Wits" action=5 adds=0 stat=3 vs1=1 vs2=2
}
```

Mientras vomito la poca comida que aun tengo en la panza, aprovecho que mis brazos siguen atados y que mi cuchillo esta pegado al vendaje de mi piel. Mis movimientos son toscos aunque naturales, y con ellos logro lacerar mi brazo. 

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=2 adds=0 stat=1 vs1=2 vs2=9
}
```


La sangre empieza a fluir a traves de los vendajes. Creo que el corte fue profundo pues al tratar de levantarme me cuesta mantener el equilibrio y siento algo de mareo. Confió que mi acción desesperada atraiga algún depredador.


```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Iron" action=6 adds=0 stat=1 vs1=3 vs2=8
}
```

- Likely:
	- Jauria de lobos.
	- Un oso pardo
- Unlikely:
	- Un Troll
	- Un Frostbound

```iron-vault-mechanics
oracle name="[Ask the Oracle \/ Likely](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.likely)" result="Yes" roll=92
oracle name="[Ask the Oracle \/ 50\/50](datasworn:move.oracle_rollable:classic\/fate\/ask_the_oracle.fifty_fifty)" result="No" roll=49

```

Me siento con algo de dificultad mientras la sangre continua goteando. Mi cabeza duele pero debo hacer tiempo y se me ocurre una pregunta que tal vez debí hacer antes.

— No te preocupa que los cadaveres atraigan carroñeros? —
— En absoluto. Esos cadaverés, como los de los sujetos que me escoltan son apenas recipientes. Llevamos un proceso meticuloso para evitar contratiempos— dice orgullosamente
— Por supuesto ... — digo mientras otra punzada de dolor atraviesa mi cabeza.
— Nadie se ha revelado o resistido? — cada pregunta es menos relevante pero el malestar me impide pensar con claridad

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=4 vs2=4
}
oracle name="[Turning Point Oracles \/ Major Plot Twist](datasworn:oracle_rollable:classic\/turning_point\/major_plot_twist)" result="A secret alliance is revealed." roll=22

```

Un poco decepcionada por la pregunta, contesta:
— Claro, pero pocos son tan dociles y dispuestos a una charala como tú. Aunque debo decir que los que mucho conversan suelen ser los que mas suplican al final — 

Hace una pausa y sentencia:
— Creo que hemos conversado lo suficiente —
Luego se incorpora mientras el sujeto con el hacha me arrastra a empujones hacia la carroza. Depronto escucho que un caballo relincha en las sombras. 

Parece que el plan tuvo éxito.



