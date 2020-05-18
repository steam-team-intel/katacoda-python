## Switches
Los switches no son tan naturales en Python como si en otros lenguajes de programacion. Los switches sirven para ejecutar una porcion de codigo u obtener un valor dado un caso.


```python
def switch_demo(argumento):
    switcher = {
        1:'Enero',
        2:'Febrero',
        3:'Marzo',
        4: 'Abril',
        5: 'Mayo',
        6: 'Junio',
        7: 'Julio',
        8: 'Agosto',
        9: 'Septiembre',
        10: 'Octubre',
        11: 'Noviembre',
        12: 'Diciembre'
}
    print(switcher.get(argumento,'Mes invalido'))
    
switch_demo(2) 
```{{execute}}

Escriba diferentes valores dentro de *switch_demo()*
