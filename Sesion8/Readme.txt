ENUNCIADO SESION8


Usando como base el entregable de la sesi�n 7 (entregable: Ciudades y Pa�ses por GeoIP), utiliza MVC para separar la l�gica de negocio de la l�gica de la aplicaci�n y de la vista.

Debes utilizar la siguiente estructura de directorios:

- index.php

- app/

-- Models/

-- Controllers/

-- Views/

- libs/

Puedes utilizar libs para a�adir las clases como Database que debe ser agn�stico a la l�gica de negocio de la aplicaci�n.

Requisitos:

1. Para ejecutar el programa, se debe utilizar el �dispatcher� index.php.

2. La aplicaci�n deber tener un formulario para poder introducir la IP.

3. Debes utilizar las funciones Filter de php para obtener el dato del formulario.

3. La aplicaci�n debe calcular el n�mero de red a partir de la IP introducida para poder consultar la tabla city_blocks_ip4.

4. Debe aparecer como m�nimo la informaci�n de nombre de ciudad, pa�s, latitud, longitud y c�digo postal.

Consejos:

Donde hay m�s datos de IP es en Estados Unidos, para probar la aplicaci�n utiliza IPs  americanas.
Puedes utilizar librer�as externas para calcular el rango de ip a partir de la IP y mascara de red  (http://archive.ubuntu.com/ubuntu/pool/universe/p/php-net-ipv4/php-net-ipv4_1.3.4.orig.tar.gz)