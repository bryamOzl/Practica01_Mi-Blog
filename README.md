# Practica01_Mi-Blog

 	FORMATO DE INFORME DE PRÁCTICA DE LABORATORIO / TALLERES / CENTROS DE SIMULACIÓN – PARA ESTUDIANTES

CARRERA: Ingeniería de Sistemas	ASIGNATURA: Programación Hipermedia
NRO. PRÁCTICA:	1	TÍTULO PRÁCTICA: Creación de sitio web usando HTML5
OBJETIVO ALCANZADO:
Entender y organizar de una mejor manera los sitios de web en Internet.
Crear sitios web aplicando estándares actuales.
Desarrollar aplicaciones web interactivas y amigables al usuario.
ACTIVIDADES DESARROLLADAS
1.	Crear un repositorio en GitHub con el nombre “Practica01 – Mi Blog”
Para poder realizar esto lo primero que tenemos que hacer es crear una cuenta en GitHub.
Ya con la cuenta creada procedemos a crear nuestro repositorio para la práctica.
 










Luego ya podremos crear nuestro repositorio para el proyecto.
 
2.	Realizar un commit y push por cada requerimiento de los puntos antes descritos.
a.	Para realizar esto tenemos que entrar en el siguiente programa. Esto primero tenemos que descargar un ejecutable desde la página Git e instalarlo.
 
b.	Primero tenemos que a la capeta donde se encuentra nuestro proyecto y luego procedemos a ingresar nuestro usuario de GitHub y nuestro coreo.
C:\>cd C:\xampp\htdocs\bryam\practica1

C:\xampp\htdocs\bryam\practica1>git config --global user.name "bryamOzl"

C:\xampp\htdocs\bryam\practica1>git config --global user.email "bryan95_19@hotmail.com"

C:\xampp\htdocs\bryam\practica1>git config --global -l
 






c.	Luego iniciamos el repositorio para nuestro proyecto de la siguiente forma.
C:\xampp\htdocs\bryam\practica1>git init
 

Luego procedemos a cargar nuestro proyecto o a realizar nuestro commit.
C:\xampp\htdocs\bryam\practica1>git add .
 

d.	Luego procedemos a ingresar la ruta de nuestro repositorio y también a cargar los cambios que vayamos realizando en nuestro proyecto.
C:\xampp\htdocs\bryam\practica1>git remote add origin https://github.com/bryamOzl/Practica01_Mi-Blog.git

C:\xampp\htdocs\bryam\practica1>git push origin master




 

e.	Luego para cargar los cambios que realizamos en nuestro proyecto tenemos que ejecutar las siguientes líneas y nos avisara los cambios que realizamos y también podemos ver en nuestro repositorio los cambios cargados.
C:\xampp\htdocs\bryam\practica1>git add .
C:\xampp\htdocs\bryam\practica1>git commit -m "Practica01_Mi-Blog"
C:\xampp\htdocs\bryam\practica1>git push origin master
 
 
3.	Capturas del código desarrollado.
a.	Etiquetas utilizadas para desarrollar el blog.
<! Doctype html>: Etiqueta que usa en HTML5.
<html> </html>: Etiqueta usada para abrir y cerrar el documento html.
<head> </head>: Etiqueta para la cabecera.
<meta />: Configurar datos en lo referente al documento.
<title> </title>: Para establecer el título de la página aparecerá en la pestaña.
<body> </body>: Para establecer el contenido de la página.
<header> </header>: Para la cabecera.
<img />: Etiqueta usada para la inserción de imágenes.
<li> </li>: Etiqueta usada para poner los ítems de la lista.
<section> </section>: Utilizada para crear una sección del documento.
<article> </article>: Para una composición del documento.
<h1> </h1>: Titulos de nivel 1.
<p> </p>: Insertar parrafos.
<aside> </aside>: Etiqueta usada para poner anuncios, citas de documentos, notas, entre otros.
<br />: Para crear un santo de línea.
<footer> </footer>: Para colocar el pie de página.
<center></center> Para centrar la información o imágenes.
<font></font>: Para dar formato a las letras o el fondo estableciendo las opciones que uno desee utulizar.
<li></li>: Para insertar un punto como guion.
<a></a>: Para crear una referencia.

b.	Estructurar un sitio web estático usando HTML5. El sitio web será informativo sobre un tema que será autoría del estudiante. El sitio web deberá contar con una página principal denominada index.html y debe contener al menos cinco páginas *.html más organizadas en varias carpetas. Todas las páginas contaran con un menú de navegación que permitirá al usuario moverse entre todas las páginas HTML.

 

Como vemos en nuestra carpeta esta establecida lo anterior pedido.





c.	Aquí tenemos el código de la página index.
 

d.	Lo siguiente es cumplir la estructura de la siguiente forma.
 

En donde, la etiqueta <header> deberá contener una imagen (logo) relacionada al tema elegido.
Además, la etiqueta <footer> deberá tener la información del estudiante como nombres completos, organización, correo (usar hipervínculo, mailto), teléfono (usar hipervínculo, tel), además deberá tener el símbolo de copyright junto a la leyenda de “Todos los derechos reservados”. Por ejemplo, © Todos los derechos reservados.

Las páginas *.html deberán tener al menos una etiqueta <section>, <article> y
<aside>.
De igual manera, se pide que al menos una de las páginas dentro del contenido
de la etiqueta <article>, tengan los siguientes requisitos:
• Una tabla con la siguiente estructura:
 
• Un video de YouTube (ver, etiqueta <iframe>).
• Manejar listas ordenadas o desordenadas con al menos cinco ítems.
• Tener al menos cinco etiquetas de texto que se encuentran en la figura 1-
16 del texto guía de la asignatura.

Para lo anterior esta el código en historia.htlm sería el siguiente:
 
 

e.	Finalmente, se pide que una de las páginas tenga al menos dos secciones(<section>) con tres artículos (<article>) cada sección. Luego, cada sección debe tener un encabezado (<header>), en donde, se ubicarán enlaces que permitan navegar entre los artículos usando id’s (ver, página 63 del texto guía).

Para lo anterior el código esta en el archivo llamado solibres.html.
  




4.	Al finalizar la práctica se debe validar todas las páginas HTML creadas usando el W3C Validator.
a.	Archivo index.html.
 

b.	Archivo historia.html.
 














c.	Archivo venydes.html.
 
d.	Archivo linuxvswindoes.html.
 















e.	Archivo solibres.html.
 
f.	Archivo noticias.html.
 
5.	Luego, se debe crear el archivo README del repositorio de GitHub.

RESULTADO(S) OBTENIDO(S):

CONCLUSIONES:
RECOMENDACIONES:

Nombre de estudiante: Bryam Gabriel Mora Lituma


Firma de estudiante: 

