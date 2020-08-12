# Lightning más cerca de tu celular

**INTRODUCCION**

Bienvenidos a un nuevo resumen mensual de Decred en Español, soy Victor, contratista de Decred y hoy vamos a repasar todas las novedades de estas últimas semanas.

**RESUMEN DEL MES**

Intro a la novedad piola: En la primera parte de este programa vamos a hablar de la implementación de la Lightning Network sobre la red de Decred. Con tantas novedades interesantes como el servicio de privacidad y la descentralización del Tesoro, la red Lightning pasó a segundo plano, pero mucho para contar!

Otros temas del día:

- Gobernanza: Hay muchas propuestas activas en Politeia, la gran mayoría son de marketing, pero no parece haber mucho apoyo por parte de la comunidad.
- Desarrollo: Como siempre, hay importantes novedades de algunos de los principales proyectos: la descentralización del Tesoro, Politeia, el CMS y Decrediton.
- Marketing: últimamente hubo muchas discusiones en torno a las estrategias de marketing ejecutadas desde Decred. Vamos a repasar de qué se estuvo hablando en los chats.
- Eventos: Por último vamos a estar cerrando con los eventos que organizamos desde Decred en Español este mes.

Empezamos con el resumen.

LA NOVEDAD

Hablemos de Lightning Network, la red Lightning.

¿Hacia dónde está yendo la Lightning Network de Decred? Es un tema que ya no parece estar en agenda o al menos no tan visible como antes, pero dcrlnd avanza muy rápido.

https://github.com/decred/dcrlnd/issues/80

https://github.com/decred/dcrlnd/pull/95

Este mes que pasó, parte del código para correr nodos de Lightning en modo Verificación Simple de Pagos fue integrado y siendo revisado. Esto suena complicado, pero lo importante acá es que nos estamos acercando a tener billeteras móviles con Lightning. Pagos instantáneos en nuestros celulares, sin confiar en nadie.

Para quienes no conocen cómo funciona está tecnología, Lightning Network es una solución de segunda capa al problema de la escalabilidad. Esta solución nació en Bitcoin como una forma de tener transacciones "instantáneas", transacciones muy muy rápidas, que le den a los pagos con criptomonedas una experiencia similar a la que hoy tenemos con tarjetas de cŕedito o débito. Enviar el dinero en menos de 10 segundos, agarrar nuestro café e irnos. 

Pero no se queda solamente en esta idea de pagar rápido. Lightning también abre la puerta a nuevas ideas de lo que se puede hacer con los medios de pago tradicionales. Por ejemplo, podríamos "streamear dinero", pasar fondos de una billetera a otra en tiempo real, pagar por segundo, cobrar por segundo.

Pero Lightning Network también tiene desafíos únicos desde una perspectiva de ingeniería de software. ¿Cómo conseguimos más velocidad sin perder la seguridad que ofrece la blockchain? La respuesta fácil es "operá tu propio nodo y listo". Genial, pero ¿podemos hacer eso desde un dispositivo móvil? Ahora, con gran parte de las transacciones pasando por el celular, dejar de lado a estos usuarios no es una opción. Y si bien hoy la blockchain de Decred pesa menos de 4 GBs, no podemos contar con ello en el futuro.

Acá es donde entra el concepto de Verificación Simple de Pagos, Simple Payment Verification o simplemente SPV. Quienes usan Decrediton seguramente vieron que al principio les ofrece dos opciones: correr en modo completo, descargando y validando toda la blockchain, o usar el modo sencillo, SPV. A diferencia del modo completo, donde los nodos descargan toda la blockchain y se requiere una importante capacidad de procesamiento y almacenamiento de datos para que el nodo funciona, el modo sencillo solo verifica los encabezados de los bloques.

Si bien se avanzó mucho desde que Matheus comenzó a trabajar en dcrlnd, el software de la red Lightning de Decred, todavía falta para tener estas billeteras soñadas. Es necesario integrar esta tecnología a las billeteras móviles, crear una experiencia de usuario sencilla y, cómo siempre, probar todo para resolver cualquier problema antes de abrirle las puertas a los usuarios.

**GOBERNANZA**

Link al tesoro: https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx?txntype=merged_debit

Ahora si, pasamos a la segunda sección de este resumen de {Abril }y vamos a hablar sobre todo relacionado con la gobernanza de Decred.

En julio, el Tesoro recibió 13.050 DCR y gastó 16.073 DCR, quedando así con cerca de 3.000 DCR menos que el periodo pasado. Este mes, el precio promedio de DCR fue de 15,13 USD.

Este mes hubo muchísima actividad en Politeia y se presentaron 6 nuevas propuestas:

