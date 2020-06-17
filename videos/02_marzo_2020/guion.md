# Decred Journal en Video #02 - Marzo 2020

1. Introducción
   1. Saludos a la comunidad de Decred en Español
   2. Gancho
   3. Presentación
      1. Soy Victor, contratista de Decred, les traigo otro resumen mensual
   4. Resumen
      1. Hoy vamos a hablar del DEX que está desarrollando Decred, cuyo desarrollo se encuentra bastante avanzado y ya tenemos algunas cosas para mostrar.
      2. Este también mes se activaron las nuevas reglas de consenso. Los nuevos encabezados de los bloques ya están disponibles y le brindan mayor privacidad y seguridad a los usuarios de clientes livianos, como las billeteras para celulares.
      3. Como siempre tenemos novedades del área de desarrollo: mejoras a los nodos, Politeia y el sistema de contratistas
      4. Moviéndonos a Politeia, dos propuestas de Marketing regional fueron aprobadas: Estados Unidos, que también se ocupa de todo el contenido en inglés, y Brasil tendrán su propio presupuesto de Marketing.
      5. Y este més es una fecha especial porque el Decred Journal, la revista mensual dedicada a todo lo que pasa en el ecosistema de Decred cumplió dos años ininterrumpidos de cobertura. 
      6. Ahora si, ahora si arrancamos con el resumen de marzo
2. La novedad piola
   1. Link: https://twitter.com/chappjc/status/1245075450625511425
      1. Hace ya un año que la comunidad de stakeholders de Decred decidió que construir un DEX es necesario. Hoy, luego de tres propuestas en Politeia: una para definir la idea, otra para detallar cómo será y una más para establecer el plan de desarrollo. Ahora, estás ideas están cobrando forma.
      2. Lo que Decred está desarrollando es un Exchange Descentralizado, una plataforma abierta donde cualquiera podrá intercambiar Decred por Bitcoin de forma anónima y segura aprovechando la tecnología de atomic swaps, también desarrollada por Decred.
      3. Este mes, el equipo de desarrollo del DEX, liderado por Jonathan Chappelow, Brian Stafford y Company 0, coordinó la primera orden de compraventa en las redes de prueba de Bitcoin y Decred usando un prototipo. Estas son enormes noticias, significa que muchas de las piezas centrales del DEX ya están funcionando.
      4. Pero todavía no está en etapas de abrirse y comenzar a recibir a sus primeros usuarios. La etapa final de la propuesta de desarrollo es tener un prototipo funcionando sobre las redes de prueba, es decir que todavía falta para que abra al público. Aún así, cualquier podrá probar el software usando su interfaz web sin necesidades de conocer cómo interactuar con este usando una terminal de línea de comandos.
      5. Uno de los avances más importantes es el sistema de negociación que coordina las ordenes de compra y venta. Esta era la ultima pieza restante para permitirle al cliente ejecutar intercambios atómicos. El código implementado hace que el cliente atraviese todo el proceso, comunicarse con el servidor, auditar las transacciones, crear y transmitir sus propios contratos, todo lo requerido por el proceso de atomic swaps.
      6. Quienes quieran leer más sobre el DEX, pueden leer la propuesta y revisar los repositorios entran a los links que les dejamos en ladescripción. Ya que están ahi abajo, no olviden seguirnos y activar la campana para recibir los últimos videos de Decred en Español.
3. Gobernanza
   1. Link tesoro https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx?txntype=merged_debit
   2. Ahora si, pasamos a la segunda sección de este resumen de Marzo y vamos a hablar sobre todo relacionado con la gobernanza de Decred.
   3. Este mes se activaron las nuevas reglas de consenso. Se trata del quinto hard-fork controlado y aprobado por los usuarios de Decred. Como hablamos al principio, estos cambios le brindan mayor seguridad y privacidad a todos los clientes livianos como las billeteras para dispositivos móviles y a aquellas personas que prefieren no descargar una copia completa de la blockchain para usar sus wallets. Por como funciona Decred, todos el software que corra la versión anterior, la 1.4, será desconectado de la red. Recuerden actualizar Decrediton y todas las aplicaciones que usen!
   4. En marzo, el Tesoro recibió 13.700 DCR y gastó 17.153 DCR, quedando así con cerca de 3500 DCR menos que el periodo pasado. Este més, el precio promedio de DCR fue de 13.40 USD.
   5. En Politeia se publicaron 4 nuevas propuestas:
      2. La propuesta de Marketing para los Estados Unidos fue aprobada luego de reducir su presupuesto a 177 mil dolares y quitar el presupuesto para eventos a razón del COVID19. Recibió una aprobación del 74%, donde participaron el 31% delos stakeholders.
      3. La propuesta de Marketing de Brasil también fue aprobada con un apoyo del 65% y una participación del 34%. Esta implementará un presupuesto de 108 mil dolares para desarrollar las actividades de marketing en uno de los países con mayor comunidad. También debieron quitar el presupuesto para eventos.
      3. La segunda propuesta de DCR Comic pide un presupuesto de $16.200 para realizar 12 comics más y aumentar el tiempo dedicado al manejo de redes sociales. La propuesta fue puesta en pausa tras recibir criticas sobre el uso de Stakey y el 6 de abril el equipo presentó nuevos personajes para acompañar a Stakey. El 9 de abril se abrió la votación. La propuesta no fue aprobada, pero el equipo de DCR Comic seguirá colaborando con otras áreas del proyecto, como la realización de estos videos!
      4. Por último, dos propuestas siguen en discusión: PolisPay App busca 5000 dolares para agregar soporte para DCR y hay una propuesta de Decred Daily para mantener una cuenta de Twitter y crear una nueva pagina web por 5280 dolares.
