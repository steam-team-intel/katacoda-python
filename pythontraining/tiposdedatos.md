


El concepto de tipo de datos es importante en programación, pues cada tipo de datos cuenta con una funcionalidad diferente.

En Python se manejan varios tipos de datos de diferentes categorías. Los tipos más básicos y utilizados son *int, float, string* y *bool*.

Sin embargo, existen muchos más, como *complex, list, tuple, dict, set, bytes* ...

Para comprobar el tipo de un dato basta con hacer un llamado al método type(). Pruebe ejecutando las siguientes líneas.


```python
print(type(1))
```{{copy}}

```python
print(type(3.4))
```{{copy}}

```python
print(type('hola'))
```{{copy}}

```python
print(type(True))
```{{copy}}

En Python también es posible especificar un tipo de datos si se desea:

```python
frase = str("Hello World!")
num = int(2021)
print(type(frase),type(num))
```{{copy}}

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{copy}}
