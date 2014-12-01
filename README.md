Tutorial de Git para Tajamar. 
=============================
Sergio Jimenez Romero - MCSD Web Apps and Mobile.
=================================================
 En este repositorio vamos a almacenar los ficheros que sean tratados en el tutorial.
 
 Como una referencia rápida aquí están las definiciones y comandos básicos.
 
Zonas
-----
* Working Copy: Espacio sobre el que trabajamos.

* Staging area: En esta zona colocaremos los ficheros que queremos que sean 'guardados' en el repositorio (commit).

* Repository: Lugar donde se almacenan los ficheros deseados del proyecto.

Comandos (En el git bash, precedidos por 'git')
--------
PARTE 1
* status: Estado actual del repositorio.
* log: Historial de commits hechos en ese repositorio.
* add "archivo": Añadir contenidos del 'working copy' al 'staging area'.
* reset HEAD "archivo": Devolver contenidos del 'staging area' al 'working copy'.
* checkout -- "archivo": Descarta los cambios en un fichero del 'working copy'.
* push: Envia a un repositorio remoto.
* pull: Descargar el contenido de un repositorio remoto.

PARTE 2
* branch: Listado de ramas del repositorio.
* checkout "rama": Moverse a una rama del repositorio.
* checkout -b "rama": Crear una rama y moverse a ella.
* merge "rama": Mezclar contenido de la rama actual y la elegida.
* branch -D "rama": Borrar rama del repositorio con todo su contenido.