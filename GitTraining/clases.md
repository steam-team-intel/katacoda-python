Python se basa en clases para representar objetos. Estos objetos tienen asociados atributos y métodos, y unos objetos interactúan con otros.

La manera en la que se declara una clase es la siguiente: 

`class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad
    def presentacion(self):
        print("Hola! Mi nombre es " + self.nombre)
        `{{copy}}

El método __init__ funciona como método constructor de nuestra clase Persona. Define los atributos con los que se creará un objeto de tipo Persona.

También se puede observar que los métodos de Python siempre incluyen una referencia a sí mismos, por convención.

Una clase se puede ver como una definición abstracta de un objeto. Una **instancia**, por otro lado, es una concreción de dicho objeto. 

Para crear instancias de la clase Persona:

`persona1 = Persona('Miguel', 19)
persona2 = Persona('Paula', 23)`{{copy}}

Una vez se ha instanciado una clase, se puede llamar a los métodos de la misma. Los métodos son funciones asociadas a una clase.

`persona1.presentacion()
persona2.presentacion()`{{copy}}

***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{copy}}
