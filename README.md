# La peste negra

Estacion del museo viviente medieval. Los visitantes abren la pagina en su telefono,
presionan Comenzar y al minuto algunos se enferman solos. Todo dura tres minutos.

## Como se usa el dia de la exposicion

1. Proyecta o muestra la pagina con #qr al final de la direccion para que todos escaneen.
2. Cuando todos la tengan abierta, di que presionen Comenzar. La pagina espera unos
   segundos y arranca al mismo tiempo en todos los telefonos.
3. Abajo de cada pantalla sale un codigo de tres letras. Di el tuyo en voz alta. Si a
   alguien le salio otro, presiono fuera de tiempo y tiene que entrar con el enlace
   Ya empezo sin mi poniendo tu codigo.
4. Del segundo 0 al 55, el companero 1 explica la estacion. Los telefonos laten y de vez
   en cuando se oye toser a alguien de la sala.
5. En el 0.55 se ponen rojas una de cada cinco pantallas y vibran. En el 1.40 caen mas.
   Entre todas queda infectada como una de cada tres personas.
6. A partir de ahi cada quien tiene algo que decidir, y lo que decide cambia lo que le pasa.
   Ver la seccion de abajo.
7. El companero 2 entra como medico con la tabla abierta en su telefono, lee el color del
   frasco de cada pantalla roja, aplica el tratamiento y separa a los sanos de los enfermos.
8. En el 2.05 los enfermos mueren, uno por uno, con estertores y campanas de muerto.
9. En el 2.25 sale la revelacion sola en todas las pantallas y en el 2.45 cruzan las ratas.
   Ahi se sueltan las ratas de control remoto.
10. En el 3.00 queda el cierre sobre la cuarentena y cada quien abre su expediente.

## Lo que decide cada visitante

Nadie mira la pantalla esperando. Los tres momentos son estos.

**Si enfermas, lees tu frasco.** Sale tu orina con su color y eliges cual de los cuatro
humores te sobra. El color es una pista de verdad, la misma rueda que usaba el medico, asi
que se puede acertar. Es la unica pregunta de la estacion que tiene respuesta correcta.

**Si enfermas, eliges tratamiento.** Cuatro opciones reales de 1348, cada una pensada para
un humor, porque se trataba con lo contrario. Te alivia trece segundos y despues vuelve la
fiebre. Elijas lo que elijas, te mueres.

**Si sigues sano, decides si huyes.** Te quedas o te vas al campo, como hicieron los ricos.
Tienes hasta el 1.36, que es cuando cierran las puertas. El que se queda cae en la segunda
oleada mucho mas que el que huye, asi que la decision se paga. Y al final, al que huyo se le
dice que llevo la peste al pueblo siguiente.

Al terminar, cada telefono abre **su expediente**. Que tuviste, que leiste en el frasco y que
habria leido un medico de la epoca, que dejaste que te hicieran, que elegiste y como acabaste.
Debajo, el sello de los cuarenta dias. La idea es que la frase final no la diga un cartel sino
tu propia hoja, que nada de lo que elegiste cambio nada porque en 1348 no habia con que.

## Direcciones utiles

- #guion abre el guion del expositor con el reloj y la senal de cada momento.
- #medico abre la tabla de los cuatro humores con su color y su tratamiento. Es la que lleva
  el medico en la mano durante la estacion. No sigue el reloj y nunca se enferma.
- #qr muestra el codigo para que la gente escanee.
- ?ensayo=6 corre todo seis veces mas rapido para ensayar.
- ?desde=140 arranca con el reloj ya adelantado, para ver solo el final.
- ?rol=enfermo y ?rol=sano fuerzan el papel para probar las pantallas. Sin esto te toca al
  azar y es normal pasar varias pruebas seguidas sin enfermarte, porque solo cae uno de
  cada cinco en la primera oleada.
- ?rol=medico hace lo mismo que #medico.

## El sonido

No hay ningun archivo de audio. Todo se genera en el propio telefono, asi que no depende del
wifi del museo ni de que un servidor este arriba el dia de la exposicion.

Hay tos, tos lejana, un grito de otra calle, campanas de muerto y el estertor. La tos de tu
propio telefono suena fuerte y las de los demas suenan filtradas y bajas, asi que con la sala
llena el efecto es que todo el mundo esta tosiendo alrededor. En la calma se oye una tos suelta
cada ocho o quince segundos, antes de que pase nada, y eso es lo que va montando el ambiente
mientras el companero 1 explica. Si estas enfermo toses cada pocos segundos y el telefono
vibra con cada golpe.

Para oirlo sin esperar al pase entero, abre la consola del navegador y escribe
probarSonidos(). Tambien acepta un nombre suelto, probarSonidos('tos'), y valen tos, lejos,
grito, campanas y estertor.

## Notas

La vibracion solo funciona en Android. En iPhone no hay vibracion, por eso cada momento
lleva tambien sonido y cambio de color de pantalla.

El sonido de un navegador solo se abre cuando la persona toca la pantalla. Comenzar ya
sirve, pero si alguien no oye nada que toque la pantalla una vez.

Si el telefono recarga la pagina a medio pase, vuelve sola a donde iba y mantiene si
estaba sano o enfermo.
