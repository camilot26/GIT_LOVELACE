# comandos de GIT

## COMANDO PARA VER LA VERSION DE GIT 
- git --version


abrir la consola en la carpeta de codigo y poner code . 

## comandos para configuracion inicial de git

- git config --global users.name "Tejada"

- git config --global users.email "correo "

## comando para editar o ver la configuracion de git
para salir del edit ctrl + 0 y ctrl + x
y si es VIM esc y :wq


- git config --global --edit 
- git config --global --list 

## como iniciar git en un directorio 

-git init 


## comando para saber el estado de nuestros archivos 

-git status

## Comandos para listar las versiones de mi proyecto 

-git log 

git log --oneline  

## Comando para cambiar de versión


- git cheackout <id, dek commit o nombre de la rama>

## PASOS PARA CREAR UNA VERSION DE NUESTRO CODIGO 

1. AGREGAR TODO LOS ARCHIVOS AL COMMIT 

-git add. TODOS
-git add /*.js SOLO ARCHIVOS CON LA EXTENSION
-git add index.js UN SOLO ARCHIVO CON EL NOMBRE Y EL PUNTO DE LA EXTENSION 

2. tomar la foto del codigo (crear una nueva version)

- git commit -m "nombre del comit"

