Las listas almacenan datos de cualquier tipo, son ordenadas y se pueden modificar.

Se puede crear una lista vacía mediante la siguiente sentencia:

`mi_lista = []
print(mi_lista)`{{copy}}

Esta sentencia crea una lista de enteros:

`mi_lista = [1, 2, 3, 4]
print(mi_lista)`{{copy}}

Y esta sentencia crea una lista de datos mixtos:

`mi_lista = ['hello', 9.6, 24, 'goodbye']
print(mi_lista)`{{copy}}

Al ser ordenadas, podemos obtener y modificar elementos por posición, por medio de lo que llamamos su índice:

`mi_lista = ['hello', 9.6, 24, 'goodbye']
print(mi_lista[0])
mi_lista[0] = 'hola'
print(mi_lista)`{{copy}}

Existen varios métodos para gestionar listas. Por ejemplo, con len() se obtiene el tamaño de una lista:

`len(mi_lista)`{{copy}}

Y el método insert() inserta un elemento en dada posición de la lista:

`mi_lista.insert(0,'hola')
print(mi_lista)`{{copy}}

Mientras que append() inserta un elemento al final. Pruebe insertar un elemento de cualquier tipo al final de mi_lista.

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{execute}}
