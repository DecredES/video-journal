# 04 - MAYO 2020

**INTRODUCCION**

Bienvenidos a un nuevo resumen mensual de Decred en Español, soy Victor, contratista de Decred y hoy vamos a repasar todas las novedades que nos trajo mayo.

**RESUMEN DEL MES**

Intro a la novedad piola: En mayo, Jamie Holdstock, uno de los desarrolladores de Decred, anunció la primera versión de un nuevo sistema de Servicio de Voto más privado que permitirá que cualquier usuario de Decrediton use la red de mezcla al comprar tickets a través de un proveedor de servicio de voto. Esta es la pieza que faltaba para extender las herramientas de privacidad a todos los usuarios de Decred y de lo primero que vamos a estar hablando.

También hablaremos de novedades en:

- Gobernanza: Este mes se presentaron 5 nuevas propuestas. Entre ellas, la del equipo de América Latina. Hace muy poquitos días terminó la votación que concluyó con la continuidad de los esfuerzos de Marketing en LATAM, la renovación de la investigación de permabullnino y la financiación de Decred OnChain, un nuevo sitio web.
- Desarrollo: Al igual que todos los meses, hay muchisimas novedades del lado del desarrollo. El DEX pasó a etapa de prueba y ya cualquiera puede descargarlo y ver cómo funciona. Politeia y el CMS recibirán nuevas actualizaciones. Y tenemos nuevas versiones de las billeteras móbiles!
- Investigación: El último mes estuvo lleno de nuevos artículos publicados por los investigadores de Decred, incluídos checkmate y richardred.
- Eventos: Y por último, hablaremos de los eventos que organizamos desde Decred en Español.

¡Ahora, sí, arrancamos con el resumen!

**LA NOVEDAD PIOLA: Nuevo software de servicio de voto!**

Links:

- https://blog.decred.org/2020/06/02/A-More-Private-Way-to-Stake/
- https://github.com/decred/vspd

vspd es una **nueva implementación**, hecha desde cero, del **software para Proveedores de Servicio de Voto de Decred**. Este permite votar sin tener que tener una computadora prendida las 24 horas. Hace lo mismo, pero **vspd funciona de una forma completamente diferente al sistema anterior para poder brindar mayor privacidad**.

Son un montón de cambios, pero ¿por qué se hizo desde cero y no se modificó el sistema anterior? **El problema era que el sistema de VSP anterior, dcrstakepool, estaba basado en un sistema de cuentas identificadas por mails.** Al querer desligar a las personas de sus tickets, esto se transformó en un problema e hizo falta repensar cómo funciona la relación entre stakeholders y los proveedores de voto, ¿cómo harían para identificarse mutuamente?

Con el nuevo servicio, los tickets se registran de forma individual y ahora **el pago del fee ocurre en una transacción separada**. Esto permite que tanto la compra del ticket como la comisión que se le paga al VSP se mezclen en el mismo grupo que los tickets de quienes votan solos, es decir, quienes corren su propia infraestructura.

vspd también nos trae mejoras a los usuarios, ahora:

- no hace falta hacer backup del redeem script
- podemos configurar las preferencias de votación por cada ticket
- no reutilizamos nuestra dirección
- y podemos elegir usar múltiples VSP para un solo ticket

Atención: Si bien se trata de una pieza fundamental para la red, **no se puede apurar su desarrollo**. Todavía **no está listo** para ser usado en el día a día, queda integrarlo con las wallets de línea de comando y luego recién con Decrediton. Según Jamie Holdstock, quien lideró el desarrollo, habra todo **un año de transición en el que los proveedores podrán correr una o ambas versiones**, hasta que se migre de forma definitiva a vspd. **A medida que más proveedores lo adopten, más usuarios podrán acceder a los servicios de privacidad y más grandes serán las mezclas.**

**GOBERNANZA**

Link al tesoro: https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx?txntype=merged_debit

Ahora si, pasamos a la segunda sección de este resumen de {Abril }y vamos a hablar sobre todo relacionado con la gobernanza de Decred.

En mayo, el Tesoro recibió 13.594 DCR y gastó 19.153 DCR, quedando así con cerca de 5559 DCR menos que el periodo pasado. Este mes, el precio promedio de DCR fue de 14,11 USD.

Este fue un mes de mucha actividad. En Politeia se presentaron 5 nuevas propuestas, de las cuales 4 ya terminaron de votarse:

