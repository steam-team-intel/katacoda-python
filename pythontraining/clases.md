## Clases

Las funciones computacionales funcionan como las matematicas, reciben un elemento y entregan un resultado a partir del mismo.

La manera en la que se declara una clase es la siguiente: 

`class Mascota:
    def __init__(self, especie):
        self.spp = especie
    def obtener_especie(self):
        print(self.spp)`{{execute}}

Creamos una instancia de la clase:

`Mia = Mascota('Oso')
Mia.obtener_especie()`{{execute}}
