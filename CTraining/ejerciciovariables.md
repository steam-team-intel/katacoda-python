
Ahora bien, usemos las variables en un contexto de la vida real.

En este caso, planteemos el problema de ***Quiero saber cuántos meses han pasado desde el mes de mi nacimiento**

Para esto vamos a necesitar la siguiente información:

- El año de su nacimiento 
- El mes de su nacimiento 
- El año actual 
- El mes actual 

**Primer paso:***  Definir las variables:

```C
int anhoNacimiento;
int mesNacimiento;
int mesActual;
int anhoActual;
```{{copy}}

***Segundo Paso:*** Solicitar esa información

Para solicitar información, C tiene una función especial para eso, Se imprime un texto para que el usuario entienda que nuestro programa le va a solicitar alguna información, por ejemplos:

```C
printf("Por favor, introduce el año de su nacimiento y pulse enter: "); ```{{copy}}

Una vez que el usuario ya puede saber que le estan solictan información, usamos la función de C.
  

**Scanf**: Analiza una entrada de datos con formato y carga el resultado a la varible que se defina, y funciona de la siguiente manera:

 ```C
scanf("%d", &anhoNacimiento); ```{{copy}}


Una vez tengamos toda la información que necesitamos, hay que proceder a hacer el calculo, el cual sería:

Su edad actual * 12 + (El mes actual - el mes de su nacimiento).

***En C sería algo así:


 ```C
int mesesTotales = (anhoActual - anhoNacimiento) * 12 + ( mesActual - mesNacimiento);
printf("Han pasado %d meses desde su nacimiento", mesesTotales, "desde su nacimiento"); ```{{copy}}
	


## Recordatorio

**Include Necesario**
Para todos los posibles escenarios de programación en C, es necesario agregar el include y para que ejecutar el código es necesario 1.

```C
#include <stdio.h>
int main()
{
    // Aqui iría el código
}```{{copy}}

Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}![image](https://user-images.githubusercontent.com/70983699/145272131-d886a1b7-d2fb-444b-b8e2-92e601d0001a.png)