- [DCR On-Chain Research: Phase 2](https://proposals.decred.org/proposals/68a32c1f36d24a17e5eb69d6d1b6adb587ca45c9c7e64e85c353e7dba7fca545)
  - Esta es la segúnda propuesta de investigación de @permabullnino. Solicita US$ 16.000 para cubrir de 8 a 10 meses de trabajo, continuando con la temática de la etapa anterior, pero con menos artículos largos y más enfasis en publicaciones medianas y cortas.
  - La propuesta pasó con una aprobación del 74,4%
- [Decred OnChain](https://proposals.decred.org/proposals/023091831f6434f743f3a317aacf8c73a123b30d758db854a2f294c0b3341bcc)
  - Checkmate presentó una nueva propuesta, pero está vez no es de investigación, sino para crear un nuevo sitio web con métricas y gráficos sobre la blockchain de Decred. Este proyecto requiere de US$ 7.800 para desarrollar la primera versión del sitio, con 5 charts y textos explicativos. En el equipo de desarrollo están @nachito y @pablito, quienes forman parte del equipo de producción de este resumen en video.
  - Felicitaciones a ellos porque la propuesta fue aprobada con más del 86% de los votos.
- [TV Marketing for Decred](https://proposals.decred.org/proposals/9eaafc20f206776e38642e272233390f351c5562c3835369a558cc7d7e341018)
  - Esta propuesta ofrece producir 2 o 6 entrevistas de 10 minutos para ser transmitidas por la red de televisión de FMW. La propuesta tiene muchos números, pero no queda claro qué tan relevantes son. Afirman poder aumentar el precio del token un 901% y esto puso alerta a muchos de los usuarios de Pi.
  - La propuesta sigue en discusión.
- [CoinStory - Historia y Evolución de las Criptomonedas](https://proposals.decred.org/proposals/4affceb07f5b8126366e8b73ed3d164ebc010bc6fefba19375c4c2e2b252beb0)
  - Esta propuesta publicada por David Stancell, solicita US$ 1.000 para que Decred sea sponsor de su libro sobre criptomonedas. A cambio, David incluirá una sección sobre Decred y ubicará el logo de DCR en su sitio web.
  - La propuesta fue rechazada tras solo alcanzar una aprobación del 11,6%
- [Decred Latam Marketing and Events Proposal 2](https://proposals.decred.org/proposals/3c02b677462d6d22d61bf786798e975b38df7a203c2467429d4ec91f75ef0c40)
  - Por último está nuestra propuesta! Junto al equipo de América Latina presentamos una propuesta para renovar nuestro presupuesto y contar con US$ 46.000 para desarrollar acciones de marketing y crear más contenido que nunca. La idea es hacer más video, organizar más eventos online y ponernos en contacto con más desarrolladores. (Así que si tenés ganas de programar para Decred, escribinos en los comentarios y suscribite para enterarte de todas las novedades).
  - La propuesta fue aprobada en el último momento, con 60,7% de votos positivos.

**DESAROLLO**

Más allá del lanzamiento del nuevo software de VSP, tenemos otras novedades en el área de desarrollo:

- Politeia, que vio uno de sus meses con más actividad, recibirá importantes cambios. Ya están probando los Pedidos de Propuestas, que le permitirán a la comunidad señalar propuestas específicas que desean ver. A su vez, continúa el trabajo para reemplazar la interfaz gráfica y usar más de los nuevos componentes de React incluídos en pi-ui, la librería gráfica de Decred.
  - https://github.com/decred/politeiagui/pull/1910

- El Exchange Descentralizado, el DEX, ya está en etapa de prueba. Cualquiera puede participar descargando el software, siguiendo el link que les dejamos en la descripción del video, e intercambiar Bitcoin por Decred en las redes de prueba. Cada vez falta menos para que el DEX sea lanzado en la red principal. Si tienen alguna duda sobre cómo instalar el cliente del DEX, recuerden que pueden consultar en nuestro canal de Telegram: @DecredES
  - https://github.com/decred/dcrdex/wiki/Testnet-Testing
  - https://twitter.com/chappjc/status/1267115398610255874
- Por último, las billeteras móviles se vienen con todo y los últimos cambios incluyen varias mejoras de seguridad, entre ellas la posibilidad de monitorear direcciones de Decred desde el teléfono, sin que este tenga acceso a las claves privadas. Así, vamos a poder ver en cualquier momento si nuestros tickets votaron o qué está pasando con nuestros fondos, sin poner poner nuestras claves en ningún lado. Gracias equipo de devs, ¿a ver si mis tickets votaron? *saca el celular*
  - https://github.com/decred/dcrandroid/pull/471
  - https://github.com/raedahgroup/dcrios/pull/685

**INVESTIGACIÓN**

Hoy tenemos una pequeña sección dedicada a los avances en investigación. Para quienes no lo sabían, entre los contratistas de Decred hay varios investigadores que dedican su tiempo a analizar datos y escribir sobre el estado de la blockchain de Decred y su gobernanza.

- Checkmate publicó un artículo sobre el Realised Cap de Decred, un indicador muy similar al Market Cap que refleja la suma total de todas los créditos en circulación, pero con una corrección muy importante: no se usa el precio actual que vemos en los exchanges para calcularlo, sino el precio de la última vez que se movio cada crédito en la blockchain. Si compre 10 DCR hace varios meses a 20 dólares y las moví a mi wallet, esas monedas siempre le sumarán 200 dólares al Realised Cap, no importa si ahora cada DCR vale más o menos. Recién cuando las muevo, su precio se actualiza. Esta forma de medir el precio total de todo el DCR en el mercado permite sacar del medio mucho del ruido que los exchanges generan en el corto plazo y ver realmente qué están haciendo los holders. Ahí abajo en la descripción les dejamos el link al artículo. https://medium.com/decred/decred-on-chain-realised-cap-mvrv-ratio-and-gradient-oscillators-a36ed2cc8182
- Permabullnino también publicó un nuevo artículo. Nino trabajó mucho explorando el comportamiento de los tickets y su precio en DCR, pero esta vez se metio con los mineros. Su nuevo artículo está enfocado en el Pulso de la Minería de DCR y se centra en los tiempos entre bloques y lo que nos pueden enseñar sobre el comportamiento de los mineros, que recordemos reciben la mayor parte de la recompensa de cada bloque y tienen gran impacto en el precio de DCR. ¡Vayan a leerlo! https://medium.com/@permabullnino/decred-on-chain-mining-pulse-3b28d5155a04
- Richard Red publico la primera parte de su investigación sobre la blockchain de Decred. Esta se centra en el movimiento de DCR y el análisis del origen de este. Así, detectó a distintos grupos de holders, como aquellos que participaron del airdrop inicial o los contratistas que invirtieron su DCR en tickets. Según explica, la blockchain escribe su propia historia al detallar todos los movimientos, pero es necesario desarrollar mejores herramientas de analisis para entenderla y a la vez poner a prueba la privacidad de los usuarios y el nuevo servicio de mezcla. https://blockcommons.red/post/dcr-on-chain-1/
- Por último, Ammar Naseer publicó "Por qué necesitamos Decred: un acercamiento inclusivo al dinero", un artículo donde analiza Bitcoin como una forma de repensar el dinero y estudia Decred como una moneda que implementa los avances de Bitcoin junto a herramientas de cooperación y resolución de conflictos. https://medium.com/@Ammarooni/why-we-need-decred-an-inclusive-approach-to-sound-money-db2f990c107b

**EVENTOS**

https://medium.com/decred/decred-journal-may-2020-a481bec47516

En mayo, Decred en Español organizó y participó en muchos eventos. Entre ellos:

1. Jueves de CryptoDrinks, donde @elian dio una breve intro a Decred
2. Organizamos la 5ta edición de #HablemosDecred, donde nos acompañó Fernando Quiros, periodista del Cointelegraph en Español.
3. Participamos de Hack por la Paz
4. Carolina y Ana armaron un panel de Gobernanza descentralizada y DAOs junto a otras comunidades y plataformas, incluídas MakerDAO y Colony.
5. Pablito dio un webinar sobre el Financiamiento de Software Open-Source, para que los devs encuentren formas de hacer que sus proyectos sean sustentables. *Hacer una pausa en silencio y mirando a cámara para insertar footage del video* Si les interesa saber más, pueden encontrar el video completo acá, en nuestro canal.

**TRADUCCIONES**

Como todos los meses, pueden leer la traducción del Decred Journal completa en español en el Medium de Decred en Español. Saludos a Franco, quien se encarga de la traducción.

**CREDITOS Y ENGAGEMENT**

1. Estos resumenes en video son el trabajo en conjunto del equipo de contenido de Decred en Español. Detrás de escena están Pablito y Nachito, trabajando en la producción y edición de estos videos.
2. Antes de irse, no olviden suscribirse al canal de Youtube d eDecred en Español tocando el boton acá abajo y comenten qué les gustaría saber sobre Decred ya que también estamos haciendo videos educativos
3. Nos vemos el mes que viene para otro resumen de Decred en Español
