**Resuelto**

Una posible solución para el problema anterior podría ser el siguiente:

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
  int anhoActual;
	printf("Por favor, introduce el número de año actual y pulse enter: ");
	scanf("%d", &anhoActual); 
	int mesesTotales = (anhoActual - anhoNacimiento) * 12 + ( mesActual - mesNacimiento);
	printf("Han pasado %d meses desde su nacimiento", mesesTotales, "desde su nacimiento");
	
}```{{copy}}


##Recordatorio

Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}![image](https://user-images.githubusercontent.com/70983699/145272131-d886a1b7-d2fb-444b-b8e2-92e601d0001a.png)
