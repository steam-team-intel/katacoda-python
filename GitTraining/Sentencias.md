Este comando crea un repositorio vacío de git.

## Ejecutar git init.

Para inicializar un repositorio de git solo hace falta ejecutar el comando `git init`{{execute}}

Para ver si el comando anterior funcionó ejecutaremos el comando `ls -a`{{execute}} que nos permite ver el contenido oculto de una carpeta.

Editar los archivos(archivodeprueba.py y texto.txt) con lo que se desee.

Para poder ver el estado de Git en nuestro proyecto ejecutaremos el comando `git status`{{execute}}.

Al ejecutar dicho comando nos dará un resultado como el siguiente:

`On branch master`

`Initial commit`

`Untracked files:`
`  (use "git add <file>..." to include in what will be committed)`

`        archivodeprueba.py`
`       texto.txt`

`nothing added to commit but untracked files present (use "git add" to track)`

Esto nos dice varias cosas, primero en cual branch(rama) estamos posicionados, segundo nos dice que estamos en un commit inicial, luego nos muestra el nombre de los archivos que git no este monitoreando de color rojo y los que si de color verde.

Es importante ver este comando pues nos dirá lo que está y no en nuestro repositorio.

Para añadir estos archivos al repositorio tenemos que utilizar el comando `git add texto.txt`{{execute}}.

Pruebe haciendo cambios y utilizando el comando `git status`{{execute}}.


