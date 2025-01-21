# COURSE PLATZI DJANGO

- django es un framwork escrito en python.
- primeramente fue usado para contruir blogs. 
- ejemplos son instagram y spotify.
- es facil de usar y te permite crear aplicaciones de cero.

## REQUISITOS PARA ESTE CURSO

- que sepas python. 
- que sepas programacion orientada a objetos.
- que sepas HTML Y CSS. 
- que sepas sobre los entornos virtuales. *para este casos usaremos poetry pero tambien es valido env o venv*


### USO DE POETRY 
- crea un nuevo entorno con `poetry init`
- añade django al entorno de poetry `poetry add django`

### CREACION DE UN NUEVO PROYECTO CON DJANGO
- el comando para crear un nuevo proyecto tenemos `django-admin startproject <nombre_proyecto>`
- con el comando `django-admin --help` nos proporciona todos los comandos posibles para el comando.
- para iniciar el servidor de pruebas usamos el comando `python manage.py runserver` *por defecto lo crear en el puerto 8000*
- para iniciar con una nueva app usamos `python manage.py startapp <nombre_aplicacion>` 

### LA ARQUITECTURA DE DJANGO
- la aquitectura de django se usa lo que se conoce como MODEL (modelo), VIEW (controlador), TEMPLATE (vista)
- 