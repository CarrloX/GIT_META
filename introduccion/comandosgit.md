#configuracion
comando para conocer la version de github

-git -v
-git --version

comandos para configurar git por primera vez
-git config --global user.name "Your name"
-git config --global user.email "correo@correo.com"

comando para ver que usuario esta configurado o con que correo electronico

-git config --global user.name
-git config --global user.email
-git config --list

comando para inicializar git en un directorio

-git init

comando para el estado de los archivos
-git status

comando para ver todas las versiones de mi proyecto

-git log
-git log --oneline

comando para cambiar entre versiones 

-git checkout <nombre de la rama o del identificador de la version>
-git checkout --.

pasos para crear una version de mi codigo 

1. agregar los cambios
-git add .
-git add *.js
-git add hola.html

2. compremeter los archivos
-git commit -m "Descipcion del commit"

# comando para listar las ramas
git branch

