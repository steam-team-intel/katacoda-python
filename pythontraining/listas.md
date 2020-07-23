## Listas

Las listas almacenan datos de cualquier tipo, no todos tienen que ser iguales. 
La cantidad de datos en una lista es accesible a traves del comando _len()_

Este comando crea una lista vacía:

`mi_lista = []
print(mi_lista)`{{copy}}


Este comando crea una lista de enteros:
`mi_lista = [1, 2, 3]
print(mi_lista)`{{execute}}

Este comando crea una lista de datos mixtos:

`mi_lista = [1, "Hello", 3.4]
print(mi_lista)`{{copy}}

Este comando obtiene un objeto de la lista por índice:

`print(mi_lista[1])`{{copy}}

Este comando obtiene el tamaño de una lista:

`len(mi_lista)`{{copy}}

Este comando saca el ultimo elemento de la lista:

`mi_lista.pop()`{{copy}}

`print(mi_lista)`{{copy}}

Este comando inserta un elemento en dada posición de la lista:

`mi_lista.insert(0,'hola')
print(mi_lista)`{{copy}}

Append agrega al final de la lista:

`mi_lista.append('hola')
print(mi_lista)`{{copy}}

### Para ejecutar desde consola
`python3 archivodeprueba.py`{{copy}}
