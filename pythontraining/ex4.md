Dada la clase persona que se muestra elabore la función modificar nombre y agregue otro atributo que sea número de teléfono con una función que modifique y muestre este.


`class Persona():
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad
    def mostrarEdad(self):
        print(self.edad) 
    def modificarEdad(self,edad):
        if edad>0:
            self.edad = edad
            print(self.edad)
        else: 
            print("es un feto")`{{copy}}
            
            
Recuerde que para ejecutar archivos desde un IDE
Para crear un archivo basta escribir en la terminal:

`touch archivodeprueba.py`{{execute}}

Para ejecutar el archivo escriba en consola:

`python3 archivodeprueba.py`{{execute}}
