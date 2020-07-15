# TEMPLATE GUIONES VIDEO JOURNAL

**INTRODUCCION**

Bienvenidos a un nuevo resumen mensual de Decred en Español, soy Victor, contratista de Decred. Y como siempre, vamos a repasar todas las novedades de este último mes.

**RESUMEN DEL MES**

Este mes tenemos dos novedades importantes. La primera es que el DEX sigue avanzando y si bien ya hablamos del DEX en videos pasados, este es sin lugar a dudas uno de los desarrollos más esperados por la comunidad y va a seguir dando que hablar, incluso después de su lanzamiento. La segunda es la implementación de Rosetta, un nuevo estándar desarrollado por Coinbase para facilitarle a toda clase de desarrolladores la integración de distintas blockchains, como la de Decred o Bitcoin, a sus proyectos.

Otros temas del día:

- Gobernanza: una nueva propuesta pasó por Politeia y ahora otra está en discusión.
- Desarrollo: hubo avances en los repositorios de Politeia, Decrediton y el nuevo vspd
- Integraciones: Staking desde un exchange: ¿qué pasó con el servicio que comenzó a ofrecer KuCoin? Richard Red publico algunos números y vamos a ver si vale la pena.
- Eventos: Y como siempre, cerramos con el resumen de eventos que organizamos desde Decred en Español

¡Arrancamos con este resumen!

**LA NOVEDAD**

**Primera novedad**

Marco Peereboom, quien actualmente trabaja en el proyecto de descentralización del Tesoro, sobre el cual ya hablamos y les dejamos el link acá abajo, no paró de tuitear imágenes del Exchange Descentralizado.

https://twitter.com/marco_peereboom/status/1281045287243526144
https://twitter.com/marco_peereboom/status/1281411509273460736
https://twitter.com/marco_peereboom/status/1281597635690934274
https://twitter.com/marco_peereboom/status/1281991382970912768
https://twitter.com/marco_peereboom/status/1282380511550279681/photo/1

Según parece, ¡el DEX ya estaría preparado para sus primeras pruebas en la red principal de Decred! Según comentó Jonathan Chappelow, quien está liderando el desarrollo del DEX junto a Buck, estas pruebas comenzarán pronto. A su vez, señaló si bien la interfaz gráfica apenas se mencionó en la propuesta, decidieron expandir el alcance del proyecto y avanzar y que el DEX se vea bien. Lo mismo sucedió con el soporte para clones de Bitcoin como Litecoin y un nuevo algortimo de emparejamiento de órdenes que ya fue implementado. "No fue fácil ni rápido, pero ya esta hecho y es una grán mejora sobre las especificaciones originales", resaltó.

El equipo ya está trabajando en la experiencia de usuario y preparando el DEX para sus primeras pruebas en la red principal.

**Segunda novedad**

La segunda novedad es un tanto inesperada, no es algo que haya tenído gran demanda como el DEX, pero es sin dudas un desarrollo necesario y clave: la integración de Decred a Rosetta, un middleware, una capa intermedia, desarrollado por Coinbase para integrar blockchains a distintos proyectos, de forma segura y sin que los devs tengan que aprender los detalles de cada blockchain.

El nombre Rosetta viene de la Piedra Rosetta, una tabla hallada en 1799 que tiene inscripciones del mismo texto en Griego y en Egipcio y resultó clave para la comprensión de los jeroglíficos egipcios. Haciendo honor a su nombre, Rosetta intenta ser una pieza de software que una distintas blockchains, no en sentido de interoperabilidad, es decir que no permite que las blockchains hablen entre si, sino más bien como un lenguaje común que sirva para comunicarse con blockchains de todo tipo, desde clones de Bitcoin como Litecoin hasta cadenas realmente distintas como lo son Decred y Ethereum.

Si la adopción de Rosetta aumenta, integrar Decred a cualquier proyecto estará al alcance de cualquier desarrollador.

Saludos a Matheus, un dev de Brazil y quien actualmente lidera el desarrollo de Lightning Network, que se encargó de esta integración.

**GOBERNANZA**

Link al tesoro: https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx?txntype=merged_debit

Ahora si, pasamos a la segunda sección de este resumen de Junio y vamos a hablar sobre todo relacionado con la gobernanza de Decred.

En Junio, el Tesoro recibió 12.629 DCR y gastó 8.340 DCR, quedando así con cerca de 4.000 DCR arriba del periodo pasado. En ese mismo mes, el precio promedio de DCR fue de 16.05 USD.

En Politeia se presentaron 2 nuevas propuestas:

(Mostrar Politeia Express)
  - @ivandecredfan publicó una propuesta para producir contenido en ruso. Ivan pedía un presupuesto de 1.600 dolares mensuales para dedicarle 20 horas por semana a la producción de videos y otros contenidos como la traducción de artículos escritos. También, solicitaba el pago equivalente al de un mes de trabajo por el trabajo ya realizado. La propuesta comenzó a votarse a principios de julio y fue rechazada con 5.624 votos a favor y 3.093 votos en contra, una aprobación del 35,5%.
  - https://proposals.decred.org/proposals/df11d7ac85061e6a02d6503555e585a1a37fffd82101eeea14670537c951926f
