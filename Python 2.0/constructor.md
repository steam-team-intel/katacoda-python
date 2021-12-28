Cada vez que se crea un objeto, se llama a un método para crearlo. Ese método se llama constructor.

El constructor se crea con la función init. Como parámetro escribimos la palabra clave self, que se refiere a sí mismo (el objeto). El proceso visualmente es:

![image](https://user-images.githubusercontent.com/70983699/146961504-bd769f88-b07e-49df-b2ea-7651a7e4bdb9.png)

Dentro del constructor inicializamos tres variables: nombre, forma y chips. A veces, las variables se denominan propiedades en el contexto de la programación orientada a objetos.

```Python  
class Galleta:
	# Constructor
	def __init__(self, nombre, forma, chips='Chocolate'):
		# Instance attributes
		self.nombre = nombre
		self.forma = forma
		self.chips = chips```{{copy}}
    

El objeto recién creado ahora tiene las variables establecidas, sin tener que definirlas manualmente. Puede crear decenas o cientos de objetos sin tener que establecer los valores cada vez.

Python __init__
La función init (self) construye su objeto. No son solo las variables que puede establecer aquí, también puede llamar a métodos de clase. Todo lo que necesita para inicializar los objetos.

Digamos que tienes un avión de clase, que una vez creado debería empezar a volar. Hay muchos pasos involucrados en el despegue: acelerar, cambiar de flaps, cerrar las ruedas, etc.

```Python  
class Avion:
    def __init__(self):
        self.alas = 2

        # fly
        self.conducir()
        self.despegar()
        self.cerrarruedas()

    def conducir(self):
            print('Acelerando')

    def despegar(self):
            print('Iniciando el vuelo.... Despegando')

    def cerrarruedas(self):
            print('Cerrando las ruedas del avion')```{{copy}}
 
Las acciones predeterminadas se pueden definir en métodos. Estos métodos se pueden llamar en el constructor.


    
***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{execute}}

