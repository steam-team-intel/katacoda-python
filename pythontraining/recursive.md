## Recursividad

Las funciones recursivas se llaman a sí mismas para resolver un problema.

La funcion factorial se crea de la multiplicacion de todos los numeros previos.

!![Factorial](https://wikimedia.org/api/rest_v1/media/math/render/svg/d3f9070191e1fbdfffcb7174059ea8aa64cf2588)


`def factorial(n):
    if n == 1: #condicion de parada
        return n
    else: 
        return n*factorial(n-1)`{{execute}}
  
Llamamos a la función como:
`factorial(3)`{{execute}}

