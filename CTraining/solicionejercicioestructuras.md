**Resuelto**

Una posible solución para el problema anterior podría ser el siguiente:

```C
#include <stdio.h>

/* Al principio del texto es útil poner comentarios que
expliquen cosas del programa:*/
// Programa: TallerCIntel.c
// Utilidad: Interactua con el usuario para preguntarle información necesaria para imprimir en pantalla cuantos meses tiene el usuario
// Programador: Hazel.
// Fecha: La de hoy.
// Versión: 1.0


#include <stdio.h>
#include <string.h>

struct Estudiante  {
   char  Nombre[50];
   char  Carrera[50];
   char  Sede[100];
   int   Carnet;
};

/* Declaramos la funcion */
void imprimirInfoEstudiante( struct Estudiante estudiante );

int main( ) {

   struct Estudiante estudiante1;        /* Declaramos libro1 como tipo Libro */
   struct Estudiante estudiante2;        /* Declare Libro2 como tipo Libro */
 
   /* Informacion sobre estudiante1 */
   strcpy( estudiante1.Nombre, "Hazel Arias Abarca ");
   strcpy( estudiante1.Carrera, "Administracion de tecnologia de Informacion"); 
   strcpy( estudiante1.Sede, "Cartago");
   estudiante1.Carnet = 01;

   /* Informacion sobre libro2 */
   strcpy( estudiante2.Nombre, "Arnoldo Rodriguez Jimenez");
   strcpy( estudiante2.Carrera, "Derecho");
   strcpy( estudiante2.Sede, "San Jose");
   estudiante1.Carnet = 02;
 
   /* Imprimir Información sobre estudiante1*/
   imprimirInfoEstudiante( estudiante1 );

   /* Imprimir Información sobre libro2 */
   imprimirInfoEstudiante( estudiante2 );

   return 0;
}

/* Funcion para Imprimir Información sobre cualquier libro tipo Libro */

void imprimirInfoEstudiante( struct Estudiante estudiante ) {

   printf( "Nombre del estudiante : %s\n", estudiante.Nombre);
   printf( "Carrera del estudiante : %s\n", estudiante.Carrera);
   printf( "Sede del estudiante : %s\n", estudiante.Sede);
   printf( "Carnet del estudiante : %d\n", estudiante.Carnet);
   printf( "******************************************* %s\n" );
}```{{copy}}




## Recordatorio 

Para ejecutar desde consola, es necesario compilar el archivo con los cambios realizados:

Puede utilizar al archivo "archivodeprueba.c" creado anteriormente. 

**Compilación de un archivo .c**

`gcc archivodeprueba.c -o programa`{{execute}}

**Ejecución de un archivo .c**

Para ejecutar el archivo, escriba el siguiente comando en la terminal:

`./programa`{{execute}}
