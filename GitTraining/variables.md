Crea una nueva confirmación que contiene el contenido actual del índice y con el mensaje de confirmación que describe el cambio.

## ejecutar Commit

Ahora procedemos a tomar una foto o copia del estado actual de nuestro proyecto para esto se utilizara el comando `git commit`{{execute}}.

Para poder realizar la copia se necesita saber quien es la persona que lo está realizando para esto tenemos que añadir nuestro nombre y correo con los comandos 

`git config --global user.email "you@example.com"`{{copy}}

`git config --global user.name "Your Name"`{{copy}}

Para confirmar que se configuro bien escribiremos el comando `git config -l`{{execute}}.

Una vez que se tiene configurado Git se puede realizar el commit, para esto utilizaremos el comando `git commit -m "primer commit"`{{execute}}.
