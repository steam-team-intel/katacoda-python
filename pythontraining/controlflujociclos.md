## Ciclos while  
Los ciclos while ejecutan una porción de código en bucle mientras una premisa sea verdadera.

Cada ejecución de dicha porción de código se llama una iteración. La condición se verifica al principio de cada iteración, para determinar si el ciclo debe romperse.


```python
# Ciclo while que espera hasta que se tire un 0
num = "no"
while num != "0":  # This constructs an infinite loop
   num = input("Ingrese un número, digite 0 para salir:")
   print ("Usted ingresó: ", num)

 

print ("Se salió del WHILE")
```{{copy}}

```python
x = 0
while x<5:
    print(x)
    x += 1
```{{copy}}

```python
estudiantes = ['Andrés', 'Ana', 'Julián'] #lista de estudiantes
while estudiantes: #mientras haya elementos en la lista
    print(estudiantes.pop(-1)) #imprime estudiante y lo saca de la lista
```{{copy}}

***PD: ***Veremos más sobre listas y su manejo más adelante. 
    
Otro ejemplo de while donde se ve claramente cómo se verifican las condiciones:

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
```{{copy}}

## Ciclos for  

Los ciclos for se ejecutan una cantidad específica de veces.

Son útiles para recorrer elementos, es decir, recorrer una secuencia elemento por elemento. 

Hacen uso de un contador para determinar cuántas iteraciones llevan y cuándo deben parar. Por convención, se suele llamar a dicho contador "i".

El contador inicia en 0 de forma predeterminada, pero esto se puede cambiar:

```python
for i in range(1, 6): #cuenta de 1 a 5 (debe ser menor a 6)
    print(i)
```{{copy}}

```python
for i in range(5): #cuenta 0 a 4 (debe ser menor a 5)
    print(i)
```{{copy}}

```python
for i in range(2, 20, 2): #empieza en 2, debe ser menor que 20, incrementa i de dos en dos
    print(i)
```{{copy}}

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{execute}}
