Una sentencia es una instrucción que el intérprete de Python puede ejecutar.

## Ejecutar una sentencia:

Debe copiar en su archivo de prueba:

```python
#include <stdio.h>
printf('Hola mundo!')
```{{copy}}

Como podrá ver las sentencias son, en esencia, órdenes que se dan a la consola de Python.

```python
printf(2021)
```{{copy}}

Estas sentencias incluyen un llamado al método "printf()", que nos da como salida la entrada que le pasemos.
No todas las sentencias tienen una salida. Por ejemplo, si copia en su archivo:

```python
int x = 5
```{{copy}}

Podrá observar como el archivo se ejecuta correctamente, pero no muestra nada en la consola. 


***Recordatorio:*** Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}
