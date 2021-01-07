Algunos conceptos importantes referentes al formato del código son:

## Comentarios

En programación, existen señaladores para indicarle al intérprete si debe ignorar una línea o porción de código.

En Python, se utiliza "#" para una sola línea, y " ''' " para bloques de código.

Los comentarios son útiles para hacer pruebas de porciones aisladas de código, o para incluir aclaraciones y/o documentación interna.

Ejecute el siguiente código:

```python
print('Deseo que esta línea se ejecute')
#print('Esta línea no debe ejecutarse')
'''frase='Este bloque no debe ejecutarse'
print(frase)'''
```{{copy}}

## Indentación

Si bien la legibilidad del código siempre es importante, en Python es particularmente vital.

La indentación es el margen antes de iniciar una línea, y denota la jerarquía que debe seguir el código al ejecutarse.

En Python, un código mal indentado puede potencialmente dar error, aunque la lógica sea correcta.
