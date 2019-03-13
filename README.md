# Front-End Workshop (free of Frameworks...)

The idea of this workshop is to create the Front-End side starting from the graphic design that we supossely received from a Graphic designer. At this point of the development the UX Researchers and UX Designers have done their work, they have send their mockups to the Graphic Designer who had design the Look & Feel of the future website. And now, it's time for the Front-End developer to start coding the UI.

The process will start thinking in how to tuckle the project to make a Front-End architecture maintenable and an easy way to componetize the UI so we can modify it easily for future improvements. At the end, we are going to communicate our Front-End with a REST API that it's going to bring us all the data that we will need.

## Agenda
  - Day 1:
  - Day 2:
  - Day 3:
  
## Concepts
  - Responsive vs Adaptive design
  - Mobile-First vs Desktop-First
  - Thinking in Components
  
### Responsive vs Adaptive design
**Responsive:** djkañls dkañl sd

**Adaptive:** añlsdkañl sdkañl sd

https://www.interaction-design.org/literature/article/adaptive-vs-responsive-design 

### Mobile-First vs Desktop-First

https://searchenginewatch.com/2019/03/01/why-mobile-first-design-is-the-only-2019-strategy-that-will-work/
https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Responsive/Mobile_first
https://mayvendev.com/blog/mobilefirst

### Thinking in Components

We will divide the UI en components...

## Languages basics 
- HTML5 semantic
- CSS3 Basics
- Vanilla JavaScript

