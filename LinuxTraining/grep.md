 El comando "grep" toma una expresión regular de la línea de comandos, lee la entrada estándar o una lista de archivos, e imprime las líneas que contengan coincidencias para la expresión regular.
 
 Para ver el funcionamiento de este comando vamos a crear un archivo con un texto un poco más complejo, en este caso lo vamos a tomar del libro <a href="https://blogs.ubc.ca/edcp508/files/2016/02/TheLittlePrince.pdf" target="_blank">Little Prince</a>.

Lo primero que vamos a hacer es crear el archivo utilizando el comando "nano" de la siguiente manera `nano littlePrince.txt`{{execute}}

Para ver en terminal lo que tiene un archivo sin necesidad de abrir un editor de texto se puede utilizar el comando "cat" de la siguiente manera `cat littlePrince.txt`{{execute}}

Una vez tenemos el archivo con el contenido deseado vamos a hacer un pequeño ejemplo del uso de comando grep. `grep and littlePrince.txt`{{execute}}

Ahora vamos a hacer uso de las opciones, si utilizamos la opción **-w**  va a buscar por palabra en vez de por caracteres como lo hace  por defecto `grep -w and littlePrince.txt`{{execute}}

Las búsquedas las va realizar con el patrón exacto que nosotros pongamos,  es decir, sí usamos un patrón como por ejemplo AND, no nos va a dar ningún resultado: `grep -w AND littlePrince.txt`{{execute}}, para poder buscar con un patrón en el cual ignoré estás diferencias podemos utilizar la opción **-i** de la sig manera: `grep -wi AND littlePrince.txt`{{execute}}

La siguiente opción que vamos a ver **n** la cual nos permite identificar en que línea del documento se encuentra el patrón a buscar `grep -n and littlePrince.txt`{{execute}}

También, con el comando grep se puede obtener las líneas  que no contienen el patrón dado, para esto se usa la opción **v**: `grep -nv and littlePrince.txt`{{execute}} 

Para limitar la cantidad de líneas que nos muestra en consola se utiliza la opción **m** `grep -nm 3 and littlePrince.txt`{{execute}} y para contar la cantidad de veces que el patrón se encuentra entonces tendremos que usar la opción **c** `grep -c and littlePrince.txt`{{execute}}
