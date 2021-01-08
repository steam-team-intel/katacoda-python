Las herramientas de control de flujo regulan la ejecución de porciones de código dependiendo de diferentes parámetros o variables.

Las condicionales sirven para ejecutar una porción de código si una premisa es verdadera.

```python
if (4==8): # Si 4 es igual a 8
    print('No sé matemáticas')
else: # En caso de que 4 no sea igual a 8
    print('Sí sé matemáticas')
```{{copy}}

Los elifs sirven para encadenar varias condiciones, y comprobar las mismas:

```python
num = 40
if num > 10:
    print('El número es más grande que 10.')
elif num < 10:
    print('El número es más pequeño que 10.')
else: 
    print('El número es, de hecho, 10.')
```{{copy}}

Utilizando el código anterior, cambie los valores de la variable "num" de manera que logre obtener las tres salidas. 

También es posible anidar condicionales, es decir, comprobar unas condiciones dentro de otras:

```python
x=3
color='azul'

if color == 'azul':
    if x>10:
        print('x es grande')
    elif x>0:
        print('x es pequeño')
    else:
        print('x es negativo')
else:
    print('el color no es azul!')
```{{copy}}

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{copy}}

