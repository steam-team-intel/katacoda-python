Para realizar esta sección vamos a ubicarnos en el directorio de "Dulces" dentro del directorio de "Recetas".

Renombrar un archivo que tengamos ya creado se puede hacer utilizando el comando "mv" de la siguiente forma: `mv Galletas.txt Sopa.txt`{{execute}}

Este comando también nos sirve para mover archivos de un directorio a otro `mv Sopa.txt /root/Recetas/Saladas/`{{execute}}

Es importante destacar que este comando también sirve para mover directorios, aún si tienen contenido dentro. 

Ahora, para copiar un archivo vamos a utilizar el comando "cp" de la siguiente forma: `cp Helado.txt Arroz.txt`{{execute}}

Además, el comando "cp" tiene la funcionalidad de copiar un archivo a otro directorio de la siguiente forma: `cp Arroz.txt  /root/Recetas/Saladas/`{{execute}}

¿Qué pasa si lo que queremos es copiar un directorio? Para eso tenemos que hacer el uso del modificador **-R**  en el comando "cp", vamos a devolvernos a la carpeta recetas y vamos a  ejecutar el siguiente comando `cp -R Dulces/ Faciles/`{{execute}}
