CONFIGURACIÓN DE GIT

    git --version -> Versión de Git

    git config --global -> configuración para todos los proyectos de ahora en adelante

    git config --global user.name "Nombre del usuario" -> ponemos el nombre del usuario

    git config user.name -> vemos el nombre

    git config --global user.email "Correo del usuario"

    git config user.email -> vemos el email

    git config --global color.ui true -> habilita los colores de los comandos


CONCEPTOS BÁSICOS

    Control de versiones, como Git, permite controlar las diferentes versiones de nuestros proyectos. No solo sirve para el desarrollo web, sino para cualquier cosa que estés programando. Lo que nos permite Git es tener las diferentes versiones de un sitio web conforme va pasando el tiempo. Gracias a Git podemos ver los cambios que hacen los usuarios y unirlos en un código principal. Es muy util para trabajar en equipo al mismo tiempo en un mismo proyecto.

    Las ramas son versiones de tu web duplicadas donde haces pruebas e implementas nuevas ideas para luego aplicarlas a la rama principal o main, es decir, a tu proyecto.

    Commits -> Son las nuevas versiones / cambios que hagas

    Staying index

PRIMEROS COMANDOS
    Ruta: D:\Curso - Diseño Web\Git y Github
    git init -> Iniciamos el repositorio en el que nos encontramos
    git status -> El estado de tu repositorio
    git add nombre del archivo -> Envia el archivo al Staying index para empezar a hacer los commits, es como dar de alta en git
    git add . -> añadimos TODOS los archivos del repositorio al staying index
    git commit -m "Agregando index.html" -> Realizamos el cambio, debemos ponerle un nombre descriptivo, ¿por qué has hecho el cambio?