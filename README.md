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
    * [Etiquetas: HTML5](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#etiquetas-html5)
 - [Formularios](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#formularios)
 - [Tablas](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#tablas)

# CSS3
- [Introducción](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#intro-css)
- [Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-sintaxis)
- [Selectores](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-selectores)
- [CSS: Color](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-color)
- [CSS: Texto](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-texto)
- [CSS: Cajas](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-cajas)
- [Distribución de Elementos](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-elementos-distribucion)
  * [Elementos Flotantes](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-elementos-flotantes)
  * [Posicionamiento](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-posicionamiento)
- [La Cascada](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-cascada)
- [Herencia](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-herencia)
- [Especificación](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#css-especificacion)

# JavaScript
  - [Introducción](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#intro-js)
  - [Sintaxis](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-sintaxis)
  - [Elementos de la Programación](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#e-variables)
    * [Variables](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-variables)
    * [Condicionales](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-condicionales)
    * [Ciclos](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-ciclos)
    * [Funciones](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-funciones)
    * [Objetos](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-objetos)
  - [El DOM (Document Objet Model)](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/README.md#js-dom)

<a href="#" id="introduccion"></a>
# Introducción

Un sitio web es, en escencia, un documento de texto que es interpretado por nuestro navegador de internet. HTML es un conjunto de etiquetas que nos ayudan a estructurar el contenido que queremos presentar. 

Por esta razón, la extensión de nuestro archivo es `html`

<a href="#" id="etiquetas"></a>
# Etiquetas 

De la misma forma en que Word tiene un formato visual distinto para sus títulos, párrafos, listas, etc, HTML utiliza etiquetas que determinan el tipo de contenido que se busca mostrar en nuestras pantallas.

## ¿Cómo vemos un documento de texto en Word?

![Estructura](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/html-lecturas-1.png)

## ¿Cómo vemos un documento de texto en un navegador con HTML?

![Estructura](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/html-lecturas-2.png)

<strong>Conclusión:</strong> La estructura de un sitio web utiliza los mismos principios de un documento de texto usando etiquetas para especificar el tipo de información que se quiere mostrar en el navegador

<a href="#" id="etiquetas-sintaxis"></a>
## Sintaxis de etiquetas

La gran mayoría de las etiquetas HTML consiste en una de apertura y otra de cierre. De esta manera, lo que va en el medio es el contenido que queremos mostrar en la pantalla. 

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
Dentro de la etiqueta `<body></body>` es donde colocaremos todo el contenido que deseamos mostrar en la pantalla y los usuarios.

![Estructura Final Primer Sitio Web](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/estructura-final-sitioweb.png)

<a href="#etiquetas-texto"></a>
# Etiquetas: Texto

Como ya se ha mencionado, un sitio web consiste en un documento de texto el cual está estructurado con etiquetas. Estas etiquetas le dan un mayor significado al contenido que queremos presentar en el navegador. 

Existen etiquetas que ayudan a estructurar los contenidos que forman parte de los encabezados de nuestro sitio, así como sus párrafos. 

### Párrafos

Para que el navegador reconozca el texto como un párrafo, debemos usar la etiqueta `<p></p>`

![Parrafos HTML](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/parrafos-html.png)

### Encabezados

En la gran mayoría de los sitios web, existen diferentes secciones que delimitan la jerarquía del contenido que llevan. Usualmente estas secciones se delimitan gracias a los títulos que llevan. 

Las etiquetas que definen los títulos son `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` y `<h6>` en donde la etiqueta `<h1>` determina un título de mayor importancia y la etiqueta `<h6>` determida un título con la menor importancia.

![Encabezado HTML](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/titulos.png)

### Strong y Enfásis

Si queremos hacer que parte de nuestro texto sea en negrita o en cursiva con HTML, las etiquetas a usar son `<strong>` y `<em>`

![Encabezado HTML](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/strong-em.png)

### Citación

Cuando queremos que el navegador reconozca una parte de nuestro texto como una cita utilizamos la etiqueta `<blockquote>`. Esta etiqueta trabaja como contenedor de la cita, la cual puede ser un párrafo (`<p>`) o un texto encerrado en la etiqueta `<cite>`

El navegador tiende a indentar el texto que se encuentra dentro de la etiqueta. Abajo podemos ver la diferencia usando un `<p>` y un `<cite>`.

![Citacion HTML](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/citacion.png)

<a href="#etiquetas-listas"></a>
# Etiquetas: Listas

Las listas funcionan para que nosotros podamos agrupar conjuntos de elementos por ejemplo para un menú de navegación.

Existen 3 tipos de listas que podemos presentar con HTML: Ordenadas, Desordenadas y de Definición.

### Listas Ordenadas

Las listas ordenadas están conformadas por un conjunto de elementos con un orden o una secuencia. Funcionan de la misma forma que una lista ordenada. 

Para crear una lista ordenada utilizamos la etiqueta `<ol>` para encerrar nuestros elementos y la etiqueta `<li>` por cada elemento de la lista.

![Listas Ordenadas HTML](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/listas-ordenadas.png)

### Listas Desordenadas

Las listas no ordenadas son de los elementos que más se usan para la construcción de un sitio web. Está conformada por un conjunto de elementos que no requieren de un orden o una secuencia específica.

Para generar una lista desordenada primero necesitamos de la etiqueta `<ul>` quien es la que encierra los elementos que son parte de la lista y la etiqeuta `<li>` para cada elemento.

![Listas Desordenadas HTML](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/listas-desordenadas.png)


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

  ### ¿Cómo escribir un enlace?

  Los enlaces se crean usando la etiqueta `<a>` en donde los usuarios pueden clickear a lo que se encuentre entre la etiqueta de apertura y de cierre. 

  Utilizando el atributo `href` podemos determinar la ruta de la página o sitio a donde queremos que el usuario vaya.

  ![Enlace](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/enlace-sintaxis.png)

<a href="#etiquetas-imagenes"></a>
# Etiquetas: Imágenes

Las imágenes son un elemento más dentro de un sitio web y nosotros podemos cargar imágenes desde HTML utilizando la etiqueta `<img>`. Esta etiqueta sólo contiene una etiqueta de apertura debido a que la imagen que se quiere cargar, se hará desde el atributo `src` en donde se colocará como valor la ruta de la imagen que querramos mostrar en la pantalla.

Como vemos en el ejemplo de abajo, hemos colocado otro atributo `width` que nos ayudará a manejar el ancho de nuestra imagen y como valor le hemos dado `530`

![Imagenes](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/imagenes.png)

<a href="#etiquetas-html5"></a>
# Etiquetas: HTML5

Si bien sabemos que podemos usar la etiqueta `<div>` para agrugar elementos que pertenecen a diferentes secciones de los sitios que construimos, HTML5 nos da etiquetas que son más semánticas. 

Esto quiere decir que estas etiquetan ayudan a que el navegador pueda tener un entendimiento más claro de las secciones de nuestro sitio. Por ejemplo, si quisieramos determinar el encabezado principal de un sitio, en lugar de agruparlo así:

```
<div id="header">
  <h1>Logo</h1>
</div>
``` 

Podríamos agruparlo así:

```
<header>
  <h1>Logo</h1>
</header>
``` 

De la última forma hacemos que la sección, que es importante, tenga un mayor significado.

A continuación te mostramos una lista de etiquetas HTML5 y en que tipo de secciones podemos utilizarlas

| Etiqueta            | Significado                           | 
| --------------------|:-------------------------------------:| 
| `<header></header>` | Aplica para los encabezados del sitio |
| `<footer></footer>` | Aplica para los pies de página del sitio |
| `<aside></aside>` | Aplica para las secciones secundarias del sitio |
| `<article></article>` | Aplica para los bloques de noticias o post de un blog de tu sitio |
| `<section></section>` | Aplica para las secciones importantes del sitio | 

<a href="#formularios"></a>
# Formularios

Los formularios son una de las partes más importantes de un sitio web ya que es la manera en como nosotros podemos obtener información de sobre nuestros usuarios y de igual manera, como los usuarios pueden ponerse en contacto con nosotros.

El diseño de un formulario consiste en un conjunto de campos de texto de diferentes tipos y un botón que nos servirá para que la información que ingrese el usuario sea enviada y guardada.

Para definir un formulario necesitamos de la etiqueta `<form>`, dentro de esta etiqueta nosotros vamos a definir los campos de texto y boton/botones usando la etiqueta `<input>`

Veamos el siguiente ejemplo:

![Formulario I](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/formularios-1.gif)

Como podemos ver en la imagen de arriba, con la etiqueta `input` podemos definir un campo y el atributo `type` nos ayuda a definir que tipo de campo queremos. Por defecto el valor del atributo es `text`.

## Contraseña 

Si queremos crear un campo para que nuestro usuario coloque su contraseña tenemos que cambiar el valor de `type` a `password`

![Formulario II](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/formularios-2.gif)

## Correo Electrónico 

Si queremos crear un campo para que nuestro usuario coloque su correo electrónico tenemos que cambiar el valor de `type` a `email`

![Formulario III](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/formularios-3.gif)

## Labels y Placeholder

Como podemos ver en los ejemplos pasados, la etiqueta `<input>` nos ayuda a generar campos de texto de diferentes tipos para que el usuario pueda colocar su información. Sin embargo, los campos por si solos no ayudan a un usuario diferenciar entre ellos. 

Para estos casos, necesitamos de la etiqueta `<label>` y el atributo `placeholder`. La etiqueta `<label>` nos ayuda a relacionar el nombre con el campo que corresponde y el atributo `placeholder` nos ayuda a dejar un pequeño mensaje dentro del campo para asegurarnos de que el usuario coloque su información en el campo correcto.

### Ejemplo de uso `<label>`

![Formulario IV](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/formulario-4.gif)

### Ejemplo de uso `placeholder`

![Formulario V](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/formularios-5.gif)

<a href="#tablas"></a>
# Tablas

Las tablas son elementos que nos ayudan a organizar textos, imagenes, hipervínculos dentro de filas, columnas y celdas.

La etiqueta para definir una tabla es `<table>`. 

![Tablas I](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/tablas-1.gif)

Dentro de ella necesitamos definir una fila con la etiqueta `<tr>`, la cual llevará dentro el número de celdas que necesitemos.

![Tablas II](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/tablas-2.gif)

Para definir las celdas podemos usar la etiqueta `<td>`. 

![Tablas III](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/tablas-3.gif)

Si queremos definir celdas como encabezados podemos usar la etiqueta `<th>` 

![Tablas IV](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/HTML5/tablas-4.gif)

<a href="#" id="intro-css"></a>
# CSS: Introducción

CSS es un lenguaje que trabaja con hojas de estilos, hecho para encargarse de hacer un sitio web más atractivo. El lenguaje nos permite crear reglas que pueden especificar colores, espacios, distribución, animación, 3D, transiciones, etc.

La clave para entender como funciona CSS es recordar que existe una caja invisible alrededor de todos y cada uno de los elementos HTML.

![CSS 1](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-1.png)

<a href="#" id="css-sintaxis"></a>
# CSS: Sintaxis

CSS funciona asociando reglas con elementos HTML. Estas reglas son las que definen como se debe de mostrar el contenido de las etiquetas HTML especificadas. Las reglas CSS están estructuradas en dos partes: un selector y una declaración.

![CSS 2](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-2.png)

Los selectores indican el elemento al cual la regla CSS será aplicada. La misma regla puede aplicarse a más de un elemento si separamos los nombres de los elementos con comas.

Las declaraciones indican como deben de verse los elementos que han sido seleccionados. Las declaraciones CSS se sitúan entre corchetes y cada una se compone de dos partes: propiedad y valor. Estas dos partes son separadas por dos puntos.

Podemos especficicar multiples propiedades en una sóla declaración, cada una separada por un punto y coma.

![CSS 3](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-3.png)

Las propiedades indican que es lo que queremos cambiar del elemento. Por ejemplo, color, fuente, ancho, altura, border, etc.

Los valores especifican la configuración que se busca utilizar para la propiedad. Por ejemplo, si queremos usar la propiedad color entonces el valor es el color que queremos que sea el texto del elemento.

## Conectar el CSS con el HTML

Existen dos maneras de conectar el CSS con nuestro archivo HTML: Usando un archivo externo y creando el CSS directamente en el HTML.

### Usando CSS externo dentro del HTML

Podemos incluir nuestro estilos directamente en nuestro archivo `html` utilizando la etiqueta `<style>` dentro del elemento `<head>`. Esta etiqueta necesita el atributo `type` para indicar que los estilos colocados son CSS. El valor del atributo debe de ser `text/css`.

![CSS 4](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-4.gif)

### Usando un archivo CSS externo

Si queremos utilizar un archivo externo para escribir nuestro estilos, debemos crear un archivo con extensión `.css`.
Lo siguiente que debemos hacer es conectar este archivo con nuestro `index.html` con la etiqueta `<link>`. Esta etiqueta necesita de dos atributos: `href` para determinar la ruta en donde se encuentra el archivo y `rel` para especificar que tipo de archivo que estamos enlazando.

![CSS 5](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-5.gif)

A pesar de que puede parecer más sencillo colocar tus estilos de forma interna, la mejor práctica es separar tus estilos de tu archivo `html` debido a que en el proceso de construir tu sitio web tu CSS puede llegar a ser muy grande y muy facilmente puede convertirse un caos al momento de intentar organizar tu código.

<a href="#" id="css-selectores"></a>
# Selectores

Como ya conocemos, las reglas de CSS utilizan selectores para llamar al elemento HTML que se desea estilizar. 

Existen varios tipos de selectores. En la tabla de abajo podrás encontrar la referencia que va desde el más básico hasta los selectores de nivel 3.

| Selector      | Significado                           | Ejemplo  |
| ------------- |:-------------------------------------:| -------: |
| Universal     | Aplica para todos los elementos HTML  |  * {}    |
| De Tipo     | Corresponde al nombre del elemento HTML | `h2`, `h3`, `h1` {} <br /> Se aplica a los elementos `<h1>`, `<h2>` y `<h3>` |
| Clase     | Captura el elemento cuyo atributo `class` tenga un valor que corresponda al especificado luego del símbolo `.` | `.nota` {} <br /> Se aplica a los elementos cuyo atributo `class` tiene un valor de `nota` <br /> `p.nota` {}  <br/ > Se aplica a los elementos `<p>` cuyo atributo `class` tiene un valor de `nota` |
| ID     | Captura el elemento cuyo atributo `id` tenga un valor que corresponda al especificado luego del símbolo `#` |  `#nombre` {} <br /> Se aplica a los elementos cuyo atributo `id` tiene un valor de `nombre` <br /> `p#nombre` {}  <br /> Se aplica a los elementos `<p>` cuyo atributo `id` tiene un valor de `nombre`    |

<a href="#" id="css-color"></a>
# CSS: Color

El color que vemos en la pantalla de una computadora es creado mezclando cantidades de rojo, verde y azul. Para conseguir el color que necesitamos, debemos de usar un selector de color. Usualmente programas como Photoshop tienen estas herramientas.

![CSS 9](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-9.png)

El color en CSS se divide en dos tipos: color en primer plano y segundo plano.

El color en primer plano se especifica con la propiedad `color` y para el color en segundo plano usamos la propiedad `background-color`.

Los valores para ambas propiedades se pueden determinar de tres formas:
  - Por nombre
  - Por código hexadecimal
  - Por valor RGB

### Nombres de Colores

CSS viene con 147 nombres predeterminados para colores que el navegador puede reconocer.

![CSS 8](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-8.png)

### Código Hexadecimal

El valor hexadecimal consiste en 6 valores de números o letras que representan la cantidad de rojo, verde y azul que contiene el color. 

Este valor lo antecede el símbolo `#`. Por ejemplo `#ee3e80`.

![CSS 10](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-10.png)

### Valor RGB

Este valor expresa el color en términos de cuanto rojo, verde y azul se utiliza. Por ejemplo `rgb(100,100,90)`.

![CSS 11](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-11.png)

### CSS3: Opacidad 

CSS3 nos presenta la propiedad `opacity` que nos permite determinar la opacidad de un elemento así como de sus hijos. El valor de esta propiedad es un número que puede estar entre 0 y 1, siendo 0 la desaparición total del elemento.

La propiedad `rgba` nos permite especificar el color de la misma manera que el valor `rgb` pero agrega un cuarto valor para indicar la opacidad. Este valor es conocido como `alpha` y como la propiedad `opacity` su valor es un número que va desde 0 al 1.

La diferencia entre `rgba` y `opacity` es que la opacidad de `rgba` sólo afecta al elemento al que se aplica más no a sus elementos hijos, en caso los tuviera.

![CSS 12](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-12.png)

<a href="#" id="css-texto"></a>
# CSS: Texto

Las propiedades que te permiten controlar la apariencia del texo se pueden devidir en dos grupos:
  - Las propiedades que afectan directamente a las fuentes ( como el tipo de letra, si el peso de la fuente es regular, negrita, italica y el tamaño de la fuente. )
  - Las propiedades que afectan al texto sin importar que fuente estén usando  ( como el color del texto y el espacio entre palabras y letras. )
  
## Escoger un tipo de letra para tu sitio

Cuando seleccionamos un tipo de letra es importante entender que el navegador solamente cargará ese tipo de letra si se encuentra instalado en la computadora del usuario

| Tipo de Letra | Ejemplo                               |
| ------------- |:-------------------------------------:| 
| sans          | Georgia, Times, Times New Roman  |
| sans-serif    | Arial, Verdana, Helvetica  |
| monospace     | Courier, Courier New  | 
| cursive       | Comic Sans MS, Monotype Cursiva  |
| fantasy       | Impact  | 

### Especificando tipos de letra

La propiedad `font-family` nos permite especificar la fuente que queremos usar para el texto que se encuentre dentro del elemento/s al cual le aplicamos una regla CSS. El valor de esta propiedad es el nombre de la fuente que queremos usar.

Recordemos que para que los usuarios puedan ver la fuente, deben de tenerla instalda en sus computadoras. En caso de que no sea posible, podemos especificar más de una fuente para que así el navegador pueda usar una alternativa de esa lista. También es común colocar al final un nombre génerico de tipo de letra. 

En caso de que el nombre de la fuente tenga más de una palabra se debe de colocar entre comillas.

![CSS 13](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-13.png)

### Especificando tamaños de fuentes  

La propiedad `font-size` nos permite especificar el tamaño de la fuente. Existen diferentes unidades de medida para esto. Las más comunes son

  - Pixeles: Los pixeles son una medida fija que da la mayor precisión y control a los diseñadores.
  - Porcentajes: El tamaño por defecto de una fuente es de 16px, por lo que un tamaño de 75% sería el equivalente a 12px y 200% sería el equivalente a 32px. 
  - EMs: Esta unidad de medida se basa en el ancho de la letra M.

![CSS 14](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-14.png)

<a href="#" id="css-cajas"></a>
# CSS: Cajas

Al comienzo de esta sección, vimos que CSS trata a todo HTML como si viviera en una caja invisible.

Existen diferentes propiedades que pueden controlar la apariencia de las cajas. Por ejemplo:
  - Controlar las dimensiones de las cajas
  - Crear bordes alrededores de las cajas
  - Crear espacios internos (padding) y externos (margin) entre cajas
  - Mostrar y esconder cajas

  ## Dimensiones de Cajas

  Antes de revisar las propiedades que controlan la dimensión de las cajas, debemos recordar que HTML está dividido en dos tipos de elementos:
    1. Elementos Bloque: Elementos que por defecto, tienen ancho es equivalente al ancho de la pantalla.
    2. Elementos In-Line: Elementos que por defecto, tienen un ancho equivalente al contenido que llevan dentro

  ![CSS 15](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-15.png)

  Dicho esto, nosotros podemos usar las propiedades `width` (ancho) y `height` (alto). La unidad de medida más usada para especificar dimensiones son los pixeles. 
  
  Si usamos porcentaje el ancho/alto de la caja se define según el ancho de la ventana del navegador o si la caja se encuentra dentro de una caja contenedora, su dimensión va a depender de la caja contenedora.  

  Otra unidad de medida es la `em`. Si usamos esta medida las dimensiones de la caja van a ser en relación al tamaño del texto que tiene.

  ![CSS 16](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-16.png)

  ## Limitando las Dimensiones de Cajas

  Muchos diseños de sitios se expanden y encogen para poder encajar en la pantalla del usuario. En este tipo de diseños la propiedad, `min-width` especifica el tamaño más pequeño que una caja puede tener cuando la ventana del navegador es estrecha y la propiedad `max-width` indica el ancho máximo que una caja debe de tener cuando la ventana del navegador es ancha.

  Estas propiedades ayudan muchísimo para asegurar que el contenido de las páginas de tu sitio sea legible ( especialmente para pantallas móviles )

  ![CSS 17](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-17.png)

  ## Contenido Desbordante

  La propiedad `overflow` hace que el navegador que hacer si el contenido de una caja is mayor que la caja. Esta propiedad nos devuelve 2 valores:
  - **hidden**: Este valor esconde cualquier contenido extra que se esté desbordando de una caja
  ![Overflow Hidden](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/overflow-hidden.gif)
  - **scroll**: Esta propiedad le agrega una barra de scrolling a la caja para que los usuarios puedan ver el contenido que no se vea.
  ![Overflow Scroll](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/overflow-scroll.gif)

  ## Bordes

  Toda caja tiene a su disposición tres propiedades que ayudar a controlar su apariencia:
  
  | Border        | Margin                               | Padding |
  |  -------------|:-----------------------------:| :-----------------------------:|  
  | Toda caja tiene un borde (incluso si no es visible). la propiedad `border` separa el borde de una caja de otra | Los márgenes se colocan fuera del borde de la caja. Podemos setear el ancho de un margen entre dos bordes de dos cajas adyacentes | Padding es el espacio que hay entre el borde de la caja y cualquier contenido que se encuentre dentro de la misma. Si `margin` es una propiedad para el espacio externo, `padding` es la propiedad para los espacios internos de la caja

  Si nosotros podemos especificar el ancho de una caja, los bordes, margin y padding son un agregado tanto para el ancho como para el alto.

  ![CSS 18](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-18.png)

  La propiedad `border` se divide en 3 categorías:
  - `border-width`
  - `border-style`
  - `border-color`

  ### Border Width

  La propiedad `border-width` se utiliza para controlar el ancho del borde. El valor de esta propiedad se puede definir en pixeles o utilizando uno de los siguientes valores predeterminados:
  * `thin`
  * `medium`
  * `thick`

  **Nota:** No podemos usar porcentajes como valor de esta propiedad.

  Al utilizar esta propiedad estamos dándole el mismo ancho de borde a los 4 lados de la caja. Si deseamos especificar diferentes anchos de borde para cada lado podemos usar estas propiedades por separado.

  * `border-top-width`
  * `border-right-width`
  * `border-bottom-width`
  * `border-left-width`

  **Tip:** Si queremos especificar diferentes anchos para los 4 lados en una sola línea podemos hacerlo de esta manera `border-width: 2px 1px 1px 2px;` en donde el orden de los valores son en el sentido a la agujas del reloj: `top`, `right`, `bottom` y `left`.

  ![CSS 19](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-19.png)

  ### Border Style

  Podemos controlar el tipo de un borde usando la propiedad `border-style`. Esta propiedad tiene los siguientes valores:
  * `solid`: una sóla línea continua
  * `dotted`: una serie de untos cuadrados
  * `dashed`: una serie de líneas cortas
  * `double`: dos líneas sólidas
  * `groove`: da la apariencia de tallado en el borde
  * `ridge`: da la apariencia de alto relieve en la página
  * `inset`: da la apariencia de estar incrustado en la página
  * `outset`: da la apariencia de salir de la pantalla
  * `hidden / none`: no muestra ningún borde

  ![CSS 20](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-20.png)

  ### Border Color

  Otra de las caracteristicas que podemos especificar para los bordes usando valores RGB, hexadecimales o valores predeterminados.

  Es posible controlar de forma individual los colores de los borders de cada uno de los 4 lados usando estas propiedades:
  * `border-top-color`
  * `border-right-color`
  * `border-bottom-color`
  * `border-left-color`

  Así como con `border-width`, es posible utilizar un atajo para colocar 4 colores diferentes en una sola propiedad por ejemplo: `border-color: darkcyan deeppink darkcyan deeppink;`. De igual manera, el orden de los valores va en el sentido de las agujas del reloj: `top` `right` `bottom` `left`.

  ### Atajo: Border

  La propiedad `border` nos permite especificar el ancho, estilo y el color de borde a lo largo de los 4 lados de la caja al que se le está aplicando la propiedad. 

  **Recuerda**: Cuando uses un atajo para cualquier propiedad, debes de respetar el orden de los valores. De lo contrario no funcionará el atajo.

  ![CSS 21](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-21.png)

  ## Espacios Internos y Externos

  ### Padding 

  La propiedad `padding` nos ayuda a especificar cuanto espacio debería de aparecer entre el contenido de un elemento y su borde. El valor de esta propiedad usualmente está especificado en pixeles pero también es posible usar porcentajes y ems.

  En caso de usarse porcentajes el padding es relativo al ancho o alto de la ventana del navegador o de la caja que funcione como contenedor de este elemento.

  Algo es importante a tomar en cuenta es que si nosotros le damos un ancho a nuestro elemento, el padding es agregado en este ancho.

  Como podemos ver en la imagen de abajo, el segundo párrafo es más sencillo de leer porque existe espacio entre el contenido y el borde de la caja. La caja también es mucho más ancha debido al padding.

  ![CSS 23](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-23.png)

  Podemos especificar diferentes valores para cada lado de la caja usando:

  * `padding-top`
  * `padding-right`
  * `padding-bottom`
  * `padding-left`

  Como atajo, podemos especificar los 4 lados en una sola línea usando `padding` en el orden al que van las agujas del reloj: `top`, `right`, `bottom`, `left`.

  ### Margin

  Esta propiedad controla el espacio externo entre cajas. Al igual que con `padding`, el valor usualmente es especificado en pixeles pero también puedes usar porcentajes y em.

  Al igual que con padding,si nosotros le damos un ancho a nuestro elemento, el margin es agregado en este ancho

  Podemos especificar diferentes valores para cada lado de la caja usando:

  * `margin-top`
  * `margin-right`
  * `margin-bottom`
  * `margin-left` 

  Como atajo, podemos especificar los 4 lados en una sola línea usando `margin` en el orden al que van las agujas del reloj: `top`, `right`, `bottom`, `left`.

  ## Centrar Contenido

  Si queremos que una caja sea centrada de forma horizontal podemos especificar el `margin-left` y el `margin-right` con un valor de `auto`. Para que esta técnica funcione, tenemos que darle a la caja un ancho.

  Una vez que le hayas dado un ancho a la caja, poner los margenes a `auto` hará que el navegador busque un espacio igual para el lado izquierdo y derecho haciendo que la caja se centre.

  ## Cambiar el comportamiento de un Elemento

  La propiedad `display` nos permite cambiar el estado de un elemento inline a un elemento bloque y viceversa. También puede ser usado para esconder el elemento del sitio.

  Los valores que recibe esta propiedad son:

  * `inline`: Para cuando quieras cambiar un elemento bloque en inline.
  * `block`: Para cuando quieras cambiar un elemento inline en bloque.
  * `inline-block`: Para cuando quieras alinear un elemento bloque de forma horizontal como un elemento inline, pero manteniendo sus caracteristicas de elemento bloque.
  `none`: Para esconder el elemento.

  ![CSS Display](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-display.gif)

  ## Escondiendo las cajas

  La propiedad `visibility` nos permite controlar cuando queremos que una caja sea visible o no. Esta propieda recibe dos valores:

  * `visible`: Para cuando quieras mostrar un elemento que estaba previamente escondido.
  * `hidden`: Para cuando quieras esconder un elemento.

  La diferencia entre `visibility: hidden;` y `display: none` es que `visibility` deja un espacio en blanco luego de esconder el elemento mientras que `display` hace lo contrario.

<a href="#" id="css-elementos-distribucion"></a>
# Distribución de Elementos

Como ya sabemos, CSS interpreta todo elemento HTML como si tuviera una caja invisible alrededor y estos elementos se dividen entre bloque e inline.

Los elementos bloque tienen la caracterísctica de comenzar en una nueva línea y por defecto, su ancho es equivalente al ancho de la ventana mientras que los elementos inline no comienzan en una nueva línea (por lo que son capaces de alinearse entre si horizontalmente) y su ancho depende del contenido que tienen.

![CSS 24](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-24.png)

![CSS 25](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-25.png)

## Elementos Contenedores 

Si un elemento bloque está dentro de otro elemento bloque entonces la caja que se encuentra fuera trabaja como un contenedor o como un elemento padre.

![CSS 26](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-26.png)

## Elementos Flotantes

La propiedad `float` hace que un elemento salga de su flujo natural y lo hace "flotar" lo más hacia la izquierda o derecha posible, dependiendo de que valor de la propiedad se esté usando. Cuando usamos esta propiedad es importante agregarle un ancho al elemento.

De lo contrario, habrán algunas inconsistencias a lo largo del diseño. 

Cualquier elemento que se encuentre dentro de un contenedor flotará alrededor del elemento que tiene la propiedad aplicada.

![CSS 27](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-27.png)

Esta propiedad es una de las que se utilizan para alinear cajas de forma horizontal. Sin embargo si tenemos más de un 1 elemento flotando que tienen diferentes altos, pueden ocurrir algunas inconsistencias como en el ejemplo de abajo.

![CSS 28](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-28.png)

Lo que está ocurriendo es que el alto del cuarto párrafo es menor que el resto, dejando un espacio en blanco que el quinto párrafo está buscando llenar.

Hacer que el alto de todos los párrafos sean los mismos o igual que el párrafo más alto es una posible solución pero no es una solución viable en términos de diseño de un sitio web que puede estar sujeto a múltiples cambios y/o rediseños. 

Para este caso la forma más común de resolverlo es usando la propiedad `clear` para el elemento que queremos que regrese a su lugar.

![CSS 29](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-29.png)

<a href="#" id="css-cascada"></a>
# La Cascada
 
Si hay dos o más reglas que son aplicadas al mismo elemento, es importante conocer cual de las reglas tendrá precendencia.

### La ultima regla, gana
Si ambos selectores son idénticos, la regla que venga al final tomará precedencia.

![CSS 6](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-6.png)

<a href="#" id="css-herencia"></a>
# Herencia

Antes de entender como funciona la herencia en CSS, debemos considerar que la estructura de etiquetas HTML trabaja como un arbol genenalogico en donde exiten elementos que son padres, hijos y hermanos.

La siguiente imagen hace una demostración de este arbol.

![CSS 22](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-22.png)

Por ejemplo, si usamos las propiedades `font-family` o `color` en el elemento `<body>`,estas propiedades se aplicarán a la mayoría de los elementos hijos. Esto se debe a que el valor de la propiedad `font-family` es heredado por ellos. De esta manera, nos ahorramos el tener que aplicar ciertas propiedades de manera repetitiva a otros elementos.

Sin embargo, no todas las propiedaes de CSS son heredables pero gracias a CSS podemos forzar a que lo sean. Echale un vistazo al ejemplo de abajo en donde forzamos el valor de la propiedad `padding` que se encuentra en `body` a que sea aplicado al elemento `.page`.

![CSS 7](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-7.png)

<a href="#" id="css-especificacion"></a>
# Especificacion

Si un selector es más específico que los demás, la regla más específica es la que tomará más precedencia. Por ejemplo:

`h1` es más específico que `*` <br />
`p span` es más específico que `p` <br />
`p#intro` es más específico que `p` <br />

<a href="#" id="intro-js"></a>
# JavaScript: Introducción

JavaScript es un lenguaje de programación que nos ayuda a crear interacción entre los elementos de un sitio y lo que hace el usuario. No es necesario instalar nada para obtener el lenguaje debido a que este ya está integrado de forma nativa en el navegador. Es decir, usando la consola del inspector de Chrome podemos programar en JavaScript en tiempo real!

![JS 13](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-13.png)

JavaScript, como todo lenguaje de programación consta de 5 elementos fundamentales para su entendimiento: 

  * Variables
  * Condicionales 
  * Funciones
  * Ciclos
  * Objetos

A continuación veremos a detalle como funcionan estos 5 elementos y la relación que tienen con la web.

## Sintaxis

Así como podemos escribir Javascript en la consola de Chrome, también podemos escribirlo en Sublime creando un archivo de formato `js`. 

La sintaxis de un lenguaje de programación es un conjunto de reglas que deben seguirse para escribir el código fuente del que se basará la creación de un programa. Las normas básicas para escribir Javascript son las siguientes:

* **No se tienen en cuenta los espacios en blanco y las nuevas líneas:** El intérprete de JavaScript ignora cualquier espacio en blanco sobrante, esto nos permite ordenar el código para un mejor entendimiento (tabulando las líneas, añadiendo espacios, creando nuevas líneas, etc.)

* **Se distinguen las mayúsculas y minúsculas:**  JavaScript interpreta como dos elementos diferentes que tienen el mismo nombre pero uno está escrito en mayúscula y el otro en minúscula.

* **No se define el tipo de las variables:** Al crear una variable, no es necesario indicar el tipo de dato que almacenará. De esta forma, una misma variable puede almacenar diferentes tipos de datos durante la ejecución del script.

* **Se pueden incluir comentarios:** los comentarios se utilizan para añadir información en el código fuente del programa. Aunque el contenido de los comentarios no se visualiza por pantalla, si que se envía al navegador del usuario junto con el resto del script, por lo que es necesario extremar las precauciones sobre la información incluida en los comentarios.

Para poder crear un programa en Javascript primero necesitamos conocer los tipos de datos que el lenguaje soporta:

### Numeros 

En Javascript los números pueden ser enteros o flotantes. Asimismo, Javascript soporta operaciones matemáticas básicas. 

![JS 1](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-1.png)

__Imagen sacada de [Ceviche.js - Sintaxis Básica](http://cevichejs.com/1-javascript#sintaxis-basica)__  

Asimismo existe el objeto `Math` que nos ayuda para cuando necesitamos hacer operaciones como redondear números, generar números random, etc.

### Cadenas

Las cadenas refieren a los elementos que son escritos con comillas simples o dobles. Es la manera en como Javascript entiende la diferencia entre data y texto plano.

![JS 2](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-2.png)

Este tipo de datos también es considerado como un objeto y por lo tanto contiene propiedades como `length`  que te devuelve el total de caracteres que lo contiene y métodos como `toUpperCase()` y `toLowerCase()` que te devuelven la cadena en mayúsculas y minúsculas respectivamente.

![JS 3](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-3.png)

### Booleanos

Un tipo de dato booleano es aquel cuyo valor puede ser verdaderos (`true`) o falsos (`false`). 

### Arreglos

Los arreglos son objetos que pueden guardar diferentes tipos de datos.

![JS 5](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-5.png)

> Los arreglos tienen una propiedad llamada `length` y utilizan los corchetes `[]` para acceder a un elemento del arreglo a través de su índice. En JavaScript, el índice de los arreglos empieza en 0 y el valor de length es igual al último índice del arreglo más uno. - __[Ceviche.js - Arrays](http://cevichejs.com/1-javascript#arrays)__

Al ser objetos, los arreglos tienen una serie de métodos que sirven para manipularlos:

* join
* pop 
* push
* indexOF
* rseverse
* concat 
* slice
* splice

Para ver información más detallada sobre estos métodos y como aplicarlos en los, puedes ingresar a  [Ceviche.js - Arrays](http://cevichejs.com/1-javascript#arrays) 

<a href="#" id="js-variables"></a>
# Variables 

Las variables son pequeños espacios en la memoria donde podemos guardar objetos. Debido a que Javascript es un lenguaje dinámico, una misma variable puede guardar diferentes tipos de datos.

Las variables son declaradas usando la palabra reservada `var` y puede tener un valor definido o estar vacia

![JS 4](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-4.png)

Gracias a nuevas actualizaciones del standard del lenguaje, ahora podemos declarar variables constantes usando `const` variables que solo viven en el bloque donde se declaran usando `let`. 

<a href="#" id="js-condicionales"></a>
# Condicionales

Las estructuras condicionales son un bloques de código cuya ejecución va a depender de la veracidad o falsedad de una condición. Para crear estas estructuras utilizamos las palabras reservadas `if`, `else` y `else if` además de utilizar las `{}` para determinar los bloques de código que queremos ejecutar.

![JS 6](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-6.png)

<a href="#" id="js-ciclos"></a>
# Ciclos: Estructuras Repetitivas

Las estructuras repetivas nos permiten implementar un grupo de instrucciones varias veces siempre y cuando se cumpla una condición. 

También podemos recorrer objetos o arreglos. Existen 4 maneras de construir un ciclo. 

### for

![JS 7](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-7.png)

### for..in

![JS 8](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-8.png)

### while

![JS 9](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-9.png)

### do..while

![JS 10](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-10.png)

<a href="#" id="js-funciones"></a>
# Funciones

Javascript es un lenguaje que trabaja de manera síncrona, es decir, el código que se vaya a ejecutar dependerá del orden en que colocamos las instrucciones. Si vemos el ejemplo de abajo, el `console.log()` no se ejecutará hasta que la `alert()` termine su ciclo de ejecución.

![JS 11](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-11.png)

Debido a la naturaleza síncrona de Javascript, las funciones nos permiten agrupar código y ejecutarlo en diferentes momentos en que se está corriendo el programa. Asimismo, las funciones nos permiten crear funcionalidad que puede ser reutilizable.

Para declarar una función necesitamos usar la palabra reservada `function`. Podemos darle nombre a la función o también podemos asignarla a una variable como una función anónima.

![JS 12](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-12.png)

### Parametros

Para que una función pueda ser reutilizable, podemos pasarle parámetros que funcionan como variables temporales dentro de la función pero cuyo valor no se declara cuando se define la función, sino al momento de ejecutarla. 

> El número de parámetros pasados a una función no es estricta. Si una función está definida para aceptar 3 argumentos y se le pasan 2 parámetros, el tercer parámetro será asignado a undefined, mientras que si a la misma función se le pasan 4 parámetros, el cuarto parámetro será ignorado. Es decir, si se tiene una función sum: - __[Ceviche.js - Funciones](http://cevichejs.com/1-javascript#funciones)__

![JS 14](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-14.png)

### Return

Toda función, luego de ser ejecutada, es capaz de retornar un valor y nosotros podemos especificar explicitamente que valor queremos que la función retorne. En caso de no hacerlo, la función siempre retornará `undefined`

![JS 15](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-15.png)

Para mayor detalle sobre Funciones puedes ir a [Cevichejs - Funciones](http://cevichejs.com/2-funciones)

<a href="#" id="js-objetos"></a>
# Objetos

Así como tenemos objetos de cadenas (String) y numeros (Number) también podemos crear nuestros propios objetos. Como se puede ver en el ejemplo de abajo, hemos creado un objeto literal llamado `persona` que contiene varios tipos de propiedades y un método `saludo`

![JS 16](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-16.png)

Una de las ventajas que nos da crear objetos es que podemos agrupar valores, al igual que un arreglo pero al mismo tiempo podemos tener un mejor contexto de donde vienen esos valores.

### Accediendo a los valores de un Objeto

Existen dos maneras de poder acceder a los valores de las propiedades y metodos de un objeto. En ambos casos debemos referenciar el objeto y podemos usar tanto un punto `.` o los corchetes `[]` para imprimir sus valores. Como el ejemplo de abajo. 

![JS 17](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-17.png)

Esta es la manera más básica de construir un objeto. Para detalles más avanzados de como el lenguaje maneja y contruye objetos puedes ir a este [Ceviche JS - Tipos vs Objetos](http://cevichejs.com/1-javascript#tipos-vs-objetos)

<a href="#" id="js-dom"></a>

## ¿Qué es una API?

Antes de que hablemos sobre lo que es el DOM necesitamos conocer lo que es una API. 

**Una API ( Aplication Programming Interface ) es un conjunto de funciones y procedimientos que se construye con el fin de ser usado por otro software**

Esto quiere decir que una API funciona como un puente de conexión entre un programa y otro. En este caso, para que nosotros podamos crear interfaces que responden a lo que hace el usuario necesitamos una manera de poder conectar lo que hacemos en JavaScript con lo que ocurre en el navegador. Aquí es donde la API o APIs entran al juego.

> Existen dos APIs en el navegador que permiten manipular la estructura, contenido y presentación visual de lo que se muestra dentro de un navegador: el Document Object Model, o DOM, y el Cascade Style Sheet Object Model, o CSSOM. - __[Ceviche.js - DOM Y CSSDOM](http://cevichejs.com/3-dom-cssom)__

## El DOM

El Document Object Model más conocido como DOM, es una API del navegador que se encarga de representar cada elemento HTML como un objeto y de esta manera, nos permite manipular y estilizar la presentación de nuestras interfaces. 

También es capaz de detectar las acciones ( también conocidas como **eventos** ) que realiza el usuario en el navegador.

La manera en como esta API hace la representación de los elementos HTML es a través del concepto de **arbol de nodos** en donde si un elemento contiene otro dentro de él, el elemento en cuestión es considerado un _nodo padre_ y los elementos dentro sus _nodos hijos_ 

Existen diferentes tipos de nodos que representan todas las partes del documento HTML. Para ver la tabla completa ingresar a [Ceviche JS - Nodos y Elementos ](http://cevichejs.com/3-dom-cssom#nodos-y-elementos)

## Document

Ahora que ya sabemos que es una API y que es el DOM necesitamos desde JavaSript poder acceder a él. Aquí es donde utilizamos el objeto `document`. Este objeto representa al nodo raíz del documento HTML y nos ayudará a poder utilizar las propiedades y métodos que necesitemos para seleccionar y modificar los nodos que querramos ya sea agregando un nuevo nodo, cambiando su estilo, agregando contenido nuevo, etc.

A modo de ejemplo podemos ver en la imagen de abajo que podemos llamar desde la consola de Chrome al objeto y nos dará el arbol de nuestro archivo de HTML.

![JS 18](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-18.png)

Existen 3 conceptos que haces un sitio o aplicación web interactivo:

  * Selección del elemento
  * Manipulación del elemento
  * Escuchar las acciones del usuario

### Document : Seleccion de Nodos

El objeto `document` nos permite seleccionar los nodos del árbol HTML con los siguientes métodos

 * **getElementById():** Selecciona un nodo HTML en base al valor del atributo `id`.
 ![JS 19](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-19.png)

 * **getElementsByClassName():** Selecciona un nodo HTML en base al valor del atributo `class`.
 ![JS 20](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-20.png)

 * **getElementsByTagName():** Selecciona un nodo HTML en base al tipo de nodo.
 ![JS 21](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-21.png)

 * **querySelector():** Selecciona un nodo HTML cuyo valor selector sea igual al argumento que se pasa por el método. Este método soporta selectores por `id` , `class`, atributo y selectores CSS de tercer nivel. En caso de haber más de un elemento con un mismo nombre de clase o tipo, el método solamente te devolverá el primer nodo que encuentre y el resto los ignorará.

 ![JS 22](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-22.png)


 * **querySelectorAll():**  Selecciona un nodo HTML cuyo valor selector sea igual al argumento que se pasa por el método. Este método soporta selectores por `id` , `class`, atributo y selectores CSS de tercer nivel. En caso de haber más de un elemento con un mismo nombre de clase o tipo, el método solamente te devolverá el primer nodo que encuentre y el resto los ignorará.

  ![JS 23](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-23.png)
 
### Document : Modificación de Contenido de Nodos

El objeto `document` nos permite modificar el contenido de los nodos del árbol HTML con las siguientes propiedades:

  * **innerHTML**
  * **textContent**

  ![JS 24](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-24.png)

### Document : Modificación de Atributos de Nodos

El objeto `document` nos permite crear y/o modificar los atributos de los nodos del árbol HTML con algunos de estos métodos y propiedades:

* **setAttribute():** Este método es para crear un nuevo atributo y recibe dos argumentos siendo el primero el nombre del atributo a crear y el segundo el valor del atributo creado.

![JS 25](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-25.png)

* **type** 

![JS 26](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-26.png)

* **className**

![JS 27](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-27.png)

### Document : Creando Nodos

El objeto `document` nos permite crear nuevos nodos del árbol HTML con el métdo `createElement`

![JS 28](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-28.png)

### Document : Anidando Nodos

El objeto `document` nos permite anidar nuevos nodos dentro árbol HTML con los metodos `appendChild()` y `prepend()`

![JS 29](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-29.png)

### Document : Eliminando Nodos

El objeto `document` nos permite eliminar nodos dentro árbol HTML con el método `removeChild()`.

![JS 30](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/JavaScript/js-30.png)

## Eventos del DOM


