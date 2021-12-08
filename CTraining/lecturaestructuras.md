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
