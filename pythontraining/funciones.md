Una función es un bloque de código que se ejecuta cada vez que se hace un llamado a la misma. Es código reutilizable.

Se les puede pasar datos como parámetros, y pueden retornar datos como resultado.

La siguiente función suma dos números:

`def suma(entero1, entero2):
    print(entero1 + entero2)`{{copy}}

Al definir esta función, se puede llamar a la misma de la siguiente manera:

`suma(1,2)`{{copy}}

Pruebe llamar a la función sin especificar parámetros y analice el resultado.

Las funciones pueden tener valores por omisión, es decir, paramétros predeterminados:

`def suma(entero1=1, entero2=2):
    print(entero1 + entero2)
    `{{copy}}

`funcion()
funcion(3,4)`{{copy}}

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{copy}}