- Por el otro lado, Lindsey, la contratista que asumió la responsabilidad de gestionar el área de Relaciones Públicas de Decred, presentó su segunda propuesta. Luego de seis meses de trabajo que vieron como resultado la aparición de Decred en algunos conocidos medios financieros como Reuters, The New York Times, Forbes y ZeroHedge, así como también en medios especializados en cripto como Cointelegraph y CoinDesk. Según informó Lindsey en su segunda propuesta, consiguió 34 que miembros de Decred aparezcan en 34 artículos (un poco más de 5 artículos por mes), que salieron en 142 publicaciones diferentes. Esta vez, vuelve a solicitar US$ 3.500 por mes para continuar con las operaciones de Relaciones Públicas durante un año entero. {Al momento de grabar este video, la votación todavía no empezó}
  - https://proposals.decred.org/proposals/c81926b1958e54b2f294085da4ab03e9a63223f8ccd32e74a43493bf62de6185

**DESAROLLO**

¿Qué desarrolló Decred este mes? Qué NO desarrolló... Como todos los meses, destacamos lo más importante:

- Decrediton: la billetera de escritorio de Decred, Decrediton, continúa avanzando hacia la próxima versión de Decred, la 1.6, que integrará las herramientas y servicios de privacidad a la interfaz gráfica de Decrediton. Sumado al lanzamiento de vspd que anunciamos el mes pasado, el equipo de desarrolladores sigue dando importantes pasos para ampliar el acceso a estos servicios que hoy solo disfrutan quienes usan dcrwallet desde la terminal. A su vez, el equipo de Decrediton trabajó en el desarrollo de nuevos componentes de React y continúa con la transición hacia pi-ui, el nuevo estándar de diseño basado en Politeia.
- Hablando de Roma, también tenemos novedades sobre Politeia, el foro donde se discuten y votan las propuestas para desarrollar Decred. Este mes se crearon nuevos sistemas para probar las Solicitudes de Propuestas, que sirven para que la comunidad señale proyectos que le gustaría ver, y se mejoró la interfaz de Politeia y el Sistema de Gestión de Contratistas. La experiencia de usuario en Politeia es fundamental para el correcto funcionamiento de Decred, la gobernanza no es solo votar, si no también discutir y, a medida que la comunidad crece, poder filtrar los mejores argumentos a favor y en contra que se dan en cada discusión.
- Por último, el nuevo software para Proveedores de Servicio de Voto lanzado el mes pasado ya está recibiendo actualizaciones. Esta vez se creo una guía de instalación, se agregó un nuevo panel para administradores y mejoró la interfaz gráfica. La funcionalidad principal ya está terminada, ahora los devs se están enfocando en probar y pulir el software para evitar algunos errores al tratar con casos excepcionales. En la red de prueba, vspd ya se utilizó para votar con miles de tickets. Esperamos que pronto llegue a la red principal. ¿Qué proveedor será el primero en implementarlo?

**Integraciones**

Para la última edición de la mensual de Decred, Richard Red, uno de los investigadores contratados por la DAO escribió un pequeño resumen sobre la integración del staking de Decred a KuCoin, uno de los primeros exchanges grandes que ofreció este servicio.

Según explicó, contando hasta fines de junio del 2020, KuCoin compró 213 tickets y 185 de estos votaron. Los primeros fueron comprados en diciembre del 2019, varios meses antes de anunciar el servicio en febrero, cuando a los usuarios se les dio apenas 48 horas para decidir si querían retirar su DCR del exchange o dejarlo para que sea stakeado, con la condición de no poder retirarlo al instante debido a cómo funciona el staking en DCR.

Según informaron algunos usuarios, el retorno de KuCoin ronda el 1,8% anual en DCR, una fracción del 6% anual que paga la red actualmente. Stakear a través de un exchange, parece no ser un buen negocio.

**Eventos**

Este último mes, Decred en Español organizó y participó en 4 eventos. Entre ellos:

1. Junio 25 HablemosDecred 6 "Git y Github: herrmientas de colaboración" https://twitter.com/Decred_ES/status/1275164449448607748 https://www.youtube.com/watch?v=4b0xYYk6xlY
2. Junio 25 "Estafas y Comunidades en Crypto" junto a Bitcoin Embassy https://twitter.com/Decred_ES/status/1275927953801609216 https://twitter.com/bitcoinemb/status/1275494038544646144
3. Julio 2 "La industria Fintech en América Latina: Desafíos Globales" junto a Legal Hackers Medellin y BlockchainEx https://twitter.com/Decred_ES/status/1278368916985741313
4. Julio 3 "Gobiernos por Bloques" con Anibal Garrido y Ezio Rojas en el Viernes Criptográfico https://twitter.com/anibalcripto/status/1278478260716933120

**TRADUCCIONES**

Como todos los meses, pueden leer la traducción del Decred Journal completa en español en el Medium de Decred en Español. Saludos a Franco, quien se encarga de la traducción.

**CREDITOS Y ENGAGEMENT**

1. Estos resumenes en video son el trabajo en conjunto del equipo de Contenidos de Decred en Español. Detrás de escena están Pablito y Nachito, trabajando en la producción y edición de estos videos. Ya está publicado también el primer video de Código Decred, un tutorial sobre Git y pronto se vienen más videos para desarrolladores.
2. Antes de irse, no olviden suscribirse al canal de Youtube de Decred en Español tocando el boton acá abajo y comenten qué les gustaría saber sobre Decred ya que también estamos haciendo videos educativos
3. Nos vemos el mes que viene para otro resumen de Decred en Español
