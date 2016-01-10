ENUNCIADO PRACTICA 5

Bas�ndote en el entregable de la sesi�n 4, debes crear un programa orientado a objetos, que muestre un listado de todas las im�genes del directorio �fotos�.

Debe contener las siguientes clases:

class File: esta clase se debe encargar de leer el directorio y obtener la lista de ficheros. Tambi�n debe contener un constructor donde se definir� la ruta de las fotos, cuando se instancie.

class Image:  esta clase hereda de File, ya que la imagen es un tipo de fichero. Tendr� m�todos espec�ficos para comprobar y validar las extensiones de las im�genes, crear las miniaturas y obtener las im�genes validadas.

class System: esta clase se encargar� de interactuar con el sistema, con un m�todo para ejecutar el comando convert.

 

Requisitos:

1. Para ejecutar el programa, solo se podr� instanciar la clase Image y ejecutar un solo m�todo p�blico.

2. Solo puede existir un m�todo p�blico en la clase Image y otro en System.

3. Todos los m�todos de File debe ser m�todos protegidos excepto el constructor.

4. La clase File debe tener los siguientes m�todos: __construct($path), createDir(), checkIfFileExists(), getFileList().

5. La clase Image debe tener los siguiente m�todos: createThumb(), validatePhoto(), getImages().

6. La clase System debe tener el m�todo execCommand().

7. Cada clase debe encargarse de su �mbito, los ficheros los gestiona File (mkdir, is_dir, is_file, opendir, readdir, closedir), las im�genes Image y el las ejecuciones del sistema la clase System.

8. La clase Image debe usar una constante para el nombre del directorio de las miniaturas, para usarse junto con el $path definido.

Para ejecutar el programa debes usar las siguientes l�neas, pudiendo cambiar la ruta de las fotos:

$path = "fotos";

$image = new Image($path);

$image_list = $image->getImages(); 

$image_list es un array, que puedes recorrer para mostrar las fotos en el HTML.

El resultado debe ser el mismo que el entregable 4 y se entregar� en un �nico fichero php.