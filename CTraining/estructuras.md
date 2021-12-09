

Las estructuras son colecciones de variables relacionadas bajo un nombre.
Las estructuras pueden contener variables de muchos tipos diferentes de datos a diferencia de los arreglos que contienen unicamente elementos de un mismo
tipo de datos.

- Colección de una o más variables, pueden ser de diferentes tipos, agrupadas bajo un mismo nombre para un mejor manejo.
- Permiten organizar datos complicados y facilitan la manipulación de la información, al tratar como una unidad un grupo de variables, en lugar de tratarlas como variables separadas.


## Definición de la estructura

Para interactuar con la estructura es necesario usar la librería de String.h, string.h es un archivo de la Biblioteca estándar del lenguaje de programación C que contiene la definición de macros, constantes, funciones y tipos y algunas operaciones de manipulación de memoria.


```C
#include <stdio.h>
#include <string.h>
 struct Libros  {
   char  titulo[50];
   char  autor[50];
   char  tema[100];
   int   NoLibro;
};
```{{copy}}

## Inicializar las estructuras

Las estructuras pueden ser inicializadas, para ser inicilizada la estructura se debe declarar de la siguiente manera:
***struct*** NombreEstructura nombreInstancia;
De esta manera creamos una instancia, sin embargo, aún no tiene los atributos que anteriormente se habían defido para la estructura.

Seguidamente, para darle valor a esos atributos usamos la funcion ***strcpy(s1,s2)***, la cual, copia el string que apunta a s2 al objeto apuntado por s1.

Para esto, usamos el siguiente ejemplo: 

```C
/* Declaramos la funcion */
void imprimirInfoLibro( struct Libros libro );

int main( ) {
   /* Declaramos libro1 como tipo Libro */
   struct Libros libro1;  
   /* Declare Libro2 como tipo Libro */
   struct Libros libro2;        
 
   /* Informacion sobre libro1 */
   strcpy( libro1.titulo, "Romeo y Julieta ");
   strcpy( libro1.autor, "William Shakespeare"); 
   strcpy( libro1.tema, "Tragedia");
   libro1.NoLibro = 01;

   /* Informacion sobre libro2 */
   strcpy( libro2.titulo, "Los Cuentos de mi Tia Panchita");
   strcpy( libro2.autor, "Carmen Lyra");
   strcpy( libro2.tema, "Cuentos infantiles");
   libro2.NoLibro = 6495700;


   return 0;
} ```{{copy}}

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

`./programa`{{execute}}
