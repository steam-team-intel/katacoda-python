## Crear, borrar y mover archivos

A continuación vamos a crear un nuevo directorio. Para esto vamos a hacer uso del siguiente comando: `mkdir nuevoDir`{{execute}}

Una vez ejecutado este comando tendríamos un nuevo directorio al cual podríamos acceder con el comando "cd" y dentro poder guardar nuestros archivos o programas si así lo deseamos. Imaginemos que nos equivocamos al crear el  directorio y deseamos eliminarlo para eso tenemos que hacer uso del siguiente comando:`rmdir nuevoDir`{{execute}}

Ahora, vamos a crear un archivo, para esto vamos a crear de nuevo un directorio con el comando anteriormente visto y vamos a acceder a él con el comando "cd",  una vez dentro de dicho directorio vamos a hacer uso  del comando "touch"  el cual nos sirve para poder crear archivos de cualquier tipo como por ejemplo: `touch archivodeprueba.py`{{execute}} o `touch texto.txt`{{execute}}

Una vez más pensemos que nos equivocamos a la hora de crear dichos archivos y deseamos eliminarlos para esto vamos a hacer uso del siguiente comando: `rm archivodeprueba.py`{{execute}}

¿Qué pasa si quiero eliminar un directorio con todos los archivos que tiene dentro? Para esto vamos a ir de nuevo al directorio raíz y vamos a probar varios comandos  primero:`rmdir nuevoDir`{{execute}}  y ahora vamos a probar el comando:`rm -R nuevoDir`{{execute}}
