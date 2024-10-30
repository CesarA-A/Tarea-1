# **_Tarea 1_**

## Descripcion

En la tarea 1 Introducción a Git aprendimos a crear nuestra cuenta en Git asi 
como un repositorio como sus caso en donde vimos los comandos en cada uno de 
ellos ademas de eso realizamos varios commit los cuales son cambios en nuestro 
repositorio, el programa que incluye nuestro repositorio en un hola mundo en 
Java el cual despues de cambio por un Hola Git 

## Como ejecutar un programa en Java

 
1. Asegúrate de tener instalado [Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html). 
2. Compila el programa ejecutando el siguiente comando en la terminal: javac HolaMundo.java.
3. Ejecuta java HolaMundo.

## Comando utilizados para Git 

Todos los comando para poder realizar la tarea 1 se encuentran en el [video](https://youtu.be/khxlEOkQrKM?si=WgSrFDXNV8N68Q4P) 

1. git config --global  user.name "Cesar Antunez":Se usa para establecer el nombre de usuario que aparecerá en tus commits de Git.
2. git config --global  user.email "correo con el que se realizo la cuenta":Establece el correo electrónico que se asocia con tus commits de Git.
3. cd "direccion de la carpeta".
4. git init:Lo utilizamos para inicializar un repositoria de Git con un directorio.
5. git remote add origin URL:Utilizado para vincular tu repositorio local con un repositorio remoto
6. git add -A:Por medio de este comando modificaremos los archivos que se han modificado,añadido o
eliminados.
7. git commint -m "Mensaje":Este nos permitira tener informacion hacerca de lo que se modifico el 
repocitorio.
8. git push origin master:Este comando sincroniza tu repositorio local con el remoto.
9. touch .gitignore:Es importante porque le indica a Git qué archivos o directorios deben ser ignorados y no rastreados.
10. git status

## Archivo .gitignore

Por medio de este archivo nos es posible decirle a Github que directorios o archivos deben ser ignorados y no rastreados, el cual creamos para poder ignorar debug.log.

Para poder realizar esto requerimos que en nuestro archivo colocar algunas instrucciones las cuales son:

1. /debug.log:Ignora solamente el archivo debug.log
2. debug.log:Ignora cualquier archivo de nombre debug.log
3. *.log:Ignora cualquier archivo con la extencion .log
4. **/logs:Ignora todas las carpeta .log

Lo que nos indica que si se estan ignorando los archivos .log necesitamos ir a nuestro repositorio y 
revisar que no aparezcan archivos con la extencio .log

 





