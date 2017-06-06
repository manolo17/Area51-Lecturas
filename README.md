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

Si bien sabemos 

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

El color en CSS se divide en dos tipos: Color en primer plano y segundo plano.

El color en primer plano se especifica con la propiedad `color` y para el color en segundo plano usamos la propiedad `background-color`.

Los valores para ambas propiedades se pueden determinar de tres formas:
  - Por nombre
  - Por código hexadecimal
  - Por valor RGB

### Nombres de Colores

CSS viene con 147 nombres predeterminados para colores que el navegador puede reconocer.

![CSS 8](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-8.png)

<a href="#" id="css-texto"></a>
# CSS: Texto

<a href="#" id="css-cajas"></a>
# CSS: Cajas

<a href="#" id="css-cascada"></a>
# La Cascada

Si hay dos o más reglas que son aplicadas al mismo elemento, es importante conocer cual de las reglas tendrá precendencia.
### La ultima regla, gana
Si ambos selectores son idénticos, la regla que venga al final tomará precedencia.

![CSS 6](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-6.png)

<a href="#" id="css-herencia"></a>
# Herencia

Por ejemplo, si usamos las propiedades `font-family` o `color` en el elemento `<body>`,estas propiedades se aplicarán a la mayoría de los elementos hijos. Esto se debe a que el valor de la propiedad `font-family` es heredado por elementos hijo. Esto nos ahorra el tener que aplicar ciertas propiedades de manera repetitiva a otros elementos.

Sin embargo, no todas las propiedaes de CSS son heredables pero gracias a CSS podemos forzar a que lo sean. Echale un vistazo al ejemplo de abajo en donde forzamos el valor de la propiedad `padding` que se encuentra en `body` a que sea aplicado al elemento `.page`.

![CSS 7](https://github.com/Area51TrainingCenter/Area51-Lecturas/blob/master/images/CSS/css-7.png)

<a href="#" id="css-especificacion"></a>
# Especificacion

Si un selector es más específico que los demás, la regla más específica es la que tomará más precedencia. Por ejemplo:

`h1` es más específico que `*` <br />
`p span` es más específico que `p` <br />
`p#intro` es más específico que `p` <br />

