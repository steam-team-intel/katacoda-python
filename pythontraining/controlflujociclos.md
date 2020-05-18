## Whiles y Fors

Los whiles son ciclos con un punto final, se ejecutan siempre que la premisa posterior sea verdadera.


```python
x = 0
while x<4:
    print(x)
    x = x+1
```{{execute}}
    
Un ejemplo de while mas complejo:

```python
tarea = True
while tarea: #Se ejecuta siempre que sea verdadero
    print('Tengo que hacer la tarea')
    trabajar = True
    if trabajar:
        print('Empiezo a hacer la tarea')
        tarea = False

if tarea == False:
    print('Ya termine la tarea')
```{{execute}}

Los fors son ciclos que se ejecutan una cierta cantidad de veces.


```python
for i in range(3):
    print(i)
```{{execute}}

Note que corre hasta 2, la condicion de parada en python no es inclusiva.
