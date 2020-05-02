# GIT BRANCH MODEL
Es un modelo de trabajo en **Git** nos sirve para la creacion de proyectos de manera ordenada y facilita el entendimiento cuando se trabaja con varios usuarios que modifican el proyecto.
Este modelo cuenta con dos ramas principales:
* Rama master
* Rama develop
La rama **master** es la rama donde se encuentra el proyecto en ejecucion es decir que es el programa que esta ciendo ya usado o que sera usado.
La rama **develop** es la rama del desarrollo en ella se colocan las cosas que se iran inplementando con el tiempo en las diferntes actualizaciones.
Aparte de estas dos ramas se tienen otras ramas las cuales se consideran secundarias y pueden ser eliminadas despues de su uso estas son:
* Rama feature
* Rama release
* Rama hotfix
La rama **feature** es donde se crean nuevas caracteristicas del proyecto se deriva de la rama develop, luego de que las caracteristicas esten creadas  se devuelven a la rama develop, lo que significa que seran caracteristicas seguras y se implementaran en la siguiente actualizacion.
La rama **release** es donde la nueva version del proyecto esta lista para lanzarse esta rama deriva de la rama develop y se fusiona con la rama master al momento del lanzamiento aqui se generan algunas modificaciones si es necesario esta rama es para saber el tipo de actualizacion que recibira el proyecto por ejemplo 1.2 o 2.0 ayuda a gestionar mejor las versiones.
la rama **hotfix** es la que se encarga de repararar los errores que se generen pueden derivarse de la rama master si o de la rama develop dependiendo donde este el error luego de corregir el error se fusiona la rama para guardar los cambios realizados.
Esto seria basicamente el uso de **Git Branch Model**
