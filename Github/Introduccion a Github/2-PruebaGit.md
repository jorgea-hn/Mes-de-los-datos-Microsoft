# Prueba de Git

## Configuracion de git

Comprobamos que git este instalado

`git --version`

Definimos variables globales user.name user.email

`git config --global user.name "<USER_NAME>"`

`git config --global user.email "<USER_EMAIL>"`

Reemplazamos las variables y colocamos nuestro usuario y email

Probamos que los cambios han funcionado con
`git  config --list`

## Configuracion del repositorio de Git

Creamos una carpeta que funcionara como directorio del proyecto

`mkdir <carpeta>`

vamos al directorio

`cd <carpeta>`

inicializamos el repo

`git init`

establecemos la rama principal como main
`git checkout -b main`

para mostrar el estado del arbol de trabajo utilizamos 
`git status`


el comando *ls* listara las carpetas o archivos de nuestro arbol de trabajo
*-a* es para mostrar los archivos o carpetas ocultas
`ls -a`


## Ayuda desde Git

Este comando te desplegara una lista de todos los comandos de git.
`git --help`



