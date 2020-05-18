## Herencia

La herencia se da cuando un objeto se basa en otro para ser creado, utiliza los mismos metodos que la clase original. Existe un objeto de origen de todos los objetos cuyo tipo es obj.


`class Gatito(Mascota):
    def __init__(self, color, raza):
        Mascota.__init__(self, 'Gato')
        self.gcolor = color
        self.graza = raza
    def obtener_raza(self):
        print(self.graza)
    def print_school(self):
        print(self.gcolor)`{{execute}}

Para crear una instancia de la clase:

`Max = Gatito('Naranja', 'Callejero')
Max.obtener_raza()
Max.obtener_especie()`{{execute}}

El nivel de abstraccion puede aumentar innecesariamente

`class Esfinge(Gatito):
    def __init__(self, color, feo):
        Gatito.__init__(self,color, 'Esfinge')
        self.feura = feo 
    def obtener_feura(self):
        print(self.feura)`{{execute}}
        
`Tina = Esfinge('Piel','Horrenda')
Tina.obtener_feura()`{{execute}}

