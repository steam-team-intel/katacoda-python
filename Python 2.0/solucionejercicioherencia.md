**Resuelto**

Una posible solución para el ejercicio anterior es:

```Python
class Vehiculo():

    def __init__(self, color, ruedas):
        self.color = color
        self.ruedas = ruedas

    def __str__(self):
        return "La información de vehiculo es: color {}, {} ruedas".format( self.color, self.ruedas )

class Coche(Vehiculo):

    def __init__(self, color, ruedas, velocidad, cilindrada):
        Vehiculo.__init__(self, color, ruedas)
        self.velocidad = velocidad
        self.cilindrada = cilindrada

    def __str__(self):
        return " color {}, {} km/h, {} ruedas, {} cc".format( self.color, self.velocidad, self.ruedas, self.velocidad, self.cilindrada )

class Motoclicleta(Vehiculo):

    def __init__(self, color, ruedas, velocidad, cilindrada):
        Vehiculo.__init__(self, color, ruedas)
        self.velocidad = velocidad
        self.cilindrada = cilindrada

    def __str__(self):
        return "La información de la motocicleta es: color {}, {} km/h, {} ruedas, {} cc".format( self.color, self.velocidad, self.ruedas, self.velocidad, self.cilindrada )

 class Bicicleta(Vehiculo):

    def __init__(self, color, ruedas, velocidad, tipo):
        Vehiculo.__init__(self, color, ruedas)
        self.tipo = tipo

    def __str__(self):
        return "La información de la bicicleta es: color {}, {} km/h, {} ruedas, {} cc".format( self.color, self.velocidad, self.ruedas, self.tipo )       

class Camioneta(Vehiculo):

    def __init__(self, color, ruedas, carga):
        Vehiculo.__init__(self, color, ruedas)
        self.carga = carga

    def __str__(self):
        return Vehiculo.__str__(self) + ",  {} km/h, {} ruedas, {} toneladas".format( self.color, self.velocidad, self.carga )       

coche = Coche("azul", 150, 4, 1200)
print(coche)```{{copy}}

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{execute}}

