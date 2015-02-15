Frontend:
Es la persona que crea experiencias basadas en codigo dentro del cliente. Llevar todas esas ideas de diseño al cliente.
Tambien esta encargado de la Usabilidad.

El cambio de idiomas es por dominio.

<title> Es el que se refleja en las busquedas, debe contener entre 60 a 70 catacteres maximo.

<meta name="description" content="Contenido de la etiqueta"/> Tiene un contenido relevante SEO, y debe contener entre 155 a 160 caracteres. Describe a la pagina

<meta name="keywords" content="html, css"/> Ya no es obligatoria ya que los navegadores buscan esta informacion de forma semantica.

<header> : Cabecera de la pagina
<figure> : Html5 reconoce como una etiqueta que tiene una imagen.
<figcaption> : Va la descripcion de la imagen.

<h1> : Es el titulo principal, y debe escribirce una sola vez por pagina.

<nav> : Navegacion.

<section> : Seccion del contenido de la pagina, puede contener articles.

<article> : Contiene contenido de la pagina.

<h2> : Subtitulos que pueden ser varios en una misma pagina.

<div> : Para dividir bloques.
<span> : Para definir estilos diferentes a parte del texto de una linea.

<footer> : Es el pie de pagina.

<strong> : Permite resaltar a un texto.
<em> : Enfacis, italica

<link> : Permite agregar un archivo css.
<style> : Permite agregar css en la misma pagina.
<script> : Agregar javascript

--
normalize.css : Permite normalizar los estilos predefinidos para los navegadores.

reset: recetea los valores a 0.

jquery : Permite normalizar algunas funcionalidades de javascript.

Colores ligth, para diseños flat design.

em : Medidad relativas, coje la medida del padre mas cercano por como su unidad, ejemplo el principal puede tener 16px, esto equivale a 1em.

rem: Es una medida relativa, pero escoje de la raiz, en este caso del body.

display: block = Hace un ancho completo a la pagina.
display : inline-block = Toma el ancho del contenido de la caja.

-----
GITHUB

Git:
Es un sistema de control de versiones.

GitHub:
Commint: Es una tarea completa, permite aceptar cambios.
Push: Permite enviar al servidor

-------
Foundation:
Es un framework Css, provee de muchas clases t widgets.
Es movile firts.
Framework: Es un conjunto de herramienteas para hacer algo, que tiene una estructura y sintaxis.

Humans.txt: Aqui se lo indica quien es el autor de la pagina.
robots.txt: Se le puede indicar que ningun buscador lo indexe

OOCSS: Css Orientado a Objetos (oocss.org):
Usar clases que sean basicas y sean reutilizables en todo nuestro sitio. Hacer todos los estilos utilizando clases, sin utilizar tag ni ids. Lo que tanbien un tag puede tener n clases, y pueden ser heredados.

Organizacion de Informacion:
Trabajan con filas y columnas, para armar el layout, las filas pueden tener hasta el maximo 12 columnas.

Medidas:
Para empesar las medidas van estar basadas en movile firts:
small: Afecta a los dispositivos moviles mas pequeños.
medium: Afecta a las tabletas y dispositivos de regular resolucion.
large: Para las laptops o pantallas gigantes.

Para que sea movil fist, se deve agregar las clases en el siguiente orden: small-* medium-* large-*

Equalizer:
Permite igualar el alto de los paneles.
Al padre se le debe agregar el atributo:data-equalizer
A los hijos se les debe agregar el atributo: data-equalizer-watch.
Esto hace que detecte el panel que este mas alto y los asigne a todos los hermanos.

Atributos
data-topbar: Permite las capacidades de los row downs.

Foundation utiliza jquery

--------
Stylus
neff: Framewor de stylus, que nos provee snipets de codigo.
------
Responsive Design:
Foundation:
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
-----
Sublime Text
Duplicar Contenido: Selecciono, Ctrl + Shift + D

---
nav sticky: Hace que la barra de navegacion se quede pegado