4. Desarrollo
   1. dcrd
      1. Continúan las mejoras al software principal de Decred, aquel que hace funcionar a los nodos. Los cambios más importantes incluyen varias mejoras a los tiempos para verificar firmas y cambios a la estructura del paquete de firmas para permitir la incorporación de firmas Schnorr en el futuro, que le permitirán a los devs realizar nuevos trucos para aprovechar mejor el espacio en los bloques y mejorar la privacidad de las transacciones.
   2. Politeia
      1. Politeia, la plataforma de gobernanza de Decred, es uno de los desarrollos más importantes de la comunidad. Este mes comenzaron algunos trabajos para integrar un nuevo backend que permita mayor escalabilidad. En vez de usar Git y guardar todos los mensajes publicados y firmados en un repositorio, el equipo de Politeia está investigando el uso de Trillian, un sistema de Google, para almacenar datos. Entre otras cosas, también podría resolver el horrible bug que hace que a veces los comentarios se publiquen dos veces.
   3. CMS
      1. Por último, el CSM también tiene novedades. Este es el sistema que usan los contratistas de Decred para gestionar sus facturas y pagos. Ahora es posible designar dueños de propuestas para que estos puedan ver qué trabajo se está facturando usando esa propuesta. El objetivo es brindar mayor transparencia y herramientas que permitan que los contratistas gestionen sus propios equipos. Detrás de escena, el CMS también está migrando de librería gráfica, en sus comienzos se uso una que permitio crear Politeia con un look muy parecido a Reddit sin mucho esfuerzo, pero con el tiempo se volvio un problema. Así fue que el equipo de Pi comenzó a trabajar en su propia librería gráfica: pi-ui y ya está siendo implementada en las distintas plataformas.
5. Red
   1. Algunos números sobre el estado de la red en marzo.
   2. El precio del ticket promedio fue de 141,9 DCR, variando entre 130 y 166,8 DCR. Este pico es un nuevo máximo histórico desde el cambio de algoritmo de staking.
   3. A su vez, este mes la blockchain creció 129 MB. Es raro ver en Decred bloques completamente llenos, pero el Tesoro, que le paga a los contratistas suele llenar bloques al emitir los pagos del mes. Este mes los pagos generaron una seguidilla de 9 bloques llenos el 16 de marzo.
6. Eventos Latam
   1. Ahora si, llegando al final nos ponemos en mood fiesta. En marzo hubo muchisimos eventos en LATAM, justo antes de que la llegada del COVID19 nos obligase a mudarnos a modalidades online.
   2. Hubo eventos en Argentina, Venezuela, México, Uruguay, Panamá y también comenzamos a incursionar en eventos virtuales. HablemosDecred es el nuevo encuentro virtual de la comunidad de Decred en Español. Se organiza jueves por medio y cualquiera puede acercarse a charlar. Seguinos en Twitter o Instagram para estár al tanto de los próximos eventos online!
7. Traducciones
   1. Como todos los meses, pueden leer la traducción del Decred Journal completa en español en el Medium de Decred en Español. Este mes fue realizada por Franco.
8. Créditos y engagement
   1. Antes de irse, no olviden suscribirse al canal de Youtube d eDecred en Español tocando el boton acá abajo y comenten qué les gustaría saber sobre Decred ya que también estamos haciendo videos educativos!
   2. Esta resumen en español sobre las actividades de Decred hubiese sido imposible sin el increible equipo que escribe el Journal todos los meses y el equipo de Decred en Español dedicado a traducir y compartir la información.
   3. Nos vemos el mes que viene para otro resumen de Decred en Español