### HTML5
  - [Root element](#root-element)
  - [Metadata](#metadata)
  - [Scripting](#scripting)
  - [Sections](#sections)
  - [Grouping content](#grouping-content)
  - [Text](#text)
  - [Document edition](#document-edition)
  - [Embedded content](#embedded-content)
  - [Tabular data](#tabular-data)
  - [Forms](#forms)
  - [Interactive elements](#interactive-elements)
  
#### Root element
- **\<html\>:** Representa la raíz de un documento HTML o XHTML. Todos los demás elementos deben ser descendientes de este elemento.
#### Metadata
- **\<head\>:** Representa una colección de metadatos acerca del documento, incluyendo enlaces a, o definiciones de, scripts y hojas de estilo.
- **\<title\>:** Define el título del documento, el cual se muestra en la barra de título del navegador o en las pestañas de página. Solamente puede contener texto y cualquier otra etiqueta contenida no será interpretada.
- **\<base\>:** Define la URL base para las URLs relativas en la página.
- **\<link\>:**  Usada para enlazar JavaScript y CSS externos con el documento HTML actual.
- **\<meta\>:**  Define los metadatos que no pueden ser definidos usando otro elemento HTML.
- **\<style\>:** Etiqueta de estilo usada para escribir CSS en línea.
#### Scripting
- **\<script\>:** Define ya sea un script interno o un enlace hacia un script externo. El lenguaje de programación es JavaScript
- **\<noscript\>:** Define una contenido alternativo a mostrar cuando el navegador no soporta scripting.
#### Sections
- **\<body\>:** Representa el contenido principal de un documento HTML. Solo hay un elemento - **\<body\>:**  en un documento.
- **\<address\>:** Define una sección que contiene información de contacto.
- **\<h1 - h6\>:** Los elemento de cabecera  implementan seis niveles de cabeceras de documentos; - **\<h1\>:**  es la de mayor y - **\<h6\>:**  es la de menor impotancia. Un elemento de cabecera describe brevemente el tema de la sección que introduce.
- **\<section\>:** Define una sección en un documento.
- **\<nav\>:** Define una sección que solamente contiene enlaces de navegación
- **\<article\>:** Define contenido autónomo que podría existir independientemente del resto del contenido.
- **\<aside\>:** Define algunos contenidos vagamente relacionados con el resto del contenido de la página. Si es removido, el contenido restante seguirá teniendo sentido
- **\<header\>:** Define la cabecera de una página o sección. Usualmente contiene un logotipo, el título del sitio Web y una tabla de navegación de contenidos.
- **\<footer\>:** Define el pie de una página o sección. Usualmente contiene un mensaje de derechos de autoría, algunos enlaces a información legal o direcciones para dar información de retroalimentación.
- **\<main\>:** Define el contenido principal o importante en el documento. Solamente existe un elemento - **\<main\>:**  en el documento.
#### Grouping content
- **\<p\>:** Define una parte que debe mostrarse como un párrafo.
- **\<hr\>:** Representa un quiebre temático entre parrafos de una sección o articulo o cualquier contenido.
- **\<pre\>:** Indica que su contenido esta preformateado y que este formato debe ser preservado.
- **\<blockquote\>:** Representa una contenido citado desde otra fuente.
- **\<ol\>:** Define una lista ordenada de artículos.
- **\<ul\>:** Define una lista de artículos sin orden.
- **\<li\>:** Define un artículo de una lista ennumerada.
- **\<dl\>:** Define una lista de definiciones, es decir, una lista de términos y sus definiciones asociadas.
- **\<dt\>:** Representa un término definido por el siguiente - **\<dd\>:** .
- **\<dd\>:** Representa la definición de los terminos listados antes que él.
- **\<div\>:** Representa un contenedor genérico sin ningún significado especial.
- **\<figure\>:** Representa una figura ilustrada como parte  del documento.
- **\<figcaption\>:** Representa la leyenda de una figura.
#### Text
- **\<a\>:** Representa un  hiperenlace , enlazando a otro recurso.
- **\<em\>:** Representa un texto  enfatizado , como un acento de intensidad.
- **\<strong\>:** Representa un texto especialmente  importante .
- **\<small\>:** Representa un  comentario aparte , es decir, textos como un descargo de responsabilidad o una nota de derechos de autoría, que no son esenciales para la comprensión del documento.
- **\<s\>:** Representa contenido que ya  no es exacto o relevante .
- **\<cite\>:** Representa el  título de una obra .
- **\<q\>:** Representa una  cita textual  inline.
- **\<dfn\>:** Representa un término cuya  definición  está contenida en su contenido ancestro más próximo.
- **\<abbr\>:** Representa una  abreviación  o un  acrónimo ; la expansión de la abreviatura puede ser representada por el atributo title.
- **\<code\>:** Representa un código de  ordenador .
- **\<var\>:** Representa a una variable, es decir, una expresión matemática o contexto de programación, un identificador que represente a una constante, un símbolo que identifica una cantidad física, un parámetro de una función o un marcador de posición en prosa .
- **\<samp\>:** Representa la salida de un programa o un ordenador.
- **\<kbd\>:** Representa la entrada de usuario o usuaria, por lo general desde un teclado, pero no necesariamente, este puede representar otras formas de entrada de usuario o usuaria, como comandos de voz transcritos.
- **\<sub - sup\>:** Representan un subíndice y un superíndice, respectivamente.
- **\<i\>:** Representa un texto en una voz o estado de ánimo alterno, o por lo menos de diferente calidad, como una designación taxonómica, un término técnico, una frase idiomática, un pensamiento o el nombre de un barco.
- **\<b\>:** Representa un texto hacia el cual se llama la atención para  propósitos utilitaros.  No confiere ninguna importancia adicional y no implica una voz alterna.
- **\<u\>:** Representa una anotación no textual sin-articular, como etiquetar un texto como mal escrito o etiquetar un nombre propio en texto en Chino.
- **\<bdo\>:** Representa la direccionalidad de sus descendientes con el fin de anular de forma explícita al algoritmo bidireccional Unicode.
- **\<span\>:** Representa texto sin un significado específico.  Este debe ser usado cuando ningún otro elemento semántico le confiere un significado adecuado, en cuyo caso, provendrá de atributos globales como class, lang, o dir.
- **\<br\>:** Representa un salto de línea.
- **\<data\>:** Asocia un equivalente legible por máquina a sus contenidos. (Este elemento está sólamente en la versión de la  WHATWG del estandar HTML, y no en la versión de la W3C de HTML5).
- **\<time\>:** Representa un valor de fecha y hora; el equivalente legible por máquina puede ser representado en el atributo datetime.
- **\<wbr\>:** Representa una oportunidad de salto de línea, es decir, un punto sugerido de envoltura donde el texto de múltiples líneas puede ser dividido para mejorar su legibilidad.- **\<mark\>:**       	HTML5 - Representa texto resaltado con propósitos de referencia, es decir por su relevancia en otro contexto.
- **\<ruby\>:** Representa contenidos a ser marcados con anotaciones ruby,  recorridos cortos de texto presentados junto al texto. Estos son utilizados con regularidad en conjunto a lenguajes de Asia del Este, donde las anotaciones actúan como una guía para la pronunciación, como el furigana Japonés.
- **\<rt\>:** Representa el  texto de una anotación ruby .
- **\<rp\>:** Representa los paréntesis alrededor de una anotación ruby, usada para mostrar la anotación de manera alterna por los navegadores que no soporten despliegue estandar para las anotaciones.
- **\<bdi\>:** Representa un texto que debe ser aislado de sus alrededores para el formateado bidireccional del texto.  Permite incrustar un fragmento de texto con una direccionalidad diferente o desconocida.
#### Document edition
- **\<ins\>:** Define una adición en el documento.
- **\<del\>:** Define una remoción del documento.
#### Embedded content
- **\<img\>:** Representa una imagen.
- **\<iframe\>:** Representa un contexto anidado de navegación, es decir, un documento HTML embebido.
- **\<embed\>:** Representa un punto de integración para una aplicación o contenido interactivo externo que por lo general no es HTML.
- **\<object\>:** Representa un recurso externo, que será tratado como una imagen, un sub-documento HTML o un recurso externo a ser procesado por un  plugin.
- **\<param\>:** Define parámetros para el uso por los plugins invocados por los elementos - **\<object\>:** .
- **\<video\>:** Representa un  video , y sus archivos de audio y capciones asociadas, con la interfaz necesaria para reproducirlos. 
- **\<audio\>:** Representa un sonido o stream de audio.
- **\<source\>:** Permite a autores o autoras especificar recursos multimedia alternativos para los elementos multimedia como  - **\<video\>:**  o - **\<audio\>:** .
- **\<track\>:**  Permite a autores o autoras especificar una pista de texto temporizado para elementos multimedia como - **\<video\>:**  o   - **\<audio\>:** .
- **\<canvas\>:** Representa un  área de mapa de bits  en el que se pueden utilizar scripts para renderizar gráficos como gráficas, gráficas de juegos o cualquier imagen visual al vuelo.
- **\<map\>:** En conjunto con - **\<area\>:** , define un mapa de imagen.
- **\<area\>:** En conjunto con  - **\<map\>:** , define un mapa de imagen.
- **\<svg\>:** Define una imagen vectorial embebida.
- **\<math\>:** Define una fórmula matemática.
#### Tabular data
- **\<table\>:** Representa datos con más de una dimensión.
- **\<caption\>:** Representa el título de una tabla.
- **\<colgroup\>:** Representa un conjunto de una o más columnas de una tabla.
- **\<col\>:** Representa una columna de una tabla.
- **\<tbody\>:** Representa el bloque de filas que describen los  datos contretos  de una tabla.
- **\<thead\>:** Representa el bloque de filas que describen las etiquetas de columna de una tabla.
- **\<tfoot\>:** Representa los bloques de filas que describen los  resúmenes de columna  de una tabla.
- **\<tr\>:** Representa una fila de celdas en una tabla.
- **\<td\>:** Representa una celda de datos en una tabla.
- **\<th\>:** Representa una celda encabezado en una tabla. 
#### Forms
- **\<form\>:** Representa un formulario, consistendo de controles que puede ser enviado a un servidor para procesamiento.
	- Atributos: autocomplete (on|off), novalidate, method, action
- **\<fieldset\>:** Representa un conjunto de controles.
- **\<legend\>:** Representa el título de un - **\<fieldset\>:** .
- **\<label\>:** Representa el título de un control de formulario.
- **\<input\>:** Representa un campo de datos escrito que permite al usuario o usuaria editar los datos.
	- Tipos de inputs: color, date, datetime, datetime-local, email, month, number, range, search, tel, time, url, week, password
	- Atributos: autocomplete, autofocus, form, formaction, formenctype, formmethod, formnovalidate, formtarget, height,
					 			width, list, min, max, multiple, pattern, placeholder, required, step
- **\<button\>:** Representa un  botón .
- **\<select\>:** Represents un control que permite la selección entre un conjunto de opciones.
- **\<datalist\>:** Representa un conjunto de opciones predefiniddas para otros controles.
- **\<optgroup\>:** Representa un conjunto de opciones, agrupadas lógicamente.
- **\<option\>:** Representa una opción en un elemento - **\<select\>:** , o una sugerencia de un elemento - **\<datalist\>:** .
- **\<textarea\>:** Representa un control de edición de texto multi-línea.
- **\<keygen\>:** Representa un control de par generador de llaves.
- **\<output\>:** Representa el resultado de un cálculo.
- **\<progress\>:** Representa el progreso de finalización de una tarea.
- **\<meter\>:** Representa la medida escalar (o el valor fraccionario) dentro de un rango conocido.
#### Interactive elements
- **\<details\>:** Representa un widget desde el que un usuario o usuaria puede obtener información o controles adicionales.
- **\<summary\>:** Representa un resumen, título o leyenda para un elemento  - **\<details\>:**  dado.
- **\<command\>:** Representa un comando que un usuario o usuaria puede invocar.
- **\<menu\>:** Representa una lista de comandos.
### CSS3
- [Selectors](#selectors)
    - [Child selectors](#child-selectors)
    - [Sibling selectors](#sibling-selectors)
    - [Attributes](#attributes)
    - [Pseudo-classes](#pseudo-classes)
    - [Text selector](#text-selector)
    - [Pseudo-elements](#pseudo-elements)
    - [Links](#links)
- [Browser prefixes](#browser-prefixes)
- [Box model](#box-model)
    - [Margin](#margin)
    - [Border](#border)
    - [Padding](#padding)
    - [Content](#content)
    - [Outline](#outline)
- [Dimensions](#dimensions)
- [Positioning](#positioning)
- [Visualization and visibility](#visualization-and-visibility)
- [Box styles](#box-styles)
    - [Background gradients](#background-gradients)
- [Flexbox](#flexbox)
- [Text styles](#text-styles)
- [Fonts](#fonts)
- [Borders](#borders)
- [Links](#links-1)
- [Media queries](#media-queries)
- [Exclusions](#exclusions)
- [Regions](#regions)
- [2D transformations](#2d-transformations)
- [3D transformations](#3d-transformations)
- [Transitions](#transitions)
- [Animations](#animations)
- [Importing stylesheets](#importing-stylesheets)
- [Cascade](#cascade)
- [Specificity](#specificity)

<!-- /TOC -->

#### Selectors
- **.class:** Busqueda por nombre de clase
- **#id:** Busqueda por identificador de elemento
- ***:** Selecciona todos los elementos
- **tag:** Busqueda por nombre de etiqueta (p.e: div, p, span,...)
- **tag,tag:** Busqueda de varios elementos separados por comas

##### Child selectors
- **elem1 elem2:** Selecciona los elementos 'elem2' que estan dentro de 'elem1'
- **elem1 > elem2:** Selecciona los elementos 'elem2' cuyo padre directo es 'elem1'
- **:first-child:** Selecciona todos los elementos que son el primer hijo
- **:first-of-type:** Selecciona los elementos que son el primero de su tipo dentro de su padre
- **:last-child:** Selecciona cada elemento que es el ultimo hijo de su padre
- **:last-of-type:** Selecciona cada elemento que es el ultimo de su tipo dentro de su padre
- **:nth-child(n):** Selecciona elementos hijos a partir de una formula de seleccion. (p.e: odd | even | number | an + b)
- **:nth-last-child(n):** Igual que el selector anterior pero empezando a contar desde el final
- **:nth-last-of-type(n):** Igual que el selector anterior pero contando solo elementos de un determinado tipo
- **:nth-of-type(n):** Selecciona aquellos elementos hijos que ocupan una determinada posicion 'n' y son del tipo indicado
- **:only-of-type:** Selecciona elementos que son el unico elemento hijo de un determinado tipo con respecto a su padre
- **:only-child:** Selecciona elementos de un determinado tipo que son el unico hijo de su padre

##### Sibling selectors
- **elem1 + elem2:** Selecciona todos los elementos 'elem2' que estan ubicados directamente despues del elemento 'elem1'
- **elem1 ~ elem2:** Selecciona los elementos 'elem2' que estan precedidos de 'elem1'

##### Attributes
- **[attr]:** Todos los elementos que tienen definido un determinado atributo
- **[attr=value]:** Todos los elementos cuyo atributo es igual a un determinado valor
- **[attr~=value]:** Todos los elementos cuyo atributo contiene un determinado valor
- **[attr|=value]:** Selecciona los elementos cuyo atributo empieza por un determinado valor y le sigue el final del valor o el caracter '-'
- **[attr^=value]:** Todos los elementos cuyo atributo comienza con un determinado valor
- **[attr$=value]:** Todos los elementos cuyo atributo termina con un determinado valor
- **[attr*=value]:** Todos los elementos cuyo atributo contiene un subtring con el valor definido

##### Pseudo-classes
- **:checked:** Selecciona los elementos marcados (p.e: input[type="check"]:checked)
- **:disabled:** Selecciona cada elemento deshabilitado
- **:empty:** Selecciona cada elemento que no tiene nodos hijos
- **:enabled:** Selecciona cada elemento que esta habilitado
- **:focus:** Selecciona los elementos que tienen el foco
- **:hover:** Selecciona elementos cuando el raton esta encima de ellos
- **:in-range:** Selecciona elementos cuando estan dentro de un rango especifico. A partir de atributos min y max en inputs
- **:invalid:** Selecciona los inputs que tienen un valor que no es valido
- **:lang(language):** Selecciona los elementos que tienen un atributo de lenguaje especifico
- **:not(selector):** Seleccion negativa de elementos, selecciona todos los que no cumplen un determinado selector
- **:optional:** Selecciona elementos input que no tienen el atributo 'required'
- **:out-of-range:** Selecciona elementos input cuyo valor de rango esta fuera del permitido por los atributos max y min
- **:read-only:** Selecciona elementos que tienen el atributo 'readonly'
- **:read-write:** Selecciona elementos que no tienen el atributo 'readonly'
- **:required:** Selecciona elementos que tienen el atributo 'required' especificado
- **:root:** Selecciona el elemento document raiz <html>
- **:target:** Selecciona el elemento cuyo id corresponde con un target de una etiqueta <a> al marcar como activa dicha etiqueta
- **:valid:** Selecciona todos los elementos input con un valor valido

##### Text selector
- **:first-letter:** Selecciona la primera letra de los elementos indicados
- **:first-line:** Selecciona la primera linea de los elementos indicados
- **::selection:** Selecciona la porcion de texto que el usuario esta seleccionando del documento

##### Pseudo-elements
- **:after:** Inserta contenido despues de cada elemento seleccionado
- **:before:** Inserta contenido antes de cada elemento seleccionado

##### Links
- **:link:** Selecciona todos los links que no han sido visitados
- **:active:** Selecciona todos los links activos ('<a>')
- **:visited:** Selecciona todos los links visitados

#### Browser prefixes
- **-ms-:** Internet Explorer
- **webkit-:** Google Chrome
- **moz-:** Mozilla Firefox
- **webkit-:** Safari
- **o- | -webkit-:** Opera

#### Box model
- **Ancho Total:** width + left padding + right padding + left border + right border + left margin + right margin
- **Alto Total:** height + top padding + bottom padding + top border + bottom border + top margin + bottom margin

##### Margin
Limpia el area en la parte exterior del borde. No se ve afectado por el 'background' y es completamente transparente
- **margin:** *(length | auto | initial | inherit)* Establece el margen del elemento
- **margin-(pos):** *(pos): top | left | right | bottom* Establece el margen del elemento para una determinada posicion
					
##### Border
El borde va alrededor del padding y del contenido. Hereda su color de la propiedad 'color' de la caja

##### Padding
Limpia el area en la parte alrededor del contenido. Se ve afectado por el 'background'
- **padding:** *(length | initial | inherit)* Establece el padding del elemento					
- **padding-(pos):** *(pos): top | left | right | bottom* Establece el padding del elemento para una determinada posicion
					
##### Content
Indica el contenido de la caja donde el texto e imagenes aparecen

##### Outline
- **outline:** *(outline-color outline-style outline-width|initial|inherit)* Establece una linea alrededor del elemento y fuera del borde. No es parte del elemento y no afecta al ancho y alto total					
- **outline-color:** *(invert | color | initial | inherit)* Establece el color de la linea exterior					
- **outline-style:** *(none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset | initial | inherit)* Establece el estilo de la linea exterior			
- **outline-width:** *(medium | thin | thick | length | initial | inheri)* Establece el ancho de la linea exterior
					
#### Dimensions
- **height:** Establece la altura del elemento en su contenido
- **max-height:** Establece el alto maximo del elemento
- **min-height:** Establece el alto minimo del elemento
- **width:** Establece el ancho del elemento en su contenido
- **max-width:** Establece el ancho maximo del elemento
- **min-width:** Establece el ancho minimo del elemento

#### Positioning
	
- **position:** 
	- static
		- Valor por defecto
		- No le afecta top, left, right, bottom
	- fixed
		- Relativo a la ventana del navegador
		- No se puede aunque se haga scroll
		- Se puede posicionar encima de otros elementos
	- relative
		- Relativo a su posicion normal
		- Se puede mover y solapar con otros elementos
		- El espacio reservado para el elemento es preservado en el flujo normal del documento
		- Posicionamiento a menudo usado como contenedor de otros elementos con posicionamiento absoluto
	- absolute
		- Se posiciona relativo al primer elemento padre que tiene una posicion distinta de static, sino en relacion al elemento html
		- Son eliminados del flujo normal del documento
		- El resto de elementos se comportan como si el elemento absoluto no existiera
		- Puede solapar otros elementos
- **z-index:**
		- Para controlar el solape de elementos que son sacados del flujo normal del documento (fixed y absolute)
		- Especifica el orden de solape de elementos como una pila
		- Puede tener valores positivos y negativos

- **top:** *(lenght | auto | % | inherit)* Establece el margen respecto del borde superior de un elemento posicionado					
- **bottom:** *(lenght | auto | % | inherit)* Establece el margen respecto del borde inferior de un elemento posicionado					
- **left:** *(lenght | auto | % | inherit)* Establece el margen respecto del borde izquierdo de un elemento posicionado					
- **right:** *(lenght | auto | % | inherit)* Establece el margen respecto del borde derecho de un elemento posicionado					
- **clip:** *(shape | auto | inherit)* Recorta un elemento con posicion absoluta					
- **cursor:** *(url | auto | crosshair | default | pointer | move | e-resize | ne-resize | nw-resize | n-resize | se-resize | sw-resize | s-resize | w-resize | text | wait | help)* Establece el tipo de cursor utilizado					
- **overflow:** *(auto | hidden | scroll | visible | inherit)* Especifica que ocurre si el contenido sobresale del elemento					

#### Visualization and visibility

- **visibility:** *(hidden | visible | collapse | initial | inherit)*
			- Esconde el elemento
			- Ocupa el mismo espacio que si fuera visible
- **display:**
	- none
		- Esconde el elemento
		- La pagina sera visualizada como si el elemento no existiera

	- block
		- Toma todo el ancho disponible
		- Tiene un salto de linea antes y despues del elemento
		- ej: h1, p, div
	- inline
		- Toma tanto ancho como el elemento necesite
		- No fuerza los saltos de linea
		- ej: span, a

	- Values: *inline | block | flex | inline-block | inline-flex | inline-table | list-item | run-in | table | table-caption | table-column-group | table-header-group | table-footer-group | table-row-group | table-cell | table-column | table-row | none | initial | inherit*

#### Box styles
	
- **background:** *(color position size repeat origin clip attachment image | initial | inherit)* Establece de una sola vez todas las propiedades del background.								
- **background-attachment:** *(scroll | fixed | local | initial | inherit)* Establece si la imagen de fondo esta fija o hace scroll con el resto de la imagen.
- **background-color:** *(color | transparent | initial | inherit)* Indica el color de la imagen de fondo de un elemento.
- **background-imagen:** *(url | none | initial | inherit)* Indica la imagen a establece como background en un elemento.
- **background-position:** *(value)* Establece el punto de inicio de una imagen de fondo.
- **background-repeat:** *(repeat | repeat-x | repeat-y | no-repeat | initial | inherit)* Indica como debe repetir la imagen a lo largo de todo el elemento.
- **background-clip:** *(border-box | padding-box | content-box | initial | inherit)* Establece el area sobre la que aplicara el color o la imagen de fondo.				
- **background-origin:** *(border-box | padding-box | content-box | initial | inherit)* Indica la posicion del fondo de imagen relativo al contenido de la caja.
- **background-size:** *(auto | length | cover | contain | intial | inherit)* Especifica el tamaño del fondo de imagen.
- **box-sizing:** *(content-box | border-box | initial | inherit)* Indica como debe tomar el ancho y alto del elemento, considerando los padding o margin, por defecto solo es contenido.
- **opacity:** Establece el nivel de transparencia, toma un valor entre 0.0 y 1.
- **filter:alpha(opacity=val):** Establece el nivel de transparencia para <=IE8, val toma un valor entre 0 y 100.

##### Background gradients

- **background:** linear-gradient(direction, color-stop1, color-stop2, ...)
						*(direction) : top | right | bottom | left | top right | top bottom (por defecto) | ..*
- **background:** linear-gradient(angle, color-stop1, color-stop2, ...)
						*(angle):* Para mas precision se establece un angulo en grados en sentido de las agujas del reloj
- **background:** repeating-linear-gradient(direction, color-stop1 pos, color-stop2 pos, ...)
						Repite el gradiente hasta alcanzar el tamaño total del elemento. *(pos):* Posicion final del color
- **background:** radial-gradient(center, shape size, start-color, ..., last-color)
						*(shape size):* closest-side | farthest-side | closest-corner | farthest-corner
- **background:** repeating-radial-gradient(center, shape size, start-color, ..., last-color)

#### Flexbox
	
- **display: box** Establece el modelo de caja flexible y aplica a todos sus hijos
- **box-flex:** Especifica si los elementos hijos de una caja deben ser flexibles o no y en cuanta proporcion
				*(value):* El valor indica la flexibilidad del hijo, p.e: un valor de 2 indica que es el doble de flexible que otro hijo
- **box-orient:** *(horizontal | vertical | inline-axis | block-axis | inherit)* Indica si los hijos de una caja flexible debe ser desplegados horizontal o verticalmente.
- **box-pack:** *(start | end | center | justify)* Especifica donde son ubicados los hijos de una caja flexible cuando esta es mas larga que el tamaño del hijo.
- **box-align:** *(start | end | center | baseline | stretch)* Especifica como se deben alinear verticalmente los hijos de una caja.
- **box-ordinal-group:** *(integer)* Indica el orden en que se deben mostrar los hijos de una caja.
- **box-direction:** *(normal | reverse | inherit)* Indica en que direccion debe ser desplegados los hijos de una caja.
- **column-count:** *(number | auto | initial | inherit)* Especifica el numero de columnas en las que se divide un elemento.
- **column-gap:** *(length | normal | initial | inherit)* Indica el espacio entre columnas.
- **column-rule:** *(column-rule-width column-rule-style column-rule-color | initial | inherit)* Establece todas las propiedades del separador de columnas a la vez.
- **column-rule-color:** *(color | initial | inherit)* Indica el color del separador entre columnas.
- **column-rule-style:** *(none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset | initial | inherit)* Indica el estilo del separador.
- **column-rule-width:** *(medium | thin | thick | length | initial | inherit)* Establece el ancho del separador de columnas.
- **column-span:** *(1 | all | initial | inherit)* Indica cuantas columnas debe ocupar un determinado elemento.
- **column-width:** *(auto | length | initial | inherit)* Establece el ancho de las columnas.
- **columns:** *(auto | column-width column-count | initial | inherit)* Permite establecer las propiedades de 'column-width' y 'column-count' a la vez.
						
#### Text styles

color 			: Establece el color del texto
					(HEX | RGB | colorName)
text-align 		: Establece el alineamiento horizontal del texto
					(center | right | left | justify)
text-decoration	: Añade o elimina decoraciones del texto, tales como subrayado, linea de tachado, etc
					(none | underline | overline | line-through | initial | inherit)
text-transform 	: Especifica mayusculas o minusculas en el texto
					(none | capitalize | uppercase | lowercase | initial | inherit)
text-indent 	: Indica la sangria de la primera linea del texto
					(length | initial | inherit)
direction 		: Indica la direccion de escritura
					(ltr | rtl | initial | inherit)
letter-spacing 	: Incrementa o decrementa el espacio entre caracteres
					(normal | length | initial | inherit)
line-height 	: Establece la altura de cada linea de texto
					(normal | number | length | initial | inherit)
text-shadow 	: Añade sombra al texto
					(h-shadow v-shadow blur color | none | initial | inherit)
unicode-bidi 	: Usado junto con direction para determinar si el texto debe ser sobreescrita para soportar otros lenguajes
					(normal | embed | bidi-override | intitial | inherit)
vertical-align 	: Establece el alineamiento vertical
					(baseline | length | sub | super | top | text-top | middle | bottom | text-bottom | initial | inherit)
white-space		: Especifica como son controlados los espacios en blanco dentro del texto
					(normal | nowrap | pre | pre-line | pre-wrap | initial | inherit)
word-spacing	: Incrementa o decrementa el espacio entre palabras del texto
					(normal | length | initial | inherit)
word-wrap 		: Permite forzar una palabra que excede el ancho partirse y saltar de linea
					(normal | break-word | initial | inherit)
text-justify 	: Cuando el texto tiene una alineacion 'justify' indica el modo de justificacion utilizado. Solo en IE
					(auto | inter-word | inter-ideograph | inter-cluster | distribute | kashida | trim | initial | inherit)
text-overflow	: Indica que deberia ocurrir si el texto sobresale de su contenedor (p.e: añadir puntos suspensivos)
					(clip | ellipsis | string | initial | inherit)
word-break 		: Especifica como debe realizar los saltos de linea entre palabras
					(normal | break-all | keep-all | initial | inherit)
#### Fonts

TIPOS DE FUENTES:

	Serif 		: Tiene pequeñas decoraciones al final de algunos caracteres (p.e: Times New Roman, Georgia,...)
	Sans-serif 	: Fuentes sin las decoraciones al final de las letras (p.e: Arial, Verdana, ...)
	Monospace	: Fuentes en que cada caracter ocupa el mismo ancho (p.e: Courier New, Lucida Console,...)

font 			: Permite establecer todas las propiedades de una fuente de una sola vez
font-family		: Especifica la familia de fuentes utilizada, si el nombre esta separado por espacios usar ""
font-size 		: Establece el tamaño de la fuente. Mejor establecerlo en 'em' y poner el body al font-size: 100% para mejores resultados
					(medium | xx-small | x-small | small | large | x-large | xx-large | smaller | larger | length | initial | inherit)
font-style 		: Especifica estilos de texto, tales como cursiva
					(normal | italic | oblique | initial | inherit)
font-variant 	: Indica si el texto se debe ver o no en mayusculas de trazo fino
					(normal | small-caps | initial | inherit)
font-weight 	: Establece el grosor del texto
					(normal | bold | bolder | lighter | number (100-900) | initial | inherit)
@font-face 		: Permite utilizar fuentes que no estan instaladas en el equipo cliente
					Tipos: TTF | OTF | WOFF | SVG | EOT
		font-family 	: Nombre de la fuente
		src 			: URL donde se encuentra el fichero de fuentes
		font-stretch 	: Define como de estirada debe mostrarse la fuente
		font-style  	: Indica si debe ser cursiva, oblicua o normal
		font-weight 	: Indica el grosor de la fuente
		unicode-range 	: Define el rango de caracteres unicode que la fuente soporta

#### Borders

border 						: Establece todas las propiadedes del borde de una sola vez
								(border-width border-style border-color | initial | inherit)
border-color 				: Establece el color de los cuatro bordes
								(color | transparent | initial | inherit)
border-style 				: Establece el estilo de los cuatro bordes
								(none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset | initial | inherit)
border-width 				: Establece el ancho de los cuatro bordes
								(medium | thin | thick | length | initial | inherit)
border-(pos)				: Establece todas las propiedades del borde segun (pos) de una sola vez
border-(pos)-color			: Establece el color del borde indicado en (pos)
border-(pos)-style 			: Establece el estilo del borde indicado en (pos)
border-(pos)-width 			: Establece el ancho del borde indicado en (pos)
								(pos): top | left | right | bottom
border-image 				: Especifica una imagen como borde
								(source slice width outset repeat | initial | inherit)
border-image-source			: Indica la ruta donde se encuentra la imagen
border-image-slice			: Indica cuanto espacio hacia dentro hay con respecto al borde de la imagen
								(number | % | fill | initial | inherit)
border-image-width			: Indica el ancho del borde con una imagen
								(number | % | auto | initial | inherit)
border-image-ouset			: Especifica cuando el borde de la imagen se extiende mas alla del borde de la caja
								(length | number | initial | inherit)
border-image-repeat			: Indica si la imagen se debe repetir, estirar, etc
								(stretch | repeat | round | initial | inherit)
border-radius				: Establece el radio de curvatura en las esquinas de la caja. Establece el borde en las cuatro esquinas
								(1-4 length | % / 1-4 length | % | initial | inherit)
border-(pos)-(side)-radius : Establece el radio de curvatura especifico para una esquina
								(pos): top | bottom
								(side): left | right
box-shadow					: Permite establecer una sombra a la caja
								(none | h-shadow v-shadow blur spread color | inset | initial | inherit)
#### Links

SELECTORES

	a:link 		: Cualquier link que todavia no ha sido visitado
	a:visited 	: Un link que el usuario ha visitado
	a:hover		: Un link cuando el usuario se posiciona encima de el
	a:active 	: Un link en el momento de pulsar en el

text-decoration : Mediante esta propiedad podemos eliminar el subrayado que tiene por defecto cada link

#### Media queries

OPERADORES LOGICOS

	and 	: Ejecutara la hoja de estilos si se cumplen como verdaderas todas las queries de la declaracion. P.e:
					@media (min-width: 700px) : Ancho mayor o igual a 700px
					@media (min-width: 700px) and (orientation: landscape) : Ancho >= a 700px y orientacion horizontal
					@media tv and (min-width: 700px) and (orientation: landscape) : Ademas de lo anterior visualizacion en TV
	or | ,	: Ejecutara la hoja de estilos si alguna queries es verdadera, separarlas por comas equivale al operador 'or'						
					@media (min-width: 700px), handheld and (orientation: landscape): Si la pantalla es >= a 700px o si esta en horizontal en un dispositivo pequeño
	not 	: Aplica a toda la query excepto a las queries que estan separadas por comas
					@media not all and (monochrome) == @media not (all and (monochrome))
					@media not screen and (color), print and (color) == @media (not (screen and (color))), print and (color)
	only 	: Sirve para prevenir que navegadores que no soportan queries con funciones apliquen los estilos asignados
					<link rel="stylesheet" media="only screen and (color)" href="Ejemplo.css" />

SINTAXIS

	Media Query 			: [[only | not]? <media_type> [ and <expression> ]*] | <expression> [ and <expression> ]*
	Lista Media Queries 	: <media_query> [, <media_query> ]*		
	<expression> 			: ( <media_feature> [: <value>]? )
	<media_type> 			: all | aural | braille | handheld | print | projection | screen | tty | tv | embossed
	<media_feature>	: width | min-width | max-width | height | min-height | max-height | device-width | min-device-width | max-device-width | device-height | 
					min-device-height | max-device-height | aspect-ratio | min-aspect-ratio | max-aspect-ratio | device-aspect-ratio | 
					min-device-aspect-ratio | max-device-aspect-ratio | color | min-color | max-color | color-index | min-color-index | 
					max-color-index | monochrome | min-monochrome | max-monochrome | resolution | min-resolution | max-resolution | scan | grid

TIPOS DE MEDIOS 

	all 			: Todos los dispositivos
	aural 			: Dispositivos de sonido y sintetizadores
	braille 		: Dispositivos tactiles de braile
	embossed 		: Usado en impresoras de braile
	handheld 		: Pequeños dispositivos y dispositivos de mano
	print 			: Usado en impresoras
	projection 		: Usado para proyectar presentaciones, como de diapositivas
	screen 			: Cualquier pantalla de ordenador
	tty 			: Dispositivos de rejilla tales como teletipos o terminales
	tv 				: Dispositivos de television


TIPOS DE CARACTERISTICAS

	color 			: Indica el numero de bits por cada color que soporta el dispositivo
	color-index 	: Indica el numero de colores que soporta un dispositivo (p.e: 256)
	aspect-ration	: Indica el aspecto de imagen, separado por el caracter '/ (p.e: 1/1)
	device-aspect-ratio : Aspecto de imagen del dispositivo de  (p.e: 16/9)
	device-height 	: Indica la altura del dispositivo de salida, es decir la totalidad de la pantalla/pagina y no del documento a mostrar
	device-width 	: Indica la anchura del dispositivo de salida
	grid 			: Determina cuando se trata de un dispositivo de cuadricula, como una terminal TTY o una pantalla de telefono. 1 en este caso, 0 en caso contrario
	height 			: Indica la altura del documento a mostrar
	monochrome 		: Indica el numero de bits por pixel en un dispositivo monocromatico, 0 si no es monocromatico
	orientation 	: Indica la orientacion del dispositivo de salida (landscape | portrait)
	resolution 		: Indica la resolucion del dispositivo, medida en dpi o dpcm
	scan 			: Indica el proceso de exploracion en televisores (p.e: progressive)
	width 			: Indica el ancho del documento a visualizar

#### Exclusions

(prefix)-wrap-flow 		: Establece un area de exclusion por la cual el elemento padre no podra ocupar
							(auto | both | start | end | minimum | maximum | clear)
(prefix)-wrap-through 	: Controla el efecto de las exclusiones
							(wrap | none

#### Regions

Permiten al texto fluir a traves de distintos elementos de la pagina

(prefix)-flow-into		: El contenido del elemento fluye a traves del resto de elementos definidos 'flow-from'
							(name) : Nombre como identificador del estilo
(prefix)-flow-from		: Los elementos con este estilo seran contenedores del texto definido con el elemento 'flow-into'
							(name) : Mismo nombres que hace referencia en el estilo 'flow-into
(prefix)-break-before	: Indica que el flujo del contenido debe terminar antes del elemento
							(auto | always | avoid | left | right | page | column | region | avoid-page | avoid-column | avoid-region)
(prefix)-break-after	: Indica que el flujo del contenido debe terminar despues del elemento
							(auto | always | avoid | left | right | page | column | region | avoid-page | avoid-column | avoid-region)
(prefix)-break-inside	: El flujo del contenido debe terminar dentro del elemento
							(auto | avoid | avoid-page | avoid-column | avoid-region)
(prefix)-region-fragment: Controla como se visualiza el contenido en la ultima region cuando esta sobresale del elemento
							(auto | break)

#### 2D transformations
	
transform: translate(x,y)
			- Mueve el elemento desde su posicion original a partir de los valores de izquierda (x) y top (y)
			- ej: -webkit-transform: translate(50px, 100px)

transform: rotate(Xdeg)
			- Rota el elemento Xdeg en el sentido de las agujas del reloj. Si es negativo rota en sentido contrario a las agujas del reloj
			- ej: -ms-transform: rotate(30deg)

transform: scale(x,y)
			- Incrementa o decrementa el tamaño del elemento, en ancho(x) y/o alto(y)
			- ej: -webkit-transform: scale(2, 4)

transform: skew(Xdeg,Ydeg)
			- Gira un elemento en x e y segun los grados indicados
			- ej: -o-transform: skew(30deg, 20deg)

transform: matrix(n,n,n,n,n,n)
			- Combina en una unica transformacion todos los metodos 2D de transformacion a partir de una matriz de seis valores

transform-origin: 
			- Cambia la posicion de un elemento al que se ha aplicado una transformacion

transform: matrix | translate | translateX | scale | scaleX | scaleY | rotate | skew | skewX | skewY

transform-origin: x y z | initial | inherit

#### 3D transformations
	
transform: rotateX(Xdeg)
			- Rota el elemento en el eje X

transform: rotateY(Ydeg)
			- Rota el elemento en el eje Y

transform-style: flat | preserve-3d | initial | inherit
			- Indica como elementos anidados son renderizados en el espacio 3D

perspective: lenght | none
			- Especifica la perspectiva de como los elementos 3D son visualizados

perspective-origin: x y | initial | inherit
			- Indica donde un elemento 3D es posicionado en su parte inferior

backface-visibility: visible | hidden | initial | inherit
			- Define si un elemento debe tener visible o no las caras traseras

transform: matrix3d | translate3d | translateX | translateY | translateZ | scale3d | scaleX | scaleY | scaleZ | rotate3d | rotateX | rotateY | rotateZ | perspective

#### Transitions

transition: property duration timing delay
			- Las transiciones dan efectos cambiando gradualmente de un estilo a otro
			- Se inicia cuando una propiedad Css especifica cambia de valor

transition-delay: time | initial | inherti
			- Especifica cuando la transicion debe comenzar

transition-duration: time | initial | inherit
			- Especifica cuantos segundos o milisegundos debe durar la transicion

transition-property: none | all | property | initial | inherit
			- Indica el nombre de la propiedad Css a la que aplicar el efecto

transition-timing-function: ease | linear | ease-in| ease-out | cubic-bezier(n,n,n,n) | initial | inherit
			- Especifica la curva de velocidad que tomara la transicion

#### Animations

animation: myAnimation delay direction duration iteration timing
			- Permite crear una animacion reemplazando animaciones Flash, imagenes animadas o animaciones con JavaScript
			- La animacion es creada dentro de @keyframes y cambiara gradualmente de un estilo a otro
			- La animacion en @keyframes se puede especificar con 'from'/'to' o mediante porcentajes
@-webkit-keyframes myAnimation
{
	from { css style }
	to { css style }
}
@-webkit-keyframes myAnimation
{
	0% { css style }
	50% { css style }
	100% { css style}
}

animation-delay: time | initial | inherit
			- Especifica cuando la animacion debe comenzar

animation-direction: normal | reverse | alternate | alternate-reverse | initial | inherit
			- Indica si la animacion debe ir o no al reverso o en ciclos alternos

animation-fill-mode: none | forwards | backwards | both | initial | inherit
			- Especifica que estilos seran aplicados al elemento cuando la animacion no esta ejecutandose, cuando ha terminado o cuando espera por un delay

animation-iteration-count: number | infinite | initial | inherit
			- Especifica el numero de veces que una animacion debe ser repetida

animation-name: name
			- Nombre de la animacion referente a @keyframes

animation-play-state: paused | running | initial | inherit
			- Especifica si la animacion esta ejecutandose o esta pausada

animation-timing-function: ease | linear | ease-in| ease-out | cubic-bezier(n,n,n,n) | initial | inherit
			- Indica la curva de velocidad de la animacion


#### Importing stylesheets

@import url 		: Importa una hoja de estilos desde un fichero externo
						@import 'styles.css' == @import url('styles.css')
@import url media 	: Permite especificar para que dispositivos se cargaran las hojas de estilos
						@import url('stylesPrinter.css') print
						@import url('stylesBig.css') projection, tv

#### Cascade

Las hojas de estilos pueden tener tres diferentes origenes

ORIGEN DE LA HOJA DE ESTILOS

	Author		: El autor del documento define los recursos con las hojas de estilos
	User 		: El usuario puede especificar diferentes estilos para un determinado documento
	User agent 	: Establece una hoja de estilos por defecto para presentar los elementos en el documento de acuerdo a unas determinadas expectativas

ORDEN DE IMPORTANCIA 

	1. user important
	2. author important
	3. author normal
	4. user normal
	5. user agent

#### Specificity

Cuando a un elemento le aplican distintas clases, se puede utilizar la siguiente regla para determinar que clase sera la que se aplique
Por orden de prioridad tienen:

	0. Propiedades de clase definidas con '!important'
	a. Clase definida por identificador
	b. Clase definida por nombre de clase
	c. Clase aplicada a etiquetas HTML

En el siguiente ejemplo se ve como aplicar la regla:

	#id1         {xxx} a=1 b=0 c=0 --> Valor = 100 (Mayor especificacion)
	UL UL LI.red {xxx} a=0 b=1 c=3 --> Valor = 013 
	LI.red       {xxx} a=0 b=1 c=1 --> Valor = 011 
	LI           {xxx} a=0 b=0 c=1 --> Valor = 001

A igual especificacion se aplica la clase que se ha definido en primer lugar

## SMACCS
- [Categorization](#categorization)
    - [Base](#base)
    - [Layout](#layout)
    - [Module](#module)
    - [States](#states)
    - [Themes](#themes)
- [Naming convention](#naming-convention)
    - [Layout](#layout-1)
    - [Module](#module-1)
    - [States](#states-1)
    - [Themes](#themes-1)
- [Depth of applicability](#depth-of-applicability)
- [Folder structure](#folder-structure)
- [Advises](#advises)
- [References](#references)

<!-- /TOC -->
#### Categorization
- Every style we write serves one of these purposes whether we are aware of it or not
- Isolating code allows for easy reuse, testing and debugging
- Categorizing reveals patterns, easier to identify when things break the pattern

##### Base
- Element selectors
- CSS Resets
- Normalize

We have to be careful when we choose base elements. Maybe at the beginning there is only one element of each but every project grows up quickly. Some of these elements are: button, table or input.

##### Layout
- Major containing elements
- Grid systems
- Grouping content
- Specify widths and margins

##### Module
- Contains content
- The majority of the site
- Each module is an interface that your users have to learn
- Each module is code that has to be written, delivered and maintained
- Isolate modules from each other
- Prevent styles from coming in or out
- Can contain sub-modules or sub-components
- Expands to fill layout
- Every module has to be testeable
- Include media queries with the modules they affect
- Sub-modules: they are module variations. p.e: btn, btn-default, btn-large, etc.
- Sub-components: they are the child elements of a module

##### States
- Changes the Look & Feel of a module or layout
- Like a module variation (sub-module) but indicate a JavaScript dependency
- States are !important
- Avoid a state affecting more than one module at a time

##### Themes
- Only for on-the-fly style changes
- Usually aren't needed

#### Naming convention
- Use classes over IDs to avoid specificity

##### Layout
Uses the *layout-* prefix to distinguish layouts between modules 

```css
.layout-header {}
.layout-sidebar {}
.layout-content {} 
```

##### Module
Uses the type of module as the name
```css
.tab {}
.listview {}
.btn {}
```
To define sub-modules the module name is added as a prefix 
```css
.btn {}
.btn-large {}
.btn-small {}
.btn-default {}
.btn-search {} 
```
Sub-components are defined in the same way we define sub-modules
```css
.modal {}
.modal-header {}
.modal-body {}
.modal-footer {}
```

##### States
- Uses the *is-* prefix to indicate JavaScript dependency or a toggleable style
- If the style is specific to a module must include the module name
```css
.btn {}
.btn-is-active {}
.btn-is-disabled {}
```

##### Themes
```css
.theme-header {}
.theme-border {}
.theme-background {}
```

#### Depth of applicability
- Use fewer selectors, preferably one
- Use child selector to limit depth

Instead of 
```css
#comments .comment .meta .authorname {}
#comments .comment .meta .commentnumber a {}
```
we should use 
```css
.comment-author {}
.comment-number > a {}
```

#### Folder structure
```
/base
    |_ base
    |_ fonts
    |_ icons
/dependencies
    |_ animations
    |_ colors
    |_ global
    |_ mixins
/layout
    |_ grid
    |_ layout
/module
    |_ module_1
    |_ module_2
    |_ ...
    |_ module_n
app
```

#### Advises
- Place everything in their own files: base.css, layout.css, grid.css, button.css, carousel.css, modal.css, ...
- Scripts are written for individual modules
- States are modified, not inline styles
- Avoid jQuery methods that add inline styles like .show() and .hide()
- Identify areas to refactor
- Code css for the system, not the page
- Smaller rule sets make it easier on the browser
- Separation of files allows members of the team to work on separate files

#### References

- [SMACSS Course Frontend Masters by Jonathan Snook](https://frontendmasters.com/courses/smacss/?u=83c5033cb7d4129b73f4255d154ceb45210e43e2)

## JavaScript
- [JavaScript Language Syntax](#javascript-language-syntax)
    - [Console](#console)
        - [Methods](#methods)
        - [Console Formating](#console-formating)
        - [Special characters](#special-characters)
- [User interaction](#user-interaction)
- [Strict Mode](#strict-mode)
- [Data Types](#data-types)
    - [Special values](#special-values)
    - [Natives](#natives)
    - [Negative zero](#negative-zero)
    - [Object.is](#objectis)
    - [typeof](#typeof)
- [Coercion](#coercion)
- [Numbers](#numbers)
    - [Properties](#properties)
    - [Methods](#methods-1)
- [Strings](#strings)
    - [Properties](#properties-1)
    - [Methods](#methods-2)
- [Objects](#objects)
    - [Creating an object](#creating-an-object)
    - [Deleting a property](#deleting-a-property)
    - [Properties](#properties-2)
    - [Methods](#methods-3)
    - [Object instance Properties](#object-instance-properties)
    - [Object instance Methods](#object-instance-methods)
- [Functions](#functions)
    - [Declaration](#declaration)
    - [Methods](#methods-4)
- [Arrays](#arrays)
    - [Creating an array](#creating-an-array)
    - [Deleting an element](#deleting-an-element)
    - [Properties](#properties-3)
    - [Methods](#methods-5)
    - [Array instance Methods](#array-instance-methods)
- [Math](#math)
- [Dates](#dates)
    - [Constructor](#constructor)
    - [Getters](#getters)
    - [Setters](#setters)
    - [Formatting](#formatting)

<!-- /TOC -->
#### Console
##### Methods
- **assert:** If the assertion is false the message is written to the console
```javascript
console.assert(condition, message)
```
- **log:** outputs a message to the console
```javascript
console.log(message);
```
- **info:** outpus an informational message to the console
```javascript
console.info(message);
```
- **warn:** outputs a warning message to the console
```javascript
console.warn(message);
```
- **error:** outputs an error message to the console
```javascript
console.error(message);
```
- **clear:** clears the console
```javascript
console.clear()
```
- **dir:** displays a list of the properties of a JavaScript object
```javascript
console.dir(HTML)
```
- **dirxml:** displays a tree of the descendants elements of the specified HTML element
```javascript
console.dirxml(HTML)
```
- **group/groupEnd:** creates a new group of messages in the console
```javascript
console.group([name]) | console.groupEnd()
```
- **groupCollapsed/groupEnd:** like console.group but the group is created collapsed
```javascript
console.groupCollapsed([name]) | console.groupEnd()
```
- **profile/profileEnd:** starts recording a performance profile
```javascript
console.profile([name]) | console.profileEnd([name])
```
- **table:** Display an object as a table in the console
```javascript
console.table([JSON], [column]);
```
- **time:** starts a timer to track how long an operation takes
```javascript
console.time([name]) | console.timeEnd([name]);
```
- **count:** logs the number of times that count() has been called
```javascript
console.count()
```
- **trace:** shows a track trace in the console
```javascript
console.trace()
```
##### Console Formating
- %s : String
- %d, %i: Number
- %f: Decimal
- %o: DOM
- %O: Object
- %c: CSS
```javascript
console.log("DOM: %o", document.body)
console.log("Object: %O", { name: 'name1', value: 1 });
console.log('%c Message with style!!', 'background: #2980B9; color: #ECF0F1; font-size: 4em;')
```
##### Special characters
- \t: Tabulator
- \': Single quotation mark
- \": Double quotation mark
- \\: \
- \n: Line break

### User interaction
- **alert:** displays an alert dialog with the content and a OK button
```javascript
alert([content]])
```
- **confirm:** a confirmation prompt asks the user to confirm an action
```javascript
var output = confirm([content])
```
- **prompt:** dialog with an input to let the user introduce some text
```javascript
var output = prompt([content])
```
### Strict Mode
- Remove some potential errors
- Execute faster than no strict mode
- Forbid sintax that probably would be define in future versions of the language
```javascript
'use strict';
```
### Data Types
- undefined
- number
- string
- boolean
- object
- symbol
##### Special values
- NaN        
- undefined (void)
- null
- Inifinity, -Inifinity
- 0, -0
##### Natives
Like subtypes of an object, inheritance from a function
- Number
- String
- Boolean
- Object
- Function
- Array
- RegExp
- Data
- Error
```javascript
typeof new String("foo")    // "object"
typeof String("foo")        // "string"

typeof new Number(37)       // "object"
typeof Number(37)           // "number"
Number("37") === 37         // true
new Number("37") === 37     // false

foo = new RegExp("a*b", "g")
foo = /a*b/g;     // better option than the dynamic one above

foo = new Date();
```
##### Negative zero
```javascript
var foo = 0 / -1;
foo === -0    // true
foo === 0     // true
0 === -0      // true
```
##### Object.is
```javascript
Object.is("foo", NaN)   // false
Object.is(NaN, NaN)     // true
Object.is(0, -0)        // false
Object.is(-0, -0)       // true
```
##### typeof
```javascript
typeof foo            // "undefined"
typeof "foo"          // "string"
typeof 12             // "number"
typeof { a: 12 }      // "object"
typeof true           // "boolean"
typeof function(){}   // "function": is not a primitive type, it's a subtype of object
typeof undefined      // "undefined"
typeof Infinity       // "number"
typeof NaN            // "number"
typeof null           // "object"
```
### Coercion
- **To String**: do not use in arrays, objects, functions, etc.
Using string coercion with arrays and objects
```javascript
[].toString()                 // ""
[1, 2, 3].toString()          // "1,2,3"
[null, undefined].toString()  // ","
[,,,].toString()              // ",,"    
{}.toString()                 // "[object Object]"
{ a: 2 }.toString()           // "[object Object]"
```
Explicit coercion
```javascript
var foo = 123;
var str = foo.toString();
var num = String(foo);
```
Implicit coercion
```javascript
var foo = 123;
var baz = foo + "";   // "123"
```
- **To Number**
Explicit coercion
```javascript
var foo = "123";
var num = Number(foo)
var num = +foo
```
Implicit coercion
```javascript
var foo = "123";
var baz = foo - 0;    // 123
var baz = foo / 1;    // 123
```
~ operator: ~N equal to -(N + 1)
```javascript
var foo = "foo";
if (~foo.indexOf("f")) {
  // do something
}
```
```javascript
Number("")          // 0
Number(" 009 ")     // 9
Number(".")         // NaN
Number("0xAF")      // 175
Number(false)       // 0
Number(true)        // 1
Number(null)        // 0
Number(undefined)   // NaN
```
- **To Boolean:** it's define the falsy values, if it's not a falsy value must be a truthy one
Explicit coercion
```javascript
var foo = "123";
var baz = Boolean(foo);
var baz = !!foo;
```
Implicit coercion
```javascript
var foo = "123";
if (foo) { }  //true
foo = 0;
if (foo) { }  // false
```
Logic operators used as coercion
```javascript
var a = "123";
var b = a || "456";
// Equivalent to
var b = a ? a : "456";
```
```javascript
var a = "123";
var b = a && "456";
// Equivalent to
var b = a ? "456" : a;
```
```javascript
// Falsy values
Boolean("")
Boolean(0)
Boolean(null)
Boolean(undefined)
Boolean(NaN)
Boolean(false)
```
### Numbers
```javascript
typeof 1
typeof 3.14
typeof NaN
typeof Inifinity
```
##### Properties
```javascript
Number.MAX_VALUE
Number.MIN_VALUE
Number.NEGATIVE_INFINITY
Number.POSITIVE_INFINITY
Number.NaN
```
##### Methods
- **toExponential:** returns a string representing the number in exponential notation
```javascript
num.toExponential([decimals])
```
- **toFixed:** formats a number using fixed-point notation
```javascript
num.toFixed([decimals])
```
- **toLocaleString:** returns a string with a language sensitive representation of the number
```javascript
num.toLocaleString([locale])
```
- **toPrecision:** returns a string representing the number to the specified precision
```javascript
num.toPrecision()
```
- **toString:** returns a string representing the number
```javascript
num.toString([base])
```
- **valueOf:** returns the wrapped primitive value of the number
```javascript
num.valueOf()
```
- **isNan:** determines whether a value is NaN or not
```javascript
Number.isNaN([number])
```
- **parseFloat:** parses a string and returns a floating point number
```javascript
Number.parseFloat([string])
```
- **parseInt:** parses a string and returns an integer of the specified base
```javascript
Number.parseInt([string], [base: 2|8|10|16])
```
- **isFinite:** determines whether the value is a finite value
```javascript
Number.isFinite()
```
- **isInteger:** determines if the value is integer
```javascript
Number.isInteger()
```
- **isSafeInteger:** determines if the value is a safe integer (can be exactly represented as an IEEE-754 and cannot be the result of rounding any other integer to fit the IEEE-754 representation)
```javascript
Number.isSafeInteger()
```
### Strings
##### Properties
- **length:** returns the length of the string
```javascript
str.length
```
##### Methods
- **fromCharCode:** returns a string created using unicode values
```javascript
str.fromCharCode([number, ...])
```
- **charAt/charCodeAt:** returns the character or their unicode value at the specified index
```javascript
str.charAt([index]) | str.charCodeAt([index])
```
- **concat:** returns a new string that combines the text of one or more strings
```javascript
str.concat([string, ...])
```
- **includes:** determines whether a string cam be found within another string
```javascript
str.include([string])
```
- **indexOf/lastIndexOf:** returns the index of the first ocurrence of the specified valued
```javascript
str.indexOf([string]) | str.lastIndexOf([string])
```
```javascript
// ~N === -(N+1)
if (~foo.indexOf("f")) { }
```
- **split:** splits a string into an array of strings by a separator string
```javascript
str.split([separator])
```
- **slice:** extracts a section of a string and returns a new string. Slice accepts negative values. *[toIndex] is not inclusive*
```javascript
str.slice([fromIndex], [toIndex])
```
- **substring:** returns a subset of a string between one index and another. Substring does not accept negative values *[toIndex] is not inclusive*
```javascript
str.substring([fromIndex], [toIndex])
```
- **substr:** returns the characters in a string beginning at the specified location through a number of characters
```javascript
str.substr([fromIndex], [length])
```
- **toLowerCase/toLocaleLowerCase:** returns the string converted to lower case or returns it according to any local specific
```javascript
str.toLowerCase() | str.toLocaleLowerCase()
```
- **toUpperCase/toLocalUpperCase:** returns the string converted to upper case or returns it according to any local specific
```javascript
str.toUpperCase() | str.toLocaleUpperCase()
```
- **localeCompare:** returns a number indicating whether a reference string comes before or after or is the same in sort order
```javascript
str.localeCompare([substring])
```
- **starsWith/endsWith:** determines whether a string begins/ends with the characters of another string
```javascript
str.starsWith(substr) | str.endsWith(substr)
```
- **trim/trimLeft/trimRight:** trims whitespace from the beginning and end, or left or right side, of the string
```javascript
str.trim() | str.trimLeft() | str.trimRight()
```
- **padEnd/padStart:** pad the current string from the end/start with a given string to create a new string
```javascript
str.padStart([string]) | str.padEnd([string])
```
- **match:** match a regular expression against a string
```javascript
str.match([regEx])
```
- **search:** executes a search for a match between a regular expression and the string
```javascript
str.search([regEx])
```
- **normalize:** returns the unicode normalization form of the string
```javascript
str.normalize([form: 'NFC' | 'NFD' | 'NFKC' | 'NFKD'])
```
- **repeat:** returns a string which contains the number of copies of the strings concatenated
```javascript
str.repeat([count])
```
- **replace:** returns a string with all matches of a pattern replaced by a replacement
```javascript
str.replace([regEx], [string])
```
### Objects
```javascript
typeof null
typeof ['a','b']
typeof new Date()
typeof {a: 1}
```
##### Creating an object
```javascript
var obj = {
  prop: value,
  method: function(){ }
}
```
##### Deleting a property
```javascript
delete obj.prop;
obj.prop = undefined;
```
##### Properties
- **prototype:** allows the addition of properties to all objects of type Object 
```javascript
Object.prototype
```
##### Methods
- **keys:** returns an array containing the names of all of the given object's own properties
```javascript
Object.keys(obj)
```
- **entries:** returns an array with the property pairs [key, value]
```javascript
Object.entries(obj)
```
- **defineProperty:** defines a new property on an object or modifies an existing property and returns the object
```javascript
Object.defineProperty(obj, prop, { enumerable: false, configurable: false, writable: flase, value: 'static'})
```
- **defineProperties:** defines new or modifies existing properties on an object
```javascript
Object.defineProperties(obj, { 'prop': { value: true, writable: true }})
```
- **getPrototypeOf:** returns the prototype of the specified object
```javascript
Object.getPrototypeOf(obj)
```
- **getOwnPropertyDescriptor:** returns a property descriptor for an own property
```javascript
Object.getOwnPropertyDescriptor(obj, 'prop')
```
- **getOwnPropertyNames:** returns an array of all properties
```javascript
Object.getOwnPropertyNames(obj)
```
- **seal/isSealed:** prevents other code from deleting properties of an object. isSealed determines if an object is sealed
```javascript
Object.seal(obj) | Object.isSealed(obj)
```
- **freeze/isFrozen:** other code can't delete or change any properties. isFrozen determines if the object is freeze
```javascript
Object.freeze(obj) | Object.isFrozen(obj)
```
- **isExtensible:** determines if extending an object is allowed
```javascript
Object.isExtensible(obj)
```
- **preventExtensions:** prevents any extensions of an object
```javascript
Object.preventExtensions(obj)
```
- **is:** Determines if two objects are identical
```javascript
Object.is(NaN, NaN)
```
##### Object instance Properties
- **constructor:** specifies the function that creates an object's prototype
```javascript
Object.prototype.constructor
```
- **__proto__:** points to the object which was used as prototype when the object was instantiated
```javascript
Object.prototype.__proto__
```
##### Object instance Methods
- **hasOwnProperty:** determines whether an object contains the specified property of the object and not inherited through the prototype
```javascript
obj.hasOwnProperty('prop')
```
- **propertyIsEnumerable:** determines if the enumerable attribute is set
```javascript
obj.propertyIsEnumerable('prop')
```
- **toString/toLocaleString:** strings representation of the object
```javascript
obj.toString() | obj.toLocaleString()
```
- **isPrototypeOf:** determines whether the specified object is in the prototype chain of the object
```javascript
obj.isPrototypeOf(obj)
```
- **valueOf:** returns the primitive value of the specified object
```javascript
obj.valueOf()
```
Note: The order is arbitrary and they aren't show in the order it was defined
```javascript
for (var i obj) { obj[i] }
```
### Functions

##### Declaration
**Function constructor VS Function declarator**
Function constructor do not create closures to their creation contexts; they always are created in the global scope.
They will only be able to access their own local variables and global ones, not the ones from the scope in which the Function constructor was called.
```javascript
function constructor (){ }
var declarator = function () { }
```
##### Methods
- **apply:** calls a function with a given this value and arguments provides as an array
```javascript
fn.prototype.apply(thisArg, [args, ...])
```
- **call:** calls a function with a given this value and arguments provided individually
```javascript
fn.prototype.call(thisArgs, args, ...)
```
- **bind:** creates a new function that has its this keyword set to the provided value
```javascript
fn.prototype.bind(thisArgs, args, ...)
```
- **isGenerator:** determines whether or not a function is a generator
```javascript
fn.prototype.isGenerator()
```
- **toSource:** returns a string representing the source code of the object
```javascript
fn.prototype.toSource()
```
### Arrays
##### Creating an array
```javascript
var array = []
var array = [1, 2, 3]
array[2] = 4
```
##### Deleting an element
```javascript
delete array[2];
array[2] = undefined
```
##### Properties
- **length:** sets or returns the number of elements in an array
```javascript
array.length
```
##### Methods
- **isArray:**  true if a variable is an array
```javascript
Array.isArray([obj])
```
- **from:** creates a new array instance from an array object
```javascript
Array.from([arr]);
```
##### Array instance Methods
```javascript
// Returns an string representing the array and its elements
myArray.toString()		
myArray.toLocaleString()

// Removes the first element from an array and returns that element
myArray.shift()			
myArray.unshift([elements])		// adds one or more element to the front of an array and returns the length of the array

myArray.pop()			// removes the last element from an array and returns that element
myArray.push([elements])		// adds one or more elements to the end of the array

myArray.splice(position, length, [elements])	// Removes or adds elements to an array. Returns the deleted elements.
myArray.slice([from], [to])		// returns a copy of a portion of the array into a new array. 

myArray.concat([array])		// returns a merged array from two or more arrays
myArray.join([string])		// joins all elements of an array into a stirng

myArray.indexOf([item])		// returns the first index of an element withing the array or -1 if none is found
myArray.lastIndexOf([item])

myArray.sort()			// sorts the elements of an array in place and returns the array
myArray.reverse()			// reverses an array in place
myArray.forEach(function(element, index, array))	// executes a function once for each element in the array
myArray.map(function(element)) 	// creates a new array with the results of calling a provided function on every element in this array
myArray.some(function(element, index, array))	// returns true if one element in the array satisfies the testing function
myArray.every(function(element, index, array)) 	// true if every element in this array satisfies the testing function
myArray.filter(function(element))		// creates a new array with the elements which the filtering function returns true
myArray.reduce(function(prev, actual, index, array))	// apply a function against an accumulator and each value of the array from left to right to reduce it to a single value
myArray.reduceRight(function(prev, actual, index, array))	// apply a function against an accumulator and each value of the array from right to left to reduce it to a single value
```

### Math
```javascript
Math.abs([number]) 	// Returns the absolute value of a number

Math.cos([number])	// Return the respective geometrical operation of a number
Math.acos([number])
Math.sin([number])
Math.asin([number])
Math.tan([number])
Math.atan([number])

Math.ceil([number])	// Returns the smallest integer greater than or equal to the number

Math.floor([number])

Math.sqrt([number])

Math.random() * (max - min) + min;

Math.round([number])

Math.min([number, ...])
Math.max([number, ...])

Math.trunc([number])
```
### Dates
##### Constructor
```javascript
new Date()
new Date(3600 * 24 * 1000)
new Date('January 1, 1982')
new Date([year], [month], [date], [hour], [minutes], [seconds], [milliseconds])
new Date(Date.UTC(2016, 1, 1))
```
##### Getters
```javascript
date.getFullYear() | date.getUTCFullYear()
date.getMonth() | date.getUTCMonth()
date.getDay() | date.getUTCDay()
date.getDate() | date.getUTCDate()
date.getHours() | date.getUTCHours()
date.getMinutes() | date.getUTCMinutes()
date.getSeconds() | date.getUTCSeconds()
date.getMilliseconds() | date.getUTCMilliseconds()
date.getTime()
date.getTimezoneOffset()
```
##### Setters
```javascript
date.setFullYear() | date.setUTCFullYear()
date.setMonth() | date.setUTCMonth()
date.setDate() | date.setUTCDate()
date.setHours() | date.setUTCHours()
date.setSeconds() | date.setUTCSeconds()
date.setMilliseconds() | date.setUTCMilliseconds()
date.setTime() 
```
##### Formatting
```javascript
date.toString()
date.toDateString()
date.toTimeString()
date.toISOString()
date.toUTCString()
date.toLocaleString('de-DE', { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' })
```
