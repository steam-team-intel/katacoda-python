
Que paso si queremos guardar nuestro proyecto en la nube.

**Git remote y repositorios online**

Lo primero que tenemos que hacer es crear un nuevo proyecto en algún repositorio online (GitHub, GitLab, etc).

Una vez creado el proyecto tenemos que conectar nuestro proyecto "local" a nuestro repositorio online para eso se utilizara el siguiente conjunto de comandos:

`git remote add origin https://github.com/WebinarGit/proyecto.git`{{copy}}

`git branch -M main`{{copy}}

`git push -u origin main`{{copy}}

Al hacer esto GitHub nos pedirá usuario y contraseña para poder realizar la acción, en este caso por  cuestiones de seguridad no se podrá realizar pero al realizarlo desde un ambiente seguro (IDE, Terminal de Git) se podrá realizar fácilmente.
