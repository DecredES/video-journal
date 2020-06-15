# Outline

1. Intro picante

   1. Gancho
      1. En febrero Decred cumplió años. Celebramos cuatro años desde la creación el primer bloque el 8 de febrero de 2016 y como todos los meses, pasó de todo.
   2. Outcome (qué se llevan de ver este video)
      1. Se celebró la #DecredGlobalMeetup en más de 11 ciudades del mundo para festejar el aniversario de la red.
      2. Dustorf escribió un extenso reporte sobre las acciones de Marketing llevadas a cabo en 2019
         1. Qué se hizo,en qué se gastó, qué salió bien y qué salió mal
         2. Y también comentó sus ideas para el 2020
      3. Se avanzó con el desarrollo del Exchange Descentralizado, se optimizó el software de los nodos de Decred  dcrd
      4. Y a principios de marzó se lanzó el nuevo sitio de Decred.org con nuevos videos y animaciones!
   3.  Testimonial (construir autoridad)
      1. Antes de comenzar, este video está basado en el Decred Journal, una revista mensual dedicada a todo lo que pasa en el ecosistema de Decred. La edición se Febrero es el resultado del trabajo de bee, degeri, Dustorf, guisso, Lindsey, richardred y la revisión de muchos otros desarrolladores y colaboradores de la comunidad.

2. Primer plato: la novedad piola

   1. Link https://voting.decred.org/
   2. Fue aprovada la activación de nuevas reglas de consenso a partir del 13 de marzo. Esta vez, los stakeholders aprobaron cambios a los encabezados de los bloques, la propuesta DCP005 es un paso hacia la expansión del modelo de seguridad de Decred para soportar dispositivos pequeños, principalmente dispositivos móviles y sus aplicaciones.
   3. Usando los nuevos encabezados una billetera móvil podrá verificar que los bloques que recibe cumplén con las reglas de consenso sin necesidad de descargar y verificar la blockchain completa. Esto mejora considerablemente la seguridad de las aplicaciones más livianas que antes dependian de terceros para verificar las transacciones.
   4. Las billeteras para Android y iOS ya comenzaron a implementar estas nuevas mejoras y sus usuarios podrán disfrutar de mayor seguridad pronto.

3. Gobierno

   1. Link tesoro https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx?txntype=merged_debit
   2. Ahora si, pasamos a la segunda sección de este resumen de Febrero
   3. El Tesoro recibió 13.000 DCR y gastó 12.600 DCR, quedando así con 400 DCR más que el periodo pasado. Este més, el precio promedio de DCR fue de 20.48 USD.
   4. En Politeia se publicaron cuatro nuevas propuestas y 5 comenzaron su votación.
      1. Se aprovo la propuesta de Exitus para la creación de contenido en video con 92.5% de los votos y una participación del 24.8%
      2. La segunda propuesta de investigación de Checkmate fue aprovada con más del 81% de los votos y una participación del 21%. Esta vez se invertirán 17.500 USD en diversas actividades, incluida la integración de algunos de sus charts y también de Permabullnino en dcrdata, el explorador de bloques.
      3. La propuesta del presupuesto de Marketing para Europa presentada por Haon fue rechazada. El equipo europeo pidió 49.000 USD para cubrir sus operaciones en la región pero solo recibió una aprovación del 38% donde participo el 25%.
      4. Dos prupuestas fueron rechazadas: una propuesta para la producción de videos en ruso solo recibió 21% de aprovación y la propuesta de oscargamboae sobre Economía Creativa no alcanzó el quorum y solo participó 15% de los tickets.

4. Desarrollo

   1. Como todos los meses, el equipo de desarrollo de Decred iteró en las distintas piezas que hacen al ecosistema de Decred, desde los nodos hasta las wallets y el explorador de bloques. Vamos a repasar los tres más importantes de Febrero. Si quieren conocer más de un desarrollo especifico, no olviden comentarlo aca abajo y veremos de hacer algun video sobre ello!
   2. dcrd
      1. Se optimizaron varios componentes del nodo, resultado así en mejoras en la velocidad y el uso de memoria al verificar firmas. También cuando se completen las mejoras se mitigarán aquellos ataques que busquen extraer información sobre la actividad del nodo mediante canales alternativos como lo es el tiempo de procesamiento.
   3. dcrwallet
      1. dcrwallet es el software de de escritorio que funciona por debajo de Decrediton. En febrero se agregaron nuevos comandos para facilitar el staking offline y brindarle soporte a billeteras de hardware como las de Trezor en el futuro.
      2. También se agregaron nuevas funcionalidades relacionadas a las herramientas de privacidad que serán usadas para implementarlas en Decrediton en la siguiente versión, la 1.6.
   4. El DEX
      1. Link https://twitter.com/chappjc/status/1245075450625511425
      2. Se avanzó muchisimo en el desarrollo del exchange descentralizado de Decred que fue aprovado en Politeia hace ya casi un año:
         1. Se creo un cliente RPC para interactuar con el servidor vía linea de comandos
         2. Se avanzo en dos componentes clave para evitar la manipulacion de los trades: se implemento la primera versión del sistema de coordinacion de ordenes de compra y venta por epocas, es decir que cada tanto tiempo se coordinaran de forma aleatoria algunas ordenes de compra y algunas de venta. Y también se implemento un algoritmo más robusto para mezclar estas ordenes.
         3. Se creo una interfaz grafica web muy simple para manejar las cuentas del exchange

