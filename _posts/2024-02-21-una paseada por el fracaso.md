---
title: Una paseada por el fracaso
date: "2024-02-21"
image: /assets/img/covers/una-paseada-por-el-fracaso.png
categories: [Blogging, Personal Notes]
tags: [abandoned, projects]
---

Hace unos meses, estuve pasando por una etapa bastante mala donde mi estrés se fue por las nubes y mi moral por los suelos. Llevaba varias semanas soportando una alta carga de trabajo y llegó un punto donde no podía más con ello. De una forma u otra, mi cabeza me hizo recordar todas aquellas veces que he abandonado proyectos por el motivo que fuera y en definitiva acabé con la moral muy baja para seguir con los actuales.

Justo por ese momento, me llegó un correo de que el Twitter Archive que había solicitado unos días antes ya estaba listo y al descargármelo me puse a ver que imágenes tenía subidas por ahí. Entre todo ese contenido, había un montón de clips de proyectos publiqué, pero entre ellos también otros tantos de proyectos donde *fracasé*.

Sorprendentemente, en vez de hacerme sentir peor, mirar esos clips me hizo sentir mejor. No me puse a pensar en el dolor del abandono del proyecto, más bien me ponía a pensar en todo lo que trabajar en él me había aportado a mí.

Es por eso, que en noviembre decidí dar una mini charla en el [Barcelona Game Creators](https://www.meetup.com/barcelona-game-creators/){:target="_blank"} para hablar de todos estos proyectos, pero (casualmente) fracasé en prepararla. Y no ha sido hasta este febrero que no he vuelto a encontrar el tiempo para hacerla.

Pues lo dicho, todo lo que hay en este post son aquellos juegos y proyectos que no aparecen en mi porfolio (y tengo material suyo), todo aquello que en algún momento existió y en otro momento desapareció, procedo a empezar esta paseada por el fracaso.

## Enero 2019 - El inicio

Algunas veces, cuando me preguntan cuando empecé a usar Unity, les respondo que empecé alrededor de mis 11 o 12 años, más o menos entre el paso de primaria a secundaria. Si bien esto es 3 años antes de esta fecha del título, la verdad es que es una aproximación que hago, ya que nunca llegué a guardar ningún proyecto de los que hice, por lo que no sé cuando empecé con exactitud, pero sí que sé que un enero de 2019 estaba subiendo este vídeo.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="start" %}

Hasta donde yo recuerdo, esto era más o menos una especie de Super Smash Bros, pero con bolas que se disparan. Pero del que sí que recuerdo seguro, es el porqué lo abandoné. El enemigo para moverse había que meterle una IA bastante compleja para ello, pero como alumno de 3º de ESO, esta tarea se me hizo imposible de hacer y por motivos más que obvios hubo que abandonarlo.

## Plataformero en 3D

Poco tiempo después de abandonar el juego de las pelotas, participé a la [Wowie Jam!](https://itch.io/jam/wowie-jam){:target="_blank"}, donde me hizo subir la moral por las nubes y me hizo creer que ya era profesional (ni siquiera ahora me considero uno).

Todo esto, me llevó a hacer un plataformero 3D ampliamente inspirado por el Super Mario 3D Land, uno de los primeros videojuegos a los que jugué.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="first_platformer" %}

En realidad, llegaron a haber más enemigos de los que se ven al video, que yo recuerde eran por lo menos un par de tipos de Bill Bala y puede que algún extra. Además, el personaje iba con un cuchillo porque todos los enemigos eran alimentos, como si estuviera en una cocina. Pero igual que el anterior, eventualmente se me empezó a hacer demasiado difícil trabajar en el juego y lo abandoné.

## Bullet Hell

Al cabo de poco, me puse de nuevo al lío, esta vez con un bullet hell en 2D. Donde me centré bastante en el game feel y realmente esta vez sí que parecía que había acertado el scope del proyecto.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="bullet_hell_1" %}

