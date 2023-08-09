# DarkGamesSitioWeb
Sitio Web de DarkGames
Version 1.0.0.0
# Sobre el Sitio
El sitio de Dark Games es una pagina que representa a un local fisico de venta de Videjo juegos y reparacion de consolas. 
En la pagina los usuarios podran ver todos los productos que se ofrecen, su precio y su descripción.
Ademas ofrece un chat con el que podran comunicarse y realizar sus consultas.
# Tecnologias, frameworks y lenguajes utilizados
-HTML5 <br>
-CSS3 <br>
-Boostrap <br>
-NODE.js <br>
-SASS <br>
# Archivos
El desarrollo cuenta con 82 archivos en el root: <br>
-index.html: page principal del sitio<br>
-Carpetas: assets, css, js, pages, scss. Las cuales cuentan con los siguientes archivos y/o subcarpetas que distinguiremos una por una a continuación:<br>
## assets(59):
-Subcarpeta ico(2): contiene el archivo.ico que se muestra en el navegador y el mismo en formato .png. <br>
-Subcarpeta nav_icos(15): contiene los iconos en formato .svg que se muestran en el sitio.<br>
-Subcarpeta webP(42) contiene 3 archivos .webP, el banner, el logo y una imagen de la page about.html y 3 sub carpetas (portadasPS3, portadasPS4, portadasXONE) la finalidad de los archivos de estas subcarpetas es ser mostrados en las page.html. <br>
## css(2):
-Archivo: style.css que da estilo al sitio. <br>
-Archivo: style.css.map, que es el mapeo que hace SASS de sus archivos para trasladarlos a style.css. <br>
## js(1):
-Archivo: package.json, utilizado por Node.js. <br>
## pages(5):
-Archivo: about.html, información sobre los dueños y ,a tienda. <br>
-Archivo: inbox.html, mensajeria interna de la pagina. <br>
-Archivo: iniciar_sesion.html, login de usuarios. <br> 
-Archivo: registro.html, logup de usuarios. <br>
-Archivo: tienda.html, muestra los productos disponibles.<br>
## scss(15): 
-Archivo: style.scss, que enlaza los _partials.scss y los mapea en el archivo style.css. <br>
-Subcarpeta partials: en la cual se distinguen las subcarpetas base, layout, pages y utilities. Estas ultimas contienen los _partials.scss que son importados al archivo style.scss y dan estlo del sitio.

# Aclaraciones para el profesor
En este espacio voy a dejar acalaraciones para que el profesor lea y tenga en consideración.
1. en las subsecciones de archivos, se coloca el nombre de la carpeta y entre parentesis el total de archivos que contiene de la siguiente manera: nombre_carpeta(n).
2. inbox.html posee un modelo de chat en tiempo real que NO es funcional en la entrega final por poseer caracteristicas no vistas durante el curso.
3. registro.html posee un formulario de ingreso de datos NO funcional en la entrega final por poseer caracteristicas no vistas durante el curso.
3. iniciar_sesion posee un formulario de ingreso de datos NO funcional en la entrega final por poseer caracteristicas no vistas durante el curso.
