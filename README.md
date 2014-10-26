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
* status: Estado actual del repositorio.
* log: Historial de commits hechos en ese repositorio.
* add <archivo>: Añadir contenidos del 'working copy' al 'staging area'.
* reset HEAD <archivo>: Devolver contenidos del 'staging area' al 'working copy'.
* checkout -- <archivo>: Descarta los cambios en un fichero del 'working copy'.
* push: Envia a un repositorio remoto.
* pull: Descargar el contenido de un repositorio remoto.
