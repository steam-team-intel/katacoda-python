## if,else,elif

Las herramientas de control de flujo regulan la ejecución de porciones de código dependiendo de diferentes parámetros o variables.
Los ifs se ejecutan si la porción de código que sigue después del if precede es verdadera.
if **a>b**:



```python
if (4==8):
    print('No se matematicas')
else:
    print('Si se matemáticas')
```{{execute}}


Los elifs sirven para probar otras condiciones ademas de la inicial
Cambie los valores de una_variable de manera que logre obtener las tres salidas.


```python
una_variable = 40
if una_variable > 10:
    print('La variable es completamente mas grande que 10.')
elif una_variable < 10:
    print('una_variable es mas chica que 10')
else: 
    print('una_variable es de hecho 10.')
```{{execute}}

Utilizando el código anterior, modifíquelo para obtener 'una variable es de hecho 10'.