De este juego me acuerdo de varias cosas graciosas, una de ellas es que no sabía como limitar la velocidad de disparos, por lo que se me ocurrió meter una cadencia suficientemente exagerada como para que al jugador le mereciera más la pena mantener pulsado que pulsar muchas veces. Aunque sí que es verdad que posteriormente lo trasladé a móvil y este ahí no podías pulsar individualmente cada disparo.

Una cosa que aprendí aquí que realmente aprecio mucho de este desarrollo es el object pooling. Durante el desarrollo del juego me encontré que eventualmente acababas llegando a un punto donde el lag hacía imposible jugar, por lo que investigando por qué era me enteré de que era culpa de instanciar muchas cosas y que el object pooling era la solución. Gracias a esto ya empecé a salir cada vez más de mi zona de confort en busca de nuevas formas de programar las cosas y hacerlo mejor.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="bullet_hell_2" %}

Le mejoré bastante el apartado visual, mezclando muchos assets de la asset store y de opengameart, pero la verdad es que me lo trabajé mucho el cómo se tenía que ver.

Desafortunadamente, poco a poco se me fue yendo el scope del juego y eventualmente la cantidad de código espagueti del juego me hizo imposible seguir trabajando en él.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="bullet_hell_3" %}

## Plataformero en 2D

En pleno verano de 2020, después de todas las jams a las que participé durante el confinamiento, empecé un “pequeño experimento”. Me propuse el reto de hacer una escena donde todo el arte fuese hecho usando un solo sprite, el cuadrado blanco por defecto del Unity.

Este experimento fue tal que así:

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_1" %}

Realmente acabé muy sorprendido de como había quedado, así que decidí seguir con ello, metiéndole el máximo detalle posible al juego. Creía haber encontrado mi artista interior.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_2" %}

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_3" %}

Aquí ya se empezaba a notar que el scope se me estaba yendo, solo por decidir meterle un ciclo día noche, pero me daba igual, el juego se veía bonito y no perdía las ganas de trabajar en él.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_4" %}

Le hice este pueblo, donde no había ninguna persona, pero las animaciones del entorno le daba mucha vida a este.

No guardo ningún clip de esto, pero la ropa que estaba colgada entre los edificios tenía incluso una animación donde la recogían.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_5" %}

Y luego creé a mi primer personaje, Don Cartelón. Este personaje tuvo la primera versión de un sistema de diálogos que proyecto tras proyecto fui mejorando hasta llegar a la versión que estoy usando actualmente en Just in Crime.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_6" %}

Y luego creé a Artacho, porque “era un armario con un mostacho”

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_7" %}

Luego seguí con la mejora del sistema de diálogos, donde le añadí soporte a emociones.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_8" %}

Y finalmente todo terminó con el añadido del personaje principal del juego.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="geometry_9" %}

Desgraciadamente, cometí uno de los errores de los que más me arrepiento de mi camino como desarrollador, no proteger mi trabajo. Este juego es de mis proyectos personales más queridos hasta la fecha, no hice ninguna copia de seguridad durante el desarrollo.

Un buen día me levanté y al encender el ordenador, a causa de un bug muy raro, OneDrive empezó a modificar datos de archivos y crear duplicados corrompidos, en definitiva, perdí el proyecto.

Seguí guardando la carpeta del proyecto de todas formas, con la esperanza de que un día conseguiría encontrar la forma de recuperar este proyecto. Y la encontré, dos años más tarde conseguí recuperar el proyecto, pero las ganas de trabajar con él desgraciadamente se desvanecieron y no lo he vuelto a tocar desde entonces.

## Porfolio jugable

Hacia finales de 2020 empecé a darle vueltas a la idea de hacer una versión de mi porfolio que fuera jugable, pillé algún que otro asset de internet y me puse con la idea.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="portfolio_1" %}

La idea no salía como yo me imaginaba en mi cabeza. Quería que fuese algo divertido, pero en vez de eso, era bastante aburrido sinceramente.

