# Instalacion_Git
Descripción de Instalación


USO GIT

- git config --version
- git config --global user.name "Lukas" --> (nombre del usuario)
- git config --global user.email "lukas_cmlp13@hotmail.com" --> (correo de github)
- git config --global -l  -->  verifica el usuario y email

- cd 'd/carpeta/nombre.archivo'  --> poner la direccion del archivo o jalarlo con el mouse
- git init 
- git status  --> verifica si hay cambios
- git add .  --> añade los cambios realizados
- git status  

- git commit -m "Commit Inicial"  --> comentar los cambios
- git status

-------Probar si hay cambios--------cambiar una parte del proyecto
- git status
- git diff -->  comparar la version anterior con la nueva si hay cambios 
- git checkout .  ------- borra los cambios realizados

------Hacer nuevo commit-----------modificar cualquier pagina
- git status
- git add .
- git commit -m "Especificar los cambios"

- git log  ---historial de versiones subidas

------------Agregar por cambios o creacion de nuevas carpetas----------------- 
-----Agregar cambios
- git status
- git add (nombre de archivo que vas a modificar)
- git commit -m "Se modifico la pagina index"
- git status --- solo se modifico el archivo seleccionado 

-----Ingresar nuevo archivo 
- git add js/
- git status
- git commit -m "Especificar cambios del proyecto"
- git status

----Borrar un add del repositorio si no se nesecita
- git status
- git add .
- git status
- git reset js/codigo.js
- git status

- git add . para volver a agregar
- git status
- git commit -m "Especificar los cambios"
- git status
- git log
q para volver a escribir 

------Crear repositorio en github------
subir repositorio
- git remote add origin (el link que esta al crear el repositorio)
- git push -u origin master

-- -----clonar proyecto-----
- cd ..   retroceder carpeta
- cd (nueva direccion de carpeta)
- git clone + direccion url
- cd nombrecarpeta/ (Nombre de la carpeta del repositorio)

si hay cambios del proyecto
- git add .
- git commit -m "especificar cambios"
- git push origin master (para subir el proyecto a la rama principal) pide login