5. Red (Idealmente una sola cosa)

   1. En febrero, la cantidad de DCR mezclado usando el servicio de privacidad alcanzó el 20% de la circulación. Esto es enorme, las transacciones CoinJoin de Decred están mezclando entre 50.000 y 100.000 DCR por dia, el equivalente a 3 millones de dólares. Esto puede ser verificando usando el nuevo gráfico de ciruclación total de dcrdata en alpha.dcrdata.org. A su vez, el explorador de bloques también está incorporando una herrramienta que permite calcular el costo de un ataque a la red de Decred.

6. Integraciones

   1. La integración más llamativa del mes fue la incoporación del Staking de DCR a la plataforma de KuCoin. El exchange anuncio que todos los usuarios que posean DCR en el exchange serán incluidos en el programa de Staking o tendrán un tiempo para retirar su DCR.
   2. KuCoin se encargará de todo, cobrar y repartir las ganancias del Staking, pero esto podría ser un poco mucho. Debido al funcionamiento del Staking en DCR, los usuarios deberán esperar, o hacer fila, para retirar su DCR del exchange, ya que al estar lockeado en tickets no puede ser retirado inmediatamente.
   3. A su vez, KuCoin no menciona en ninguna parte nada relacionado al poder de voto de los tickets controlados por el exchange. Siendo el sistema de Staking el principal mecanismo de Gobernanza de Decred, los usuarios de KuCoin quedan excluidos de esta y al parecer no tendrán ni voz ni voto por stakear su DCR.

7. Eventos Latam

   1. Feb 6 — [Decred Global Meetup](https://www.eventbrite.com/e/decredglobalmeetup-en-buenos-aires-tickets-90817259869) — Buenos Aires, Argentina. Hosted by @EspacioBitcoin. ([photos](https://twitter.com/cryptorc_tech/status/1225879454158901248))

      Feb 6 — [Decred Global Meetup](https://www.eventbrite.com/e/decredglobalmeetup-ciudad-de-mexico-en-bitcoin-embassy-bar-tickets-90619377999) — Mexico City, Mexico. Hosted by Bitcoin Embassy Bar. ([photos](https://twitter.com/bitcoinemb/status/1228091984906113025), [video](https://twitter.com/Decred_ES/status/1225656932431626241))

      Feb 27[–3er After UX Crypto](https://www.eventbrite.com.ar/e/3er-after-ux-crypto-sponsor-decred-tickets-95737271757) — Santa Fe, Argentina. Decred was a sponsor. ([photos](https://twitter.com/Decred_ES/status/1233159907194605572))

      Feb 27 — Decred and Stamping.io Meetup — Lima, Peru. @victorarubin  presented Decred to Stamping.io and Life Leadership community in Lima,  about 60 people attended. ([video](https://matrix.to/#/!aNPTuiryMFmdMQWUzb:decred.org/$1582953585375340iScnJ:matrix.org))

8. Traducciones

   1. Como todos los meses, pueden leer la traducción del Decred Journal completa en español en el Medium de Decred en Español. Este mes fue realizada por Franco.

9. Creditos y engagement (subscribanse, telegram, matrix)

   1. Antes de irse, no olviden suscribirse al canal de Youtube d eDecred en Español tocando el boton acá abajo y comenten qué les gustaría saber sobre Decred ya que también estamos haciendo videos educativos!
   2. Esta resumen en español sobre las actividades de Decred hubiese sido imposible sin el increible equipo que escribe el Journal todos los meses y el equipo de Decred en Español dedicado a traducir y compartir la información.
   3. Nos vemos el mes que viene para otro resumen de Decred en Español



## Descripción del video



Decred en Español - Resumen Febrero 2020



Secciones:

Cambios a las reglas de consenso

Tesoro

Propuestas

Mejoras al nodo

Wallets

Desarrollo del DEX

Red

Integraciones

Eventos en LATAM



Conoce más sobre Decred entrando a https://decred.org



¡Únete a la comunidad de Decred en Español!

Twitter: https://twitter.com/decred_es

Telegram: https://t.me/DecredES

Facebook: https://www.facebook.com/DecredESP/

Instagram: https://www.instagram.com/decred_es

Matrix: https://chat.decred.org/