Aun así, un tiempo más tarde lo volví a intentar. Esta vez me inspiré por el estilo de Manifold Garden, para hacer que fuese un arte asequible para mí y que a la vez pegase un poco con la estética de exposición.

![Portfolio](/assets/img/personal/una-paseada-por-el-fracaso/portfolio_2.jpg){: .center }

Pero esto no impidió que me aburriese de nuevo y el proyecto se quedase completamente en el olvido.

## Secret Santa Jam

Por la Navidad de 2020, me apunté a la [Secret Santa Jam](https://itch.io/jam/secret-santa){:target="_blank"}, una jam donde en vez de haber un tema, tú recibes una carta que supuestamente iba dirigida a “Papá Noel” y entonces tú tienes que hacerte pasar por él y crear un juego acorde con esa carta para que luego el día de Navidad le llegue este regalo.

Pues mi scope para esta jam desde un buen inicio se fue más allá de las nubes y volví con un plataformero 3D con todo lo que había aprendido hasta el momento.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="platformer_1" %}

Hasta aquí parece un juego bastante normal, pero luego hay la parte donde invertí tiempo sin mucho sentido.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="platformer_2" %}

Estuve siendo inspirado por el Super Mario Odyssey y toda la expresividad que este juego le da al jugador con las habilidades de Mario.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="platformer_3" %}

Y una vez con las mecánicas hechas, me puse a avanzar con las animaciones, las cuales le dieron mucha más vida.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="platformer_4" %}

Y aún más mecánicas que le añadí, hasta tener el gameplay base completo.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="platformer_5" %}

Finalmente, me puse con el diseño de niveles para el juego con un montón de assets de [Kenney](https://www.kenney.nl/){:target="_blank"}.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="platformer_6" %}

Pero desgraciadamente el diseño de niveles es de mis puntos más débiles, siempre me quedo atascado cuando toca hacerlo. Así como con el arte y la música puedo llegar a hacer un apaño, el diseño de niveles me drena la energía de una forma espectacular.

Así que este juego también lo abandoné. Pero a diferencia de otros, donde el único afectado era yo, este juego iba dirigido a otra persona y solo con pensar en que una persona iba a quedarse sin su regalo de Navidad, me dolía el alma.

Pero bueno, aprendí un montón de cosas nuevas. Algo que agradezco  mucho de lo que hice en la jam, es la cantidad de experimentos con herramientas que hice.

## El juego de las letras

Pasado el deadline de la jam, para animarme, me propuse hacer un juego pequeñito para mí mismo, igual que hice con la [Brackeys Jam](https://gerardgascon.com/jams/Chess-II-Counterattack){:target="_blank"}, la idea de este juego era volver a hacer todos los assets yo solo. Y conseguí un resultado bastante guay.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="abc_1" %}

Me lo planteé como si fuera una jam, y se supone que tenía que terminarlo para año nuevo, pero me volví a atascar en el diseño de niveles y lo abandoné. Un año más tarde lo intenté retomar, le hice un par de niveles nuevos y me volví a atascar.

El año pasado finalmente me puse “en serio” y lo intenté terminar, le retoqué algunos niveles, le metí nuevas mecánicas y el juego se quedó tal que así.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="abc_2" %}

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="abc_3" %}

Desgraciadamente, me vino un volumen bastante grande de tareas que hacer y tuve que abandonar de nuevo el proyecto, ojalá este año sea el año en el que finalmente lo termine. Realmente era muy simpático el juego…

## RetroJam 2021

El año 2021 fue marcado por la Mega Drive. Mientras estaba aprendiendo como programar para ella, decidí apuntarme a la retro jam, ya que consideraba que era un buen sitio donde practicar como funcionaba la consola.

Así que me puse a ello y empecé a hacer un roguelike tipo Binding of Isaac, pero con movimiento por cuadrícula.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="roguelike_1" %}

Luego de esto me puse a hacer la generación de las salas, la cual sería bastante sencilla de hacer en un motor de videojuegos actual, pero la falta de experiencia trabajando con C, hizo que me liase.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="roguelike_2" %}

