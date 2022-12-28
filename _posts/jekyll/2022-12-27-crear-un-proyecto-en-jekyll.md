---
layout: post
title: Primer Proyecto en Jekyll
categories: jekyll
tags: [jekyll]
date: 2022-12-02 22-00-00 
---
## Crear Proyecto con Jekyll

Para crear un nuevo proyecto con Jekyll, sigue estos pasos:

- Abre una consola o terminal en tu ordenador.

- Crea un directorio para tu proyecto con el comando `mkdir nombre_del_proyecto`. Reemplaza nombre_del_proyecto con el nombre que quieras darle a tu proyecto.

- Accede al directorio del proyecto con el comando `cd nombre_del_proyecto`.

- Ejecuta el comando `jekyll new` . para crear un nuevo proyecto de Jekyll en el directorio actual. Esto creará una estructura de directorios y archivos básica para tu proyecto.

## Estructura Basica de Jekyll
Una vez que nosotros tengamos creado nuestro proyecto con Jekyll vamos a poder visualizar diferentes carpetas y archivos ahi dentro, con el comando `code .`.
!["jekyll carpets"](/assets/images/post-jekyll/jekyll-carpets.png)

Para que podamos visulizar la pagina en el navegador debemos activar el servidor en la consola con este comando `bundle exec jekyll serve`
y pegar en el buscador esta **URL** `http://127.0.0.1:4000/`.

### Carpetas Estaticas
En Jekyll la carpeta **_site** es la carpeta donde se almacenan los archivos generados del sitio web estático, estos archivos son la version final del sitio, que se puede utilizar para publicar el sitio en un servidor web.
Cuando nosotros ejecutamos `bundle exec jekyll serve` Jekyll toma los archivos de tu sitio y los procesa para crear la version final dentro de la carpeta `site`. 

Esto incluye la conversion de los archivos [Markdown](https://www.markdownguide.org/basic-syntax/) o HTML en archivos estaticos, la aplicacion de plantillas y la inclusion de archivos de estilo y JavaScript.

**IMPORTANTE:** 
 Esta carpeta nunca debe ser modificada manualmente, siempre desde las respectivas carpetas de la raiz.


!["jekyll carpets"](/assets/images/post-jekyll/jekyll-carpets-serve-site.png)

en mi caso dentrod dentro de la carpeta `jekyll` se almacenan todas mis paginas con extension **HTML**

### Assets

Dentro de esta carpeta comunmente se guardan cosas que estan relacionadas con la apariencia y el disenio de nuestra pagina web. Estos archivos pueden ser imagenes, archivos de estilos CSS, archivos de JavaScript.
La idea de la carpeta `assets` es tener un lugar centralizado donde se encuentren todos los archivos de modo que sea facil encontrarlos y facil de enrutarlos.


