

Los operadores se utilizan para realizar diferentes cómputos entre variables y valores.

Algunos ejemplos son:


```C
#include <stdio.h>


/* Al principio del texto es útil poner comentarios que
expliquen cosas del programa:*/
// Programa: TallerCIntel.c
// Utilidad: Imprime en pantalla un mensaje de bienvenida.
// Programador: Hazel.
// Fecha: La de hoy.
// Versión: 1.0


int main() {
    printf("Hello, world!");

	int anhoNacimiento;
	printf("Por favor, introduce el año de su nacimiento y pulse enter: ");
	scanf("%d", &anhoNacimiento); 
	printf("El año de su nacimiento es: %d\n", anhoNacimiento);

	//Pero cuantos meses ha pasado desde mi nacimiento 
	int mesNacimiento;
	printf("Por favor, introduzca el número del mes de su nacimiento  y pulse enter: ");
	scanf("%d", &mesNacimiento); 

	
	int mesActual;
	printf("Por favor, introduce el número de mes actual y pulse enter: ");
	scanf("%d", &mesActual); 
	int mesesTotales = (2021 - anhoNacimiento) * 12 + ( mesActual - mesNacimiento);
	printf("Han pasado %d meses desde su nacimiento", mesesTotales, "desde su nacimiento");
	
}```{{copy}}

***Recordatorio:*** 

**Include Necesario**
Para todos los posibles escenarios de programación en C, es necesario agregar el include y para que ejecutar el código es necesario 1.

```C
#include <stdio.h>
int main()
{
    // Aqui iría el código
}```{{copy}}
}

Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}![image](https://user-images.githubusercontent.com/70983699/144491673-a7a9d377-68c8-4bbf-971d-49e660e3975f.png)