Aunque en un principio pareciese funcionar, perdía mucho tiempo con movidas con las que nunca me había pegado y al final decidí abandonarlo, dejando el juego en este estado:

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="roguelike_3" %}

![roguelike](/assets/img/personal/una-paseada-por-el-fracaso/roguelike_4.png){: .center }
_Elenco de enemigos que iban a estar presentes en el juego_

Aun así, no todo estaba perdido. En un último esfuerzo para intentar salvar la jam y presentar algo, desarrollé este prototipo, donde había que disparar al personaje que el juego te dijera.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="roguelike_5" %}

Pero desgraciadamente no sirvió de nada, ya que se acabó el tiempo y todo mi trabajo se quedó en nada.

## Bullet Hell Jam

Al cabo de un tiempo, me apunté a otra jam, aquí tenías que hacer un bullet hell. A mí se me ocurrió la idea de hacer un bullet hell sin enemigos, donde “luchas contra ti mismo”.

La idea estaba graciosa, así que me puse a prototipar con ella.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="chaotic_shooter_1" %}

Pero un bullet hell es sinónimo de caos, así que le añadí un *poquito* de caos.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="chaotic_shooter_2" %}

Y finalmente el juego terminó viéndose así.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="chaotic_shooter_3" %}

En este punto vi que el juego tampoco me motivaba tanto y rápidamente lo abandoné, la idea parecía interesante, pero ejecutarla bien ya era otra historia, así que se quedó con una anécdota curiosa de mis jams.

## Mini Jam 83

De esta jam tengo muy poco del que hablar, ya que la empecé y la abandoné a una velocidad récord. Básicamente, para resumir este juego: DOOM y ZX Spectrum tienen un hijo y este hijo tiene espadas y dados.

Los ítems de este juego iban a ser randomizados con un dado que podías llevar en cualquier momento, si querías la espada, el dado tenía que darte una espada y así con todas las armas.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="doom_like" %}

Pero aquí tuve un golpe de conciencia, tenía otro proyecto donde le debía estar dedicando este tiempo. Así que abandoné el juego para volver a ello.

Otra jam anecdótica más.

## ¿Alguien ha dicho Wii?

A principios de septiembre de 2021 se me ocurrió intentar trastear con la Wii, ya que con la Mega Drive no había suficiente. No sé cómo lo hice, pero lo conseguí, reemplacé el editor de Miis del menú Home por un juego propio.

![wii_game_1](/assets/img/personal/una-paseada-por-el-fracaso/wii_game_1.jpg){: .center}
_Primera prueba de build funcionando en dolphin_

![wii_game_2](/assets/img/personal/una-paseada-por-el-fracaso/wii_game_2.jpg){: .center w="300"}
_Primera prueba funcionando en una vWii (Wii U)_

Y luego de esto me puse a hacer un juego de encontrar al malo y dispararlo, igual que lo que intenté hacer en la Mega Drive.

Pero después de esto lo abandoné por qué lo veía sin ningún tipo de futuro más allá de poder presumir de haberlo logrado, así que obviamente lo abandoné sin más.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="wii_game_3" %}

## Miner Mole

