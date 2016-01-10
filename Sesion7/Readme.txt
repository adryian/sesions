Enunciado sesion7

Utilizando la base de datos creada en la sesi�n 6, tienes que desarrollar un programa en php para consultar ciudades y pa�ses a partir de una IP.


El programa debe contener las siguientes clases:

Class Database: una clase para gestionar la conexi�n a MySQL y la ejecuci�n de las sentencias SQL.
 

Class GeoIP: una clase para consultar la informaci�n de ciudad y pa�s a partir de una IP.
 

Requisitos:

Para ejecutar el programa, solo se podr� instanciar la clase GeoIP y ejecutar un solo m�todo p�blico.
Se debe poder ejecutar el programa desde l�nea de comando, pas�ndole como primer argumento la IP.
Debe aparecer la informaci�n de nombre de ciudad, pa�s, latitud, longitud y c�digo postal como m�nimo.