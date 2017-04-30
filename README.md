# Lecturas Curso de HTML5 + CSS3 + jQuery


<a id="sublime-text"></a>
### Descargar Sublime Text

Antes de comenzar a probar código necesitamos descargar nuestro editor de texto Sublime Text.

[Ingresa a este enlace](https://www.sublimetext.com/3) y descarga la versión según el sistema operativo que uses

# HTML5
  - [Introducción](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#introduccion)
  - [Etiquetas](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas)
    * [Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas-sintaxis)
    * [Atributos](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas-atributos)
    * [Etiquetas: Texto](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas-texto)
    * [Etiquetas: Listas](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas-listas)
    * [Etiquetas: Hipervínculos](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas-hipervinculos)
    * [Etiquetas: Imágenes](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas-imagenes)

# CSS3
- [Introducción](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#intro-css)
- [Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-sintaxis)
- [Herencia](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-sintaxis)
- [Especificación](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-sintaxis)

# JavaScript
  - [Introducción](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#intro-js)
  - [Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-sintaxis)
  - [Elementos de la Programación](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-sintaxis)
    * [Variables](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-variables)
    * [Condicionales](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-condicionales)
    * [Ciclos](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-ciclos)
    * [Funciones](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-funciones)
    * [Objetos](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-objetos)
  - [El DOM (Document Objet Model)](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-sintaxis)

  # jQuery
  - [Introducción](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#intro-js)
  - [Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-sintaxis)

<a href="#" id="introduccion"></a>
# Introducción

Un sitio web es, en escencia, un documento de texto que es interpretado por nuestro navegador de internet. HTML es un conjunto de etiquetas que nos ayudan a estructurar el contenido que queremos presentar. 

Por esta razón, la extensión de nuestro archivo es `html`

<a href="#" id="etiquetas"></a>
# Etiquetas HTML5

De la misma forma en que Word tiene un formato visual distinto para sus títulos, párrafos, listas, etc, HTML utiliza etiquetas que determinan el tipo de contenido que se busca mostrar en nuestras pantallas.

## Como vemos un documento de texto en Word

![Estructura](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/html-lecturas-1.png)

## Como vemos un documento de texto en un navegador con HTML

![Estructura](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/html-lecturas-2.png)

<strong>Conclusión:</strong> La estructura de un sitio web utiliza los mismos principios de un documento de texto usando etiquetas para especificar el tipo de información que se quiere mostrar en el navegador

<a href="#" id="etiquetas-sintaxis"></a>
## Sintaxis de etiquetas

La gran mayoria de las etiquetas HTML consiste en una de apertura y otra de cierre. De esta manera, lo que va en el medio es el contenido que queremos mostrar en la pantalla. 

![Etiquetas Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/html-etiquetas-sintaxis.png)

Sin embargo, existen etiquetas que que pueden ser sólo de apertura. Esto ocurre debido a que la información que contienen es cargada a través de atributos.

<a href="#" id="etiquetas-atributos"></a>
## Atributos

Los atributos son instrucciones e información adicional que podemos darle a las etiquetas HTML para agregarle funcionalidad. Cada etiqueta soporta diferentes tipos de atributos, así como hay atributos que pueden ser usados para cualquier tipo de etiqueta.

Por ejemplo, la etiqueta `<html>` soporta el atributo `lang` el cual indica al navegador el idioma en que nuestro sitio está escrito.

![Atributos Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/html-atributo-sintaxis.png)


## Mi primer sitio web

Sigue los siguientes pasos para crear tu primer sitio web:
  1. Abre Sublime Text ( si aún no lo tienes instalado <a href="#sublime-text">ve al comienzo</a> de las lecturas )
  2. Usando el atajo de `control + t` / `cmd + t` abre un nuevo tab y escribe `index.html` 
  3. Usando el atajo `control + s` / `cmd + s` guarda tu archivo en una carpeta con el nombre `mi-primer-sitio`. 

Nota: Sigue estos pasos en el siguiente video:

![Mi primer sitio](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/mi-primer-sitio.gif)

Luego de que ya tenemos nuestro archivo `index.html` necesitamos incluir una etiqueta que le haga saber al navegador que vamos a usar HTML5.

### `<DOCTYPE html!>` 

Esta etiqueta, que va al inicio de nuestro `index.html`, le indica al navegador que el documento debe procesarse según la codificación HTML5.

Lo siguiente que necesitamos agregar es `<html></html>`. Dentro de esta etiqueta irá la información que le daremos al navegador y lo que queremos que se vea en nuestra pantalla.

### Información al navegador
Dentro de la etiqueta `<head></head>` es donde irá toda la información interna que necesita el navegador. Por ejemplo, dado que a veces el contenido de nuestro sitio puede estar en español, necesitamos que el navegador acepte caracteres especiales como tildes o la letra `ñ`.

Para eso tenemos la etiqueta `<meta>` con atributo `charset="utf-8"`. El `utf-8`.

Otro ejemplo muy usado de información para el navegador es la posibilidad de dar un título a nuestro sitio con la etiqueta `title`

Sigue los pasos para agregar estas etiquetas en el ejemplo de abajo

![Doctype, head and title](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/doctype-head-title.gif)


### Información al usuario / pantalla
Dentro de la etiqueta `<body></body>` es donde colocaremos todo el contenido que deseamos mostrar en la pantalla y los usuarios.s

<a href="#etiquetas-texto"></a>
# Etiquetas: Texto

Como ya se ha mencionado, un sitio web consiste en un documento de texto el cual está estructurado con etiquetas. Estas etiquetas le dan un mayor significado al contenido que queremos presentar en el navegador. 

Existen etiquetas que ayudan a estructurar los contenidos que forman parte de los encabezados de nuestro sitio, así como sus párrafos. 

<a href="#etiquetas-listas"></a>
# Etiquetas: Listas

Las listas funcionan para que nosotros podamos agrupar conjuntos de elementos por ejemplo para un menú de navegación.

Existen 3 tipos de listas que podemos presentar con HTML: Ordenadas, Desordenadas y de Definición.

## Listas Ordenadas

Las listas ordenadas están conformadas por un conjunto de elementos con un orden o una secuencia. Funcionan de la misma forma que una lista ordenada. 

Para crear una lista ordenada utilizamos la etiqueta `<ol>` para encerrar nuestros elementos y la etiqueta `<li>` por cada elemento de la lista.

  

## Listas Desordenadas

Las listas no ordenadas son de los elementos que más se usan para la construcción de un sitio web. Está conformada por un conjunto de elementos que no requieren de un orden o una secuencia específica.

Para generar una lista desordenada primero necesitamos de la etiqueta `<ul>` quien es la que encierra los elementos que son parte de la lista y la etiqeuta `<li>` para cada elemento.


<a href="#etiquetas-hipervinculos"></a>
# Etiquetas: Enlaces (Links)

Los enlaces son uno de los componentes más importantes en un sitio web, ya que le permiten al usuario navegar a través de todo internet y también por nuestro sitio.

Existen alrededor de 5 tipos diferentes de enlaces.

  - Enlaces de un sitio web a otro.
  - Enlaces de una página a otra en el mismo sitio web.
  - Enlaces desde una parte de una página web a otra parte del
misma página.
  - Enlaces que se abren en una nueva ventana del navegador.
  - Enlaces que inician su programa de correo electrónico y abordan un nuevo correo electrónico a alguien. 

<a href="#etiquetas-imagenes"></a>
# Etiquetas: Imagenes

Las imágenes son un elemento más dentro de un sitio web y nosotros podemos cargar imágenes desde HTML utilizando la etiqueta `<img>`. Esta etiqueta sólo contiene una etiqueta de apertura debido a que la imagen que se quiere cargar, se hará desde el atributo `src` en donde se colocará como valor la ruta de la imagen que querramos mostrar en la pantalla.

## Ejemplo 
