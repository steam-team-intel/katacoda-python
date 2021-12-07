

Las estructuras son colecciones de variables relacionadas bajo un nombre.
Las estructuras pueden contener variables de muchos tipos diferentes de datos a diferencia de los arreglos que contienen unicamente elementos de un mismo
tipo de datos.

- Colección de una o más variables, pueden ser de diferentes tipos, agrupadas bajo un mismo nombre para un mejor manejo.
- Permiten organizar datos complicados y facilitan la manipulación de la información, al tratar como una unidad un grupo de variables, en lugar de tratarlas como variables separadas.


## Definición de la estructura

```C
#include <stdio.h>
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

## ¿Comó imprimo  la información de los libros?

Para imprimir la información de los libros será necesario realizar dos pasos, el primero sería crear una función que me permita imprimir la información y el segundo paso es llamar esa función desde el main.



***Paso 1***: Función para imprimir la información del libro 

```C
/* Funcion para Imprimir Información sobre cualquier libro tipo Libro */

void imprimirInfoLibro( struct Libros libro ) {
   printf( "Titulo del libro : %s\n", libro.titulo);
   printf( "Autor del libre : %s\n", libro.autor);
   printf( "Tema del libro : %s\n", libro.tema);
   printf( "Identificador del libro : %d\n", libro.NoLibro);
   printf( "******************************************* %s\n" );
} ```{{copy}}

***Paso 2***: Llamar la función 

Para llamar la función lo debemos de hacer desde el ***main***, entonces, las siguentes dos sentencias, irían antes de cerrar con llave (}) el main.

```C
   /* Imprimir Información sobre libro1*/
   imprimirInfoLibro( libro1 );

   /* Imprimir Información sobre libro2 */
   imprimirInfoLibro( libro2 );
```{{copy}}

## Ejecución del archivo

***Recordatorio:*** Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}
