Otro uso muy común del comando grep es utilizarlo junto a otros comandos, la idea es utilizar el resultado del primer comando y aplicarle a este un patrón de búsqueda con grep

Para ver esto  vamos a realizar el siguiente ejemplo utilizando el comando tail  podemos obtener las últimas líneas de un archivo `tail -n 3 littlePrince.txt`{{execute}} , ahora vamos a elegir una palabra buscar y vamos a realizar la obtención de estas últimas líneas junto con el  comando grep de la siguiente manera `tail -n 3 littlePrince.txt | grep -win palabra`{{copy}}

Sí al comando grep le agregamos la opción -e  nos permite  poder buscar más de un patrón a  la vez: `tail -n 3 littlePrince.txt | grep -wine palabra -wine palabra2`{{copy}} 

También podemos buscar no simplemente en un archivo en específico sino que en todo un directorio de la siguiente manera: `grep -win palabra ./*.*`{{copy}} 

Por último podemos hacer una búsqueda recursiva en subdirectorios dentro de un directorio en el que estemos de la siguiente manera `grep -winR palabra ./`{{copy}} 
