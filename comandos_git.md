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

## comando para cambiar de version 
* git checkout <id del commit o nombre de la rama>
* git checkout <nombre de la rama "Main">


## pasos para crear una version de nuestro codigo 

1. Agregar todos los archivos al comit 
* git add .
* git add *.js "para agregar algunos con extencion en especifico"
* git add index.js "para agregar un archivo especifico"

2. Tomar la foto del codigo (crear una nueva version)

*git commit -m "Nombre del comit"



# ---------------------- RAMAS --------------------------------

*Las ramas en git nos facilita la dependencia de codigo

- merge : es el proceso de integrar los cambios de una rama y los combine con otra.


## Comando para listar las ramas de mi repositorio 
git branch "Listar las ramas"
git branch -v "Crear una nueva rama"

# crando rama
git branch nombre_rama
git switch nombre_rama 
git checkout -b nombre_rama (crea la rama y hace el cambio)

# comando para eliminar una rama

git branch -D nombre_Rama


# Comando para cambiar el nombre de una rama

git branch -M nuevo_Nombre