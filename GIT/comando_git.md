#Configuración

Comando para conocer la versión de github:

git -v
git --version


Comandos para configurar git por primera vez:

git config --global user.name "Valeria"
git config --global user.email "valehm248@gmai.com"


Comando para ver qué usuario está configurado o con qué correo electrónico:

git config --global user.name
git config --global user.email
git config --list


Comando para inicializar git en un directorio:

git init


Comando para ver el estado de nuestros archivos:

git status


Comando para ver todas las versiones de mi proyecto:

git log 
git log --oneline


Comando para cambiar entre versiones :

git checkout <nombre de la rama o del identificador de la versión>
git checkout --.


Pasos para crear una versión de mi código:

1. Agregar los cambios

git add .
git add *. js, html o css
git add archivo.html

2. Comprometer los archivos

git commit -m "Descripción del commit"