- Posters de Realidad Aumentada: Esta en discusión la propuesta de @mission para crear posters de realidad aumentada. En esta solicita US$ 15.000 para crear 10 posters, a US$ 1.500 cada uno. La comunidad no encontró forma de verificar la calidad de los posters y si realmente valen lo que se está pagando. 
- Propuesta de Moderación de Redes Sociales: Esta propuesta fue publicada por @bee, quien tiene la identidad de Politeia con mayor actividad en la historia de la plataforma. Acá propone decidir sobre la creación de un presupuesto de US$ 9.000, pero de los que se estima gastar solo US$ 4.800 para pagarle a los contratistas que colaboren con la moderación de las distintas plataformas de comunicación de la comunidad de Decred, desde las salas de Matrix donde se trabaja hasta canales de redes sociales como Telegram. De no aprobarse esta propuesta, los contratistas no podrán facturar por su trabajo de moderación hasta que una mejor propuesta sea aprobada en Politeia. Cabe destacar que @bee ya no es parte de la propuesta y solo la está organizando para que la comunidad tome una decisión clara sobre el tema.
- Marketing con una agencia de viajes: el usuario @travelbyben, en representación de Travala.com y TravelByBit.com presentó una propuestas pidiendo US$ 51.000 para integrar DCR como medio de pago a ambos sitios web y lanzar una campaña de marketing para anunciar la integración. El problema es que según fue aclarado en el chat, los sistemas de ambos sitios ya tienen un procesador de pagos que permitiría usar DCR. Para decirlo claro: están pidiendo dinero principalmente para financiar la campaña de marketing porque las dos integraciones de US$ 15.000 que hacen al grueso de la propuesta no se justifican sabiendo que solo es cuestión de activar la opción. La mayoría de los comentarios señalan los altos costos y la baja demanda de pagar viajes con DCR en medio de la pandemia.
- Una nuevo equipo experimental de marketing: Esta propuesta publicada por @fst_nml busca un designar un presupuesto de US$ 10.000 para financiar la experimentación de diversas estratégias de marketing. En los comentarios se lee cierto interés por la idea pero como el dueño de la propuesta no es un miembro conocido de la comunidad ni demostró hasta ahora conocimientos de marketing, parece no haberse ganado aún la confianza de los stakeholders.
- Memes a 10 DCR cada uno: Esta es la primera propuesta para financiar memes con el Tesoro de Decred, pero no creo que sea la última. @cryptoarchitect pide un presupuesto de 200 DCR para hacer 20 memes de Decred. Los memeartistas mostraron su porfolio, pero les pidieron que hagan algunos memes de Decred de ejemplo, pero todavía no lo hicieron. @cryptoarchitect cito en los comentarios "hechos" sobre Decred e incluyó los riesgos de que sin marketing el proyecto se transforme en una moneda muerta. Así todo, para avanzar tiene que definirse un presupuesto en dolares y no DCR, de lo contrario incumple con las normas de Politeia y no se abrirá su votación.
- Decred Poker, el torneo que no estabamos esperando. @darthcrypto presentó una propuesta para organizar torneos de poker online financiados por el Tesoro de Decred. el presupuesto por evento es de 300 DCR por mes. Al igual que la propuesta de los memes, hasta que no se defina un presupuesto en USD, no podrá avanzar.

Para enterarte cuando arrancan las votaciones de cada propuesta, seguinos en Twitter e Instagram, donde también publicamos Politeia Express, una sintetis de todas las propuestas que pasan por Politeia.

**DESAROLLO**

- La descentralización del Tesoro: Este es un tema al que vamos a seguir volviendo en futuro episiodios porque es uno de los cambios más importantes al consenso de Decred y si bien el desarrollo de la implementación ya casi está terminado, luego vendrán las etapas de votación, activación y posiblemente iteración o expansión de estas mejoras. Actualmente los cambios diseñados y escritos por Marco Peereboom están siendo revisados por otros programadores de Decred. Matheus Degiovani  y Dave Collins estuvieron repasando el código, pero todavía queda trabajo ya que son cambios grandes y es fundamental prestarle atención a cada detalle antes de comenzar con el proceso de DCP para cambiar las reglas de consenso. Jamie Holdstock, quien desarrollo el nuevo software para Proveedores de Servicio de Voto, también está ayudando a documentar todos los cambios para facilitar la revisión del código. Se espera que estos cambios el proceso de DCP se inicie cuando salga la versión 1.6, que también incluirá las herramientas de privacidad en Decrediton y, como ya hablamos, mejoras a dcrlnd, la Lightning Network de Decred.
- La descentralización del Tesoro trae otra novedad: la implementación de firmas Schnorr, algo que Bitcoin viene planteando hace rato, pero todavía no llegó a implementar. Dave Collins estuvo trabajando en estas por mucho tiempo y ahora los cambios al Tesoro usarán por primera vez este desarrollo.

