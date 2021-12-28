La herencia es un proceso mediante el cual se puede crear una clase hija que hereda de una clase padre, compartiendo sus métodos y atributos. Además de ello, una clase hija puede sobreescribir los métodos o atributos, o incluso definir unos nuevos.

Se puede crear una clase hija con tan solo pasar como parámetro la clase de la que queremos heredar. En el siguiente ejemplo vemos como se puede usar la herencia en Python, con la clase Vehiculo que hereda de Carro. Así de fácil.

**Paso 1: Definir la clase Padre**

```Python  
class Vehiculo():

    def __init__(self, color, ruedas):
        self.color = color
        self.ruedas = ruedas
     
     
     # Método para imprimir la información del objecto
    def __str__(self):
        return "La información de vehiculo es: color {}, {} ruedas".format( self.color, self.ruedas )```{{copy}}
        
**Paso 2: Crear la clase hija**

Una vez que creada la clase padre, para heredar la clase padre en la clase hija, en este caso, heredar la clase Vehículo en la clase carro, sería necesario instanciar un objeto vehículo desde el constructor de la clase carro, esto se puede realizar con la siguiente setencia: "Vehiculo.__init__(self, color, ruedas)"

```Python  
class Carro(Vehiculo):

    def __init__(self, color, ruedas, velocidad, cilindrada):
        Vehiculo.__init__(self, color, ruedas)
        self.velocidad = velocidad
        self.cilindrada = cilindrada```{{copy}}
        


***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{execute}}

