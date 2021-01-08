Los conjuntos son colecciones de datos no ordenados y únicos, se pueden modificar y se les pueden aplicar operaciones de conjuntos matemáticos.

El siguiente código crea un conjunto. Pruebe ejecutarlo varias veces y analice el resultado obtenido:

`canasta_frutas = {'manzana', 'naranja', 'manzana', 'pera', 'naranja', 'banano'}
print('Elementos canasta: ', canasta_frutas)
`{{copy}}

Como podrá observar, los elementos repetidos se obvian. 

Tal y como en los conjuntos matemáticos, se puede verificar la pertenencia de un elemento a un conjunto:

`print('Hay papaya? ', 'papaya' in canasta_frutas)
`{{copy}}

Dado que no hay papaya, podemos modificar el conjunto y añadir este elemento:
`canasta_frutas.add('papaya')
print('Elementos canasta: ', canasta_frutas)
`{{copy}}

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{copy}}