> CITA DE DAVE COLLINS:
> Sugerí que usemos firmas Schnorr para los pagos de la Tesorería para aprovechar algunos de los beneficios que traen: son más livianas y su seguridad puede demostrarse formalmente. Recién limpié el código de las firmas Schnorr para que cumpla con los estándares necesarios para formar parte de las reglas de consenso y si bien hay algunos cambios que queremos hacer antes de permitir que cualquier usuario las use, ya están más que listas para usarse en los pagos de la Tesorería. -@davecgh

https://chat.decred.org/#/room/!zefvTnlxYHPKvJMThI:decred.org/$yLGDR6WC7v7LTDkNYOLgTXHOozNnVc92xNS8B-0epds

**YAPA**

Cambiamos de tema y ahora hablamos de Marketing. Últimamente aumentaron las discusiones relacionadas a las estrategías de marketing, algo que también se reflejó en la cantidad de propuestas que hay en Politeia.

Si hacemos un repaso, 2020 fue un año sacudido para el area de Marketing dentro de Decred. El año arranco con una nueva agencia de Relaciones Públicas, Monde PR, y el equipo se redujo a una sola persona: Lindsey McConaghy quien está atendiendo todas las consultas que llegan a Decred por parte de la prensa y proponiendo historias para ubicar a estos créditos descentralizados en las páginas de diversos medios.

También hay que destacar que Lindsey reapareció como contratista al mismo tiempo que Ditto caía ante las preguntas de los usuarios en Politeia, con una propuesta que rápidamente se ganó la aprobación de la comunidad.

El año arrancó difícil. A todos los equipos de marketing nos tocó adaptarnos a trabajar dejando los eventos físicos de lado. La propuesta de marketing en Europa no fue aprobada y todavía no apareció otra. Dustorf, quien renovó la propuesta de marketing para los Estados Unidos y desarrollo de contenidos en Inglés, dejó de colaborar con el proyecto como lo venía haciendo.

A su vez, hay una mayor cantidad de recursos enfocados a la producción de contenidos como el podcast Decred in Depth, webinars como los que está armando el equipo de Australia, estos videos que hacemos desde Decred en Español.

Y también, nuevos productos hechos a partir de la tecnología existente y el contenido que generan las propuestas de investigación. Actualmente está en desarrollo Decred On-Chain, una nueva aplicación web similar a dcrdata pero que incluirá también información relacionada al precio de DCR, nuevas funcionalidades de privacidad y Lightning Network están llegando a Decrediton. Politeia ya está incorporando los Pedidos de Propuestas para que la comunidad pueda tomar la inciativa y demostrar su interes en propuestas que resuelvan determinados problemas o nuevos productos/plataformas deseadas.

El DEX es otro elemento clave que podría atraer nuevos usuarios a Decred.

**EVENTOS**

En julio, Decred en Español organizó y participó en {n} eventos. Entre ellos:

1. El 22 de julio, Pablito y Camilo pasaron por "Comunidades con Códigos", un panel de Blockchain Land sobre DAOs y gobernanza de protocolos descentralizados como Decred. También participó del panel Mariano de Maker DAO. [Youtube](https://youtu.be/b9sAqGs8bJ4?t=29339)
2. El mismo día, Elian hablo sobre cómo identificar y prevenir estafas en el canal de YouTube de la Academia Crypto Resources de Buenos Aires. [Youtube](https://www.youtube.com/watch?v=IAlXrrYCYcs)
3. El 23, Ana pasó también por Blockchain Land para contar cómo se financian los nuevos activos digitales y descentralizados. [Youtube](https://youtu.be/On2zYc7BrvI?t=14942)
4. El 23 Elian volvio a hablar sobre criptoestafas con Lorena Ortiz del Bitcoin Embassy Bar. [Youtube](https://www.youtube.com/watch?v=lRtXgtJ7dU8)
5. Por último, el 6 de agosto fue la octava edición de Hablemos Decred el programa en vivo donde hablamos sobre cripto, Decred, y lo que está pasando en América Latina. Esta vez estuvo de invitado Jose Manuel da Silva de Criptolugares.com para hablar del uso de las criptomonedas en el comercio. [Youtube](https://youtu.be/z-6a_tgE89E)

**TRADUCCIONES**

Como todos los meses, pueden leer la traducción del Decred Journal completa en español en el Medium de Decred en Español. Saludos a Franco, quien se encarga de la traducción.

**CREDITOS Y ENGAGEMENT**

1. Estos resumenes en video son el trabajo en conjunto del equipo de contenido de Decred en Español. Detrás de escena están Pablito y Nachito, trabajando en la producción y edición de estos videos.
2. Antes de irse, no olviden suscribirse al canal de Youtube de Decred en Español tocando el boton acá abajo y comenten qué les gustaría saber sobre Decred ya que también estamos haciendo videos educativos
3. Nos vemos el mes que viene para otro resumen de Decred en Español
