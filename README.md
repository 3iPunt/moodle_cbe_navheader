# moodle_cbe_navheader

HTML Nav Header

## Descripción

El proyecto contiene dos archivos:

* nav_header_auth.html: Cabecera cuando el usuario está autenticado.
* nav_header_no_auth.html: Cabecera cuando el usuario no está autenticado.
* nav_header_html.html: Archivo con cabecera HTML para mostrar el resultado.

El HTMl se compone de un elemento 'nav' padre que contiene los siguientes 'div':

*  navbar-burger: Menú hamburguesa para funcionalidad de la aplicación. Podrá estar oculto si no se necesita.
*  navbar-logo: Contenedor del logotipo.
*  navbar-header-course: Es un bloque que se utilizará en Moodle. Estará vacío por defecto y se sobrescribirá en Moodle.
*  navbar-auto: Es un bloque que se utilizará en Moodle. Estará vacío por defecto y se sobrescribirá en Moodle.
*  navbar-lang: Por el momento, no habrá menú de idiomas, pero lo dejamos por si acaso.
*  navbar-menu-apps: Contenedor del menú de aplicaciones.
*  navbar-usernav: Contenedor para el menú de usuario.

## Estilos CSS

Los estilos CSS están incrustados en línea en cada etiqueta

## Dependencias

* Bootstrap 4: https://getbootstrap.com/docs/4.0/getting-started/introduction/
* Font-Awesome 4: https://fontawesome.com/v4.7.0/get-started/
