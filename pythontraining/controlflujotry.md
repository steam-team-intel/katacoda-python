
## Try except


Try, except, finally son ifs y elses que se ejecutan cuando ocurre un error conocido.


```python
dividendo = 5
divisor = 0
try:
    cociente = dividendo / divisor
    print(cociente)
except:
    print("No se permite la división por cero")

```{{copy}}

### Para ejecutar el archivo escriba en consola:

`python3 archivodeprueba.py`{{copy}}
