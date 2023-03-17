# ¿Que es el control de versiones?
VCS, es un programa o cojunto de programas que realizan el seguimiento de los cambios en una coleccion de documentos.
Uno de los objetivos del VCS es recuperar versiones anteriores de archivos o del proyecto.
Otro de los objetivos es permitir el trabajo en equipo.

Otro nombre del VCS es "sistema de administracion de configuracion de software" (SCM).

con un VCS, puede:

* Ver todos los cambios realizados, cuando se hicieron los cambios y quien los realizo.
* Incluir un mensaje en cada cambio explicando los motivos.
* Recuperar versiones anteriores.
* Crear ramas, donde se crean cambios experimentales.
* Adjuntar etiquetas a las versiones.

## Control de versiones distribuido
Git es un sistema distribuido, lo que significa que el historial completo de un proyecto se almacena en el cliente y en el servidor.
Se pueden modificar archivos sin conexion de red, protegerlos localmente y sincronizarlos cuando haya conexion.

Si el servidor deja de funcionar los cambios quedan en local.
Los cambios pueden pasarse por correo electronico o compartise mediante medios extraibles.

## Terminologia de Git
* Arbol de trabajo: Cojunto de directorios y archivos anidados que contienen el proyecto.

* Repositorio (Repo): Directorio, el nivel superior de los archivos.
Un repositorio vacio es aquel que no forma parte de un arbol de trabajo y se usa para compartir o realizar copias de seguridad.

* Hash: Numero generado por una funcion hash, y representa el numero de un archivo.

* Objeto: Los repo contienen 4 tipos de objetos:
    1. Objeto blob: contiene un archivo normal
    2. Objeto arbol: Representa un directorio y contiene nombres, valores hash y permisos.
    3. Objeto confirmacion: Representa una version del arbol de trabajo.
    4. Etiqueta: Es un nombre asociado a una confirmacion.

* Confirmacion: Es crear un objeto de confirmacion, eso significa que se guardaron los cambios para que otros usuarios puedan verlos.

* Rama: Serie con nombre de confirmaciones vinculadas.

* Remoto: Es un repo remoto o en otro maquina o lugar.

* Comandos, subcomandos y opciones: Son las operaciones de Git, por ejemplo 
*git reset --hard*
git es el comando
reset es el subcomando
--hard es la opcion

## Git y GitHub
Git es un sistema de control de versiones, en que varios desarrolladores pueden colaborar para trabajar en un proyecto.

GitHub es una plataforma en la nube que usa Git, simplifica el proceso de colaboracion, mas herramientas de linea de comandos y un flujo integral, actua como repo remoto.

* Issues
* Debates
* Solicitudes de incorporación de cambios
* Notificaciones
* Etiquetas
* Acciones
* Horquillas
* Proyectos