En el bachillerato de Cataluña hay un proyecto que se llama *treball de recerca* dónde hay que hacer una investigación sobre el tema que te apetezca (y cuenta nota). En mi caso decidí desarrollar un juego para la Sega Mega Drive usando [SGDK](https://github.com/Stephane-D/SGDK){:target="_blank"}.

Pues todo empieza cuando un buen día, mientras estaba comiendo en casa de los abuelos, vi que había una caja con la imagen del Sonic clásico, cuando les pregunté que era eso me respondieron que era una consola, como si todo el mundo lo supiera y la iban a tirar porque nadie la usaba. Obviamente, no tenía ni idea que me habían estado escondiendo una consola y me apoderé de ella, entonces de aquí surgió la idea de trastear con ella (Y dedicarle unas horas al Sonic The Hedgehog y al Streets of Rage).

Como poco antes de empezar con esto, había estado jugando al Shovel Knight (juegazo por cierto), no me lie demasiado y cogí *prestada* la mecánica principal del juego. Así es como nació este pequeño proyecto que duraría meses.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_1" %}

Y aquí está uno de los primeros clips del juego, obviamente no tenía ni idea de lo que hacía y tuve que reiniciarlo porque estaba empezando la casa por el tejado y esto se iba a convertir en un lío enorme.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_2" %}

Y aquí está el primer prototipo de verdad del juego, donde empecé a montar mi propio sistema de físicas desde cero.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_3" %}

Y fue un trabajo de ensayo y error muy duro, ya que venir de Unity, donde lo tienes todo prácticamente montado, a no tener nada, hay muchísima diferencia.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_4" %}

Y con ya varios meses a la espalda, aquí viene el primer gran paso, el momento donde doy por terminado las físicas y empiezo a programar una cosa distinta, el movimiento de la cámara.

Por suerte SGDK tenía una librería implementada para eso, pero tardé semanas en darme cuenta de que existía.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_5" %}

Y así llegó una cantidad enorme de pruebas de dibujado del nivel y volvía a estar medio atascado con ello.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_6" %}

Por suerte, unos meses más tarde conseguí solucionar el problema y el juego hizo un salto técnico bastante elevado, aunque aparecieron nuevos problemas…

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_7" %}

Hasta que le añadí los enemigos y a partir de entonces el desarrollo empezó a acelerar.

Como curiosidad que se ve en este vídeo, la flechita de la izquierda es el consumo de CPU, cuanto más arriba, menos consumo y cuanto más abajo, más consumo.

![character_1](/assets/img/personal/una-paseada-por-el-fracaso/miner_mole_character_1.jpg){: .center w="300" }

En algún punto del desarrollo, dibujé a este personaje de aquí, como no tenía del todo claro como iba a ser, dibujé a este personajillo encapuchado. Me salió algo curioso, pero no acababa de ser lo que buscaba para el juego.

Más adelante, cuando ya estaba más que decidido que iba a usar la mecánica del Shovel Knight, decidí que la protagonista iba a ser una chica minera. Pero un buen día de julio hablando con mi primo, él me propuso por qué no hacía que el personaje fuese un topo.

![character_2](/assets/img/personal/una-paseada-por-el-fracaso/miner_mole_character_2.jpg){: .center w="300"}
_Primer diseño del topo_

Y unos días más tarde lo pulí un poco más para que se viera mejor de que iba a ir la cosa.

![character_3](/assets/img/personal/una-paseada-por-el-fracaso/miner_mole_character_3.jpg){: .center w="300"}

Después de esto, se lo mandé a un artista con el que había participado previamente a una jam para que me dibujase un spritesheet bien chulo.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_8" %}

Y aquí el juego ya empezaba a tener su estructura montada, con la carga y descarga de los niveles (con memory leaks incluidos, claro).

Fue más o menos por este momento que se abrió la convocatoria del [IndieDevDay](https://www.indiedevday.es/){:target="_blank"} 2021 y como todo desarrollador, decidí intentar preparar algo y mandar el juego, el problema es que casi todo lo que usaba eran prototipos y el personaje aún no estaba dibujado, por lo que obviamente rechazaron mi juego y no pude exponerlo. Pero bueno, el desarrollo siguió hacia adelante y a finales de agosto, principios de septiembre, tenía esto:

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_9" %}

Aquí ya estaba el famoso topo, comisionado a [FJLink](https://twitter.com/pipasdefranilla){:target="_blank"}, ahora sí que ya molaba mucho el juego. Pero también fue por entonces que volvieron las clases, tuve que empezar la redacción del trabajo y el desarrollo empezó a ralentizarse.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_10" %}

Pero eso no quita que el juego fuese avanzando pasito a pasito.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_11" %}

Le estuve añadiendo nuevos niveles, donde intentaba en cada uno de ellos meterle un efecto distinto en el scroll, que reflejase las capacidades de la consola.

{% include videos.html folder="personal/una-paseada-por-el-fracaso" name="miner_mole_12" %}

Ya sea por bueno o por malo, a mí me gusta sacar las cosas con un lacito bien bonito y poder decir orgullosamente que yo he trabajado en eso, aunque a veces me he arrepentido de trabajar en algunos juegos (entonces los [escondo](https://itch.io/c/1557951/other-other-game-jams){:target="_blank"}).

En este caso, le había dedicado un esfuerzo como el que nunca antes había hecho y no veía ninguna forma posible de lanzar este juego (que tenía la idea que fuera gratis) sin ese lacito tan bonito.

Es por eso que nunca lo llegué a lanzar, aunque tenga 4 niveles creados con sus enemigos y tal, no tiene ese lacito que hace que el juego esté cerrado, tal y como está ahora simplemente termina porque no hay más contenido.

De hecho, durante la [IndieSpainJam 2023](https://itch.io/jam/indie-spain-jam-23){:target="_blank"}, me animé a empezar a hacer streams en Twitch. Una vez terminada la jam, me propuse dedicarle el directo semanal a avanzar en un proyecto abandonado, como lo es este mismo.

![miner_mole_boss](/assets/img/personal/una-paseada-por-el-fracaso/miner_mole_boss.png){: .center }

Y esto fue lo que decidí con mi único espectadore, un conejo (enemigo natural de los topos), que cava agujeros y lanza bombas (típico de un conejo totalmente normal).

Pero luego ocurrieron un montón de cosas que me llevaron a lo que he contado al inicio de este extenso post, me empecé a sentir fatal con el abandono de proyectos y esta fue una de las cosas que más me dolió, ver que este conejo no se mueve.

## Una consola no tan fantástica

Las consolas fantásticas ([*fantasy consoles*](https://en.wikipedia.org/wiki/Fantasy_video_game_console)), son un tema que me fascina. Me encanta que existan sistemas como PICO-8 u [otros](https://github.com/paladin-t/fantasy), con unas limitaciones propias que simplemente existen porque a los desarrolladores les apetece.

Toda la comunidad que las rodea me parece fascinante y, aunque nunca me he metido en ella, siempre ha sido un tema con el que he querido trastear. Pues un buen día me levanté inspirado por un maravilloso vídeo de [Ben Eater](https://youtu.be/l7rce6IQDWs), en este vídeo, él hablaba de como montar una tarjeta gráfica que funcionaba en unas breadboards.

A mí me entraron muchísimas ganas de hacer una yo, diseñar una tarjeta gráfica ampliamente inspirada por su diseño. En esta modificación mía, le aumentaba un poco la resolución y hacía que fuera de 1-bit, reduciendo su tamaño de la memoria a solo 4 kB.

![graphics_card](/assets/img/personal/una-paseada-por-el-fracaso/graphics_card_6.jpg){: .center w="300" }
_La gráfica renderizando la RAM sin inicializar_

![graphics_card](/assets/img/personal/una-paseada-por-el-fracaso/graphics_card_1.jpg){: .center }
_Render de prueba en la tarjeta gráfica_

Pero todo esto no se iba a quedar aquí, la idea era hacer un sistema modular, tipo el [RC2014](https://rc2014.co.uk/) y que cada módulo fuese testeable individualmente con un Arduino. Algo que sonaba espectacular en mi cabeza.

![graphics_card](/assets/img/personal/una-paseada-por-el-fracaso/graphics_card_2.png){: .center }
_Visualización 3D de la PCB diseñada de la tarjeta gráfica_

Luego empecé a diseñar otras partes, la tarjeta de sonido, compuesta por 555 timers. Y la tarjeta de la CPU, usando el 65C02, aunque estuve dudando de si usar un procesador Z80.

![graphics_card](/assets/img/personal/una-paseada-por-el-fracaso/graphics_card_3.png){: .center }
_Diseño base de la tarjeta de sonido_

![graphics_card](/assets/img/personal/una-paseada-por-el-fracaso/graphics_card_4.png){: .center }
_Diseño base de la tarjeta de la CPU_

La idea inicial de esto era poder montar un mini sistema modular en el que poder crear videojuegos muy simples que pudieran funcionar con tanta limitación, ampliamente basado en las consolas fantásticas, pero con el "giro" de que esto era real.

El problema principal que tuve, era que cada prototipo en breadboard me costaba cerca de 50 €. No me podía permitir crear un sistema por el amor al arte y gastarme tanto dinero de por medio.

![graphics_card](/assets/img/personal/una-paseada-por-el-fracaso/graphics_card_5.jpg){: .center w="300" }
_Pantalla falsa de BASIC para probar el renderizado de carácteres_

Así que, obviamente, todo esto tuvo que aparcarlo en algún sitio y cruzar dedos por un día poder seguir con ello. Pero ese día nunca ha llegado.

## Dibujando a compañeros

Ya sé que parecía que desde la Indie Spain Jam, con tan poco tiempo de por medio y con tanta experiencia abandonando proyectos, no me daría tiempo a empezar y abandonar otro proyecto, ¿no? Pues sorpresa, esto fue lo que hice en Navidad.

Esta pasada Navidad se me ocurrió montarme mi propia Secret Santa Jam para mí mismo, donde les hacía un regalo a par de amigos a los que quiero mucho. Se me ocurrió una idea bastante absurda, pero al final lo que importa de los regalos, al menos para mí, es que les saque una sonrisa.

La idea era, “ya que yo no sé dibujar, ¿por qué no lo dibujan ellos que son artistas?”. Exacto, iba a hacer un proyectito donde ellos tenían que dibujar, nombrar y doblar a tantos gatitos o monstruitos como quisieran. Luego, todos estos se estarían moviendo por la pantalla.

![drawing_companion_1](/assets/img/personal/una-paseada-por-el-fracaso/drawing_companion_1.png){: .center }

Aquí está el primer ejército de los *bichobolas*.

Todo esto fue progresando bastante bien, hasta que ya casi lo tenía todo hecho.

![drawing_companion_2](/assets/img/personal/una-paseada-por-el-fracaso/drawing_companion_2.png){: .center }

Pero desgraciadamente llegó el punto donde lo tuve que abandonar porque se me estaban acercando peligrosamente los exámenes finales y desgraciadamente no les pude hacer el regalo porque no tenía ese *lacito*.

## Todo pasa

Un buen día, cuando *supuestamente* tenía 11 años, hice la conexión de que si los videojuegos los creaban personas, yo podría ser una de esas personas. Desde ese momento y con todos los altos y bajos por los que he pasado de por medio, no me arrepiento de nada de lo que he hecho.

Todo lo que he creado y todo lo que he abandonado ha sido el combustible que me ha dado la capacidad de aprender todo lo que he aprendido y nunca dejaré de crear cosas. Porque siempre habrá una oportunidad de fracasar y aprender de ello como si fuera la primera vez que lo hago.

Este “ejercicio” que he hecho de buscar todo aquello con lo que he “fracasado” en vez de hacerme sentir mal, como sería lo obvio por el nombre de la acción, me ha hecho sentir muy feliz en pensar lo bien que lo pasé en muchos de estos desarrollos. Aunque el hecho de abandonar un proyecto siempre sea algo difícil de celebrar, pensar que estos proyectos normalmente son donde más experimento y donde más aprendo, me anima a seguir con aquello que estoy haciendo y nunca olvidar aquello que he hecho.

![end](/assets/img/personal/una-paseada-por-el-fracaso/end.jpg){: .center }

Con todo esto, animo a todo el mundo a intentar encontrar aquello con lo que ha fracasado y reírse de ello, porque sin esos proyectos, lo más seguro es que nadie estaría donde está. Así que con esto termino esta paseada y me vuelvo a mi cueva para seguir triunfando en el fracaso.
