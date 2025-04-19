# Hello GIT
¿Qué es git?
- Control de versiones. Maneja las diferentes versiones de nuestro código.
- Permite trabajar con varias versiones de tu código.
- Se pude trabajar de forma local sin necesidad de internet.
----------------------------------------------------------------------------
¿Qué es GITHUB?
- Plataforma online para guardar tus repositorios GIT.
- Permite trabajar en equipo.
- Puedes crear portafolios públicos o privados
----------------------------------------------------------------------------

FLUJO DE TRABAJO EN GIT
============================================================================
- Working Directory: Carpeta donde trabajas. (tu código actual)
- Staging Area: Zona donde se realizan los cambios pero no se guardan en el
repositorio.
- Local Repository: Repositorio en la computadora. (Despues del commit)
- Remote Repository: Repositorio en la nube


COMANDOS BÁSICOS EN LA TERMINAL
============================================================================

- cd nombre_carpeta  //change directory. Permite acceder a una carpeta.
- cd ..              // Sale de la carpeta hija a la padre.
- ls 		     // Permite listar los archivos de la carpeta.
- mkdir nombre       // Permite crear una carpeta.
- touch main.py	     // Crea un fichero en la carpeta.

----------------------------------------------------------------------------
COMANDOS BÁSICOS DE GIT
============================================================================
- git init 	     //Inicializa un repositorio local en la carpeta actual.
- git add .          //Agrega todos los cambios hechos en el stagging area.
- git commit -m "msj" //Guarda esta version del proyecto.
- git status 	     // Muestra el estado de la versión que trabajamos.
- git config --global user.name “Jesus Brancacho”
- git config --global user.email “jbrancacho14@gmail.com”
- git branch -m main //Cambia el nombre de la rama MASTER por MAIN.
- git log	     //Permite ver el historial,
- git checkout	     //Permite moverse entre versiones.
- git revert e98585
- git graph
- git log --graph
- git log --graph --pretty=oneline
- git log --graph --decorate --all --oneline
- git config --global alias.tree "log --graph --decorate --all --oneline"
- git add .gitignore //Archivo para ignorar otros **/.DS_Store
- git diff	     //Ver los cambios sin hacer commit
- git reset --hard 6baff03 //Elimina la versión
- git tag clase_1    //Le pone un atributo
- git brunch login   //Crea una rama
- git switch login   //Cambia de rama
- git merge main 
- git stash 	     //Guardar los cambios sin hacer commit.
- git stash list
- git stash pop
- git stash drop
- git branch -d login //Elimina la rama
- git merge login
- git checkout -b feature 1 //crea y cambia de rama
- git commit --amend -m 'new files' //cambia el nombre del commit
----------------------------------------------------------------------------
COMANDOS BÁSICOS PARA TRABAJAR CON GITHUB
============================================================================
- git remote origin  https://github.com/usuario/repositorio.git 
- git push origin    //Guarda los cambios en el repositorio de github
- git fetch origin
- git pull origin main //Trae cambios de la remote a la local y las fusiona en tu rama actual
- git clone https://github.com/usuario/repositorio.git  //clona un repositorio de la nube en local
- fork               //Crear un repositorio ajeno en mi cuenta ya que no puedo editar el original.





- git flow init  
- git flow feature start 2auth
- git flow release start 1.0
- git flow release finished 1.0
- git cherry-pick 0ce2fc3 //traer un commit completo al final de nuestra rama
- git rebase 0ce2fc3 
