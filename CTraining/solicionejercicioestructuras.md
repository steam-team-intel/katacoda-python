**Resuelto**

Una posible solución para el problema anterior podría ser el siguiente:

```C
#include <stdio.h>
#include <string.h>

/* Al principio del texto es útil poner comentarios que expliquen cosas del programa:*/
// Programa: TallerCIntel.c
// Utilidad: Creación de estructura de estudiante y su respectiva lectura
// Programador: Hazel.
// Fecha: La de hoy.
// Versión: 1.0

struct Estudiante  {
   char  Nombre[50];
   char  Carrera[50];
   char  Sede[100];
   int   Carnet;
};

/* Declaramos la funcion */
void imprimirInfoEstudiante( struct Estudiante estudiante );

int main( ) {

   struct Estudiante estudiante1;        /* Declaramos estudiante1 como tipo Estudiante */
   struct Estudiante estudiante2;        /* Declare estudiante2 como tipo Estudiante */
 
   /* Informacion sobre estudiante1 */
   strcpy( estudiante1.Nombre, "Jimena Morales Brenes");
   strcpy( estudiante1.Carrera, "Administracion de tecnologia de Informacion"); 
   strcpy( estudiante1.Sede, "Cartago");
   estudiante1.Carnet = 01;

   /* Informacion sobre estudiante2 */
   strcpy( estudiante2.Nombre, "Arnoldo Rodriguez Jimenez");
   strcpy( estudiante2.Carrera, "Derecho");
   strcpy( estudiante2.Sede, "San Jose");
   estudiante1.Carnet = 02;
 
   /* Imprimir Información sobre estudiante1*/
   imprimirInfoEstudiante( estudiante1 );

   /* Imprimir Información sobre estudiante2 */
   imprimirInfoEstudiante( estudiante2 );

   return 0;
}

/* Funcion para Imprimir Información sobre cualquier estudiante tipo Estudiante */

void imprimirInfoEstudiante( struct Estudiante estudiante ) {

   printf( "Nombre del estudiante : %s\n", estudiante.Nombre);
   printf( "Carrera del estudiante : %s\n", estudiante.Carrera);
   printf( "Sede del estudiante : %s\n", estudiante.Sede);
   printf( "Carnet del estudiante : %d\n", estudiante.Carnet);
   printf( "******************************************* %s\n" );
}```{{copy}}





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
