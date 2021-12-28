Las clases proveen una forma de empaquetar datos y funcionalidad juntos. Al crear una nueva clase, se crea un nuevo tipo de objeto, permitiendo crear nuevas instancias de ese tipo. Cada instancia de clase puede tener atributos adjuntos para mantener su estado. Las instancias de clase también pueden tener métodos (definidos por su clase) para modificar su estado.


Las clases de Python proveen todas las características normales de la Programación Orientada a Objetos: el mecanismo de la herencia de clases permite múltiples clases base, una clase derivada puede sobre escribir cualquier método de su(s) clase(s) base, y un método puede llamar al método de la clase base con el mismo nombre. Los objetos pueden tener una cantidad arbitraria de datos de cualquier tipo. Igual que con los módulos, las clases participan de la naturaleza dinámica de Python: se crean en tiempo de ejecución, y pueden modificarse luego de la creación.
## Creación de una clase

Para crear una clase será necesario escribir la palabra reservada de python **class**, seguido del nombre de la clase, de esta manera "class Cafe:". Una clase esta compuetsa por dos elementos, el primero el constructor, donde se define cuales son los atributos que queremos en nuestra clase, de la siguiente manera:

```Python
class Cafe:
        # Constructor
        def __init__(self, nombreCafe, precio):
                self.nombreCafe = nombreCafe name
                self.precio = float(precio)```{{copy}}

El segundo elemento de las clases de Python son los métodos 
```Python
        # Revisar si tengo presupuesto para comprar el cafe      
        def revisar_presupuesto(self, presupuesto):
                # Revisar si el presupuesto es valido, es un entero o un float
                if not isinstance(presupuesto, (int, float)):
                        print('Ingrese un presupuesto valido, un float o un entero')
                        exit()
                if presupuesto < 0: 
                    print('Lo siento, usted no tiene  dinero') 
                    exit()```{{copy}} 
                    
```Python                   
        # Funcion que me dice cuanto dinero me queda al pagar el café           
        def obtener_cambio(self, presupuesto):
                return presupuesto - self.precio
        
        def vender(self, presupuesto):
                self.revisar_presupuesto(presupuesto)
                if presupuesto >= self.precio:
                        print(f'Usted no puede comprar el  {self.name}')
                        if presupuesto == self.precio:
                                print('Completo')
                        else:
                                print(f'Su cambio es de {self.obtenerCambio(presupuesto)}$')

                        exit('Gracias por su transacción')```{{copy}}


***Recordatorio:*** Para ejecutar desde consola, ingrese el comando:

`python3 archivodeprueba.py`{{execute}}
