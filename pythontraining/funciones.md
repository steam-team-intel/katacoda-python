## Funciones
Las funciones computacionales funcionan como las matematicas, reciben un elemento y entregan un resultado a partir del mismo.

La siguiente función suma dos números

`
def funcion(entero1, entero2):
    print(entero1 + entero2)

`{{execute}}

Ahora probemosla utilizando un 1 y un 2. 

`funcion(1,2)`{{execute}}

Las funciones pueden tener valores por omisión:

`def funcion(entero1=1, entero2=2):
    print(entero1, entero2)
 
`{{execute}}

`funcion()`{{execute}}
