# repositorio2
	Codigo

El código se encuentra en elevador/elevador.ino, este funciona
para 'n' pisos, no importa si son 3, 4 o 10, el código debería de
funcionar, solo que cuando inicies el Arduino el ascensor debe
de estar en la planta baja.

El código viene comentado, para poder ver como funciona,
si quieres cambiar de nombre las variables y demás solo asegúrate
de cambiar el nombre en todo el código para que no falle.

	Circuito

En circuito.jpg se puede ver como esta todo el circuito del arduino y el protoboard.

Los materiales serian:

-Arduino UNO
-Carcasa de impresora vieja (con engranes, banda, etc)
-Motor DC (de preferencia el que tenga la impresora)
-Cable UTP (pero puedes usar el que mas te acomode)
-Puente H (L293D)
-Una resistencia
-Una fuente de corriente independiente de 9v
-Dos barras metálicas que sean conductoras y del alto del que sera el total de pisos.

	Sensor para detectar los pisos.

El arduino esta programado con el código (elevador.ino)
para detectar 'n' pisos, esto gracias al algoritmo y al "sensor"
que implemente, que son dos barras una de ellas esta conectada
a la corriente + y la otra va conectada al - sin antes pasar
por el arduino para que cuando se cierre el circuito
el arduino detecte un pulso.

En img1.jpg se puede ver un cable naranja (+)
este esta conectado a una barra metálica que tiene aislante
a exepsion de los lugares donde debería de estar algún piso.

El cable blanco (-) esta conectado a la otra barra
la cual pasa por el arduino y luego a una resistencia
que da al negativo.

En img2.jpg se puede ver lo que seria todo el ascensor
utilize una impresora vieja, de la cual utilice sus motores,
carcasa, barras, soportes, engranes, etc. quitando lo sobrante
y dejando lo esencial.

En esta misma imagen se ven las dos barras conectadas, los cables
y el elevador en el cual puse un cable que conectara con ambas
barras para que sierre el circuito cuando esta en un piso
y mande un pulso al arduino.

Por ultimo para esta parte del "sensor" en la img3.jpg se ve este cable que esta firme con el ascensor (osea que sube y baja con este)
y hace de puente entre las dos barras, en esta imagen se muestra
mas a detalle esa parte.

En el circuito.jpg, todo esto iría en donde en el circuito
ay dos cables que no se conectan a ningún lado.

