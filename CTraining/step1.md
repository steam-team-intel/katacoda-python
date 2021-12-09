Buenos días, 

## ¡Bienvenidos al taller de C de Iniciativas STEAM de Intel Costa Rica!


Lo primero que haremos será configurar el ambiente, compilar y ejecutar C.

Para este taller no es necesario instalar C en su computadora. Para comenzar sólo será necesario:

**1.** Darle click al siguiente enlace  `archivodeprueba.c`{{open}}. El cual creara una archivo de c en el cual puede empezar a programar.

Para 
**Hola Mundo C**

Para ejecutar cualquier programa de c, será necesario incluir la librería de stdio. h, la cual  es un archivo de encabezado que tiene la información necesaria para incluir las funciones relacionadas de entrada / salida en nuestro programa. Ejemplo printf, scanf, etc. Si queremos usar la función printf o scanf en nuestro programa, debemos incluir el stdio. h archivo de encabezado en nuestro código fuente. 


```c
#include <stdio.h>
int main()
{
    printf("Hello World"); 
}
```{{copy}}


## Recordatorio

**Compilación de C**

Una vez se han completado estos pasos, podemos compilar c en la terminal. Para esto sólo es necesario escribir: 

`gcc archivodeprueba.c -o programa`{{execute}}


**Ejecución de un archivo .c**

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}

***TIP:*** En este taller ejecutaremos este archivo constantemente. Sin embargo, no será necesario que escriba el comando cada vez que lo necesite. 
Puede darle click sobre los comandos.
