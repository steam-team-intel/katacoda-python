Una sentencia es una instrucción que C puede ejecutar.

## Ejecutar una sentencia:

Debe copiar en su archivo de prueba:

```C
#include <stdio.h>
int main()
{
    printf("Hello World"); 
}
```{{copy}}

Como podrá ver las sentencias son, en esencia, órdenes que se dan al Programa.

```C
#include <stdio.h>
int main()
{
    printf("Hello World"); 
    printf(1); 
}
```{{copy}}

Estas sentencias incluyen un llamado al método "printf()", que nos da como salida la entrada que le pasemos.
No todas las sentencias tienen una salida. Por ejemplo, si copia en su archivo:

```C
#include <stdio.h>
int main()
{
    int costo = 20000;
}
```{{copy}}

Podrá observar como el archivo se ejecuta correctamente, pero no muestra nada en la consola. 


## Recordatorio:

**Include Necesario*
Para todos los posibles escenarios de programación en C, es necesario agregar el include y para que ejecutar el código es necesario 1.

```C
#include <stdio.h>
int main()
{
    // Aqui iría el código
}```{{copy}}

Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}
