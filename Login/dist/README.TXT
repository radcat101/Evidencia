========================
BUILD OUTPUT DESCRIPTION
========================
Este archivo es de uso público es portable y puede ejecutarse en cualquier computadora. 

Para ejecutar el proyecto desde la línea de comandos, vaya a la carpeta dist y
escriba lo siguiente:

java -jar "Login.jar" 

Para distribuir este proyecto, comprima la carpeta dist (incluida la carpeta lib)
y distribuir el archivo ZIP.

Notas:

* Si dos archivos JAR en la ruta de clase del proyecto tienen el mismo nombre,
El archivo JAR se copia en la carpeta lib.
* Solo los archivos JAR se copian en la carpeta lib.
Si la ruta de clase contiene otros tipos de archivos o carpetas, estos archivos (carpetas)
no se copian.
* Si una biblioteca en la ruta de clase de los proyectos también tiene un elemento Class-Path
especificado en el manifiesto, el contenido del elemento Class-Path tiene que estar en
la ruta de ejecución de los proyectos.
* Para establecer una clase principal en un proyecto Java estándar, haga clic con el botón derecho en el nodo del proyecto
en la ventana Proyectos y elija Propiedades. A continuación, haga clic en Ejecutar e introduzca el
nombre de clase en el campo Clase principal. Alternativamente, puede escribir manualmente el
nombre de clase en el elemento de clase principal del manifiesto.
