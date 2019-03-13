# Front-End Workshop (free of Frameworks...)

The idea of this workshop is to create the Front-End side starting from the graphic design that we supossely received from a Graphic designer. At this point of the development the UX Researchers and UX Designers have done their work, they have send their mockups to the Graphic Designer who had design the Look & Feel of the future website. And now, it's time for the Front-End developer to start coding the UI.

The process will start thinking in how to tuckle the project to make a Front-End architecture maintenable and an easy way to componetize the UI so we can modify it easily for future improvements. At the end, we are going to communicate our Front-End with a REST API that it's going to bring us all the data that we will need.

## Agenda
  - Day 1:
  - Day 2:
  - Day 3:
  
## Concepts
  - Thinking in Components
  - Responsive vs Adaptive design
  - Mobile-First vs Desktop-First
  
### Responsive vs Adaptive design
**Responsive:** djkañls dkañl sd

**Adaptive:** añlsdkañl sdkañl sd

https://www.interaction-design.org/literature/article/adaptive-vs-responsive-design 

### Mobile-First vs Desktop-First

https://searchenginewatch.com/2019/03/01/why-mobile-first-design-is-the-only-2019-strategy-that-will-work/
https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Responsive/Mobile_first
https://mayvendev.com/blog/mobilefirst

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
