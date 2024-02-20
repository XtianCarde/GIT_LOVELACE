# (titulos con doble numeral) Comandos de git

## comando para ver la version de git 
*git -v
*git --version


## comandos para la confioguracion inicial de git 

* git config --global user.name "Your name" 
 "git = nombre de la tecnologia , config= lo que se le va a hacer a la tecnologia , --global= a todo el computador"
* git config --global user.email "Your Email"

## Comandos para editar o ver la configuracion git

*para salir del edit ctrl + o y ctrl + x y si es VIM es esc :wq

* git config --global --edit
* git config --global --list

## Como iniciar git en un directorio

* git init

## Comando para saber el estado de nueatros archivos
* git status

## comando para listar las versiones de mi proyecto
* git log ""
* git log --oneline ""

## comando para cambiar de version o devolverme la version
* git checkout <id del commit o nombre de la rama>

## pasos para crear una version de nuestro codigo 

1. Agregar todos los archivos al comit 
* git add .
* git add *.js "para agregar algunos con extencion en especifico"
* git add index.js "para agregar un archivo especifico"

2. Tomar la foto del codigo (crear una nueva version)

*git commit -m "Nombre del comit"



