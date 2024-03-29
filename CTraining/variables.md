Las variables son nombres que tienen asociado un tipo de valor y un valor, algo así como una referencia.

Decimos que una variable (en general, cualquier objeto en programación) tiene un nombre significativo cuando éste especifica su utilidad o contenido.

En C es necesario declarar las variables y especificar su tipo de datos. Las variables se crean al asignarles valor.

**Tipo string** 

En C no existe un tipo predefinido para manipular cadenas de caracteres (string). Sin
embargo, el estándar de C define algunas funciones de biblioteca para tratamiento de
strings .
El formato para declarar un string es:

char nombre[longitud];

```C
#include <stdio.h>

int main() {
  char frase[10] = "Hola mundo";
  printf(frase);
 }
```{{copy}}

**Tipo entero** 

En el siguiente ejemplo, se puede hacer referencia a costoproducto:

```C
#include <stdio.h>

int main() {
   int costoproducto = 1000;
   printf(costoproducto);
}
```{{copy}}

**Tipo float** 
```C
#include <stdio.h>

int main() {
float impuesto = 0.13;
printf("El valor del impuesto es de : %f\n", impuesto);
}
```{{copy}}

**Tipo booleano** 
```c

#include <stdio.h>

int main() {
 bool valor = false;
  if(valor){
    printf("El valor es verdadero");
  }
  else{
    printf("El valor es falso");
  }
}
```{{copy}}


## Recordatorio:

**Include**

Para todos los posibles escenarios de programación en C, es necesario agregar el include y para que ejecutar el código es necesario utilizar el main como se muestra a continuación: 

```C
#include <stdio.h>
int main()
{
    // Aquí iría el código
}```{{copy}}

Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}
