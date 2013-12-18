CuerpoEspacioCV
===============

Material de soporte para el tercer bloque del curso Curso y Espacio en la escuela de artes Escénicas de Granada, Noviembre-Diciembre 2013


Ejercicios para casa (no olvideis comentar vuestro código):

- 1 Elegir uno de los programas vistos (Synapse, KinectA, blinkEye, etc) y hacer en Max un 'diccionario' de los valores que nos ofrece gracias a los objetos route y unpack.
- 2 Buscar una aplicación alternativa al bgcolor para el detector de movimiento.
- 3 Escribir la idea de proyecto en un archivo de texto y los pasos que serían necesarios para llevarlo a cabo. Estaría bien llegar al nivel de abstracción de escribir el 'algoritmo' que luego implentaremos en Max.
- 4 Usar la coordenada X del blob más grande (ejercicio 2_3) para mover un slider, este slider debe tener un rango  de 0 a 1. por lo que debereis usar el objeto 'scale'.
- 5 Ejercicio de nota: Recrear el funcionamiento interno de jit.rgb2luma ( ver comentarios en ejercicio 1_2) con un patch de max gracias al object jit.unpack y varios jit.op. La idea es conseguir el mismo efecto que rgb2luma pero con objetos alternativos, como si rgb2luma no existiera y debieramos conseguir su resultado a base de otros objetos de jitter.

- 6 Modificar el ejercicio 4 para que envie a la mochila dmx los valores de X e Y de un blob en los canales dmx 1 y 2.

- 7 Modificar el ejercicio 5 para que envie a través de la red local los valores X, Y y tamaño de los 4 primero blobs, de modo que se obtengan en el puerto 7110 los mensajes /Blobs/X1 , /Blobs/Y1 , /Blobs/T1 , /Blobs/X2 , etc

Enviadlos a contact@thomasvanta.es
