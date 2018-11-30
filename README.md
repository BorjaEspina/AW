# AW
Estos son los ejercicios. <br>
## 1.- Estructura mínima de una web:
```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>
```
## 2.- Explica las 3 formas de usar CSS en HTML:
La primera forma es añadiendo un style en head, de esta forma:
```html
<head>
	<style>
		p{color:red}
	</style>
</head>
```

La segunda es añadiendo el css en una misma linea, de esta forma:
```html
<p style="font-family: sans">Esto es un párrafo</p>
```

La última forma es creando un archivo CSS y añadiendolo con html:

```html
<head>
	<link rel="stylesheet" type="text/css" href="archivo.css">
</head>
```

## 3.- Crea una lista sin ordenar con 5 ingredientes de una receta de cocina
```html
<ul>
	<li>lechuga</li>
	<li>tomate</li>
	<li>aceitunas</li>
	<li>maíz</li>
	<li>vinagre</li>
</ul>
```
## 4.- Como se puede incluir javascript en HTML
Se añade un <script> y se aclara que elemento se tiene que ejecutar entre los parentesis.
```html
<script>
	document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>
```
	
## 5.-¿Que diferencia hay entre una clase y una ID
Un ID deberá ser un elemento único, solo deberia un elemento con el mismo nombre de identificador dentro del documento HTML. Un class es un elemento que se puede usar para más de un elemento, semánticamente es lo correcto.

## 6.- Código para hacer un enlace a otra página y que esta se abra en una nueva ventana
Lo primero será escojer el link de la página y añadirla en "a href"???", con esto nos mandaría al link al pulsar sobre el elemento. Ahora para abrirlo en una ventana a parte añadiremos detras del link "target="_blank", de esta forma se abrirá en una ventana aparte. Ejemplo:
```html
<a href="https://w3school.com" target="_blank">Ejemplo</a>
```

## 7.- ¿Qué son las pseudoclases?, pon ejemplos.
Una pseudo-clase es usada para definir un estado especial de un elemento. Se da uso con una clave precedida de dos puntos que se añade al final del sector para indicar que daremos estilo a los elementos seleccionados solo cuando se encuentren en un estado determinado. Por ejemplo: <br>
:active <br>
:any <br>
:checked <br>
:default <br>
:dir() <br>
:disabled <br>

## 8.- Explica el modelo de caja de CSS (margin, border y padding)
El modelo de la caja de CSS marca los margenes que tienen los elementos, es decir, cada elemento contiene un margin, un border y un padding, y nosotros lo podemos modificar segun lo queramos. El margin es el margen que existe entre nuestro elemento y el resto de elementos, y el margen comenzaría a partir del border. El border es una linea que puede ser de dimensiones 0 o más, es decir, podemos hacer que exista un border o que no. Esta característica se encuentra entre el margin y el padding, y es una línea con las decoraciones que queramos que puede ser más o menos ancha. El padding es la última característica, y marca la distancia que hay entre el elemento con el borde exterior, y con el resto de elementos que se encuentren dentro de ese borde.

## 9.- Explica que son los selectores de CSS y pon ejemplos
Los selectores en CSS son los componentes de una página web. La información en una página web se ordena y clasifica en selectores para dar la forma que se desea. Por ejemplo: <br>
h1 <br>
aside <br>
nav <br>

## 10.- Di a quien afectan:
p a { color: red;} = Afectaría a las A dentro de P.

p > a { color: red; } = Afectaría a los hijos directos de A dentro de P.

h1 + h2 { color: red } = Afectaría a los elementos h2 seguidos de h1.

a[class] { color: blue; } = Los links se colorearía de azul.

a[class="externo"] { color: blue; } = Los links con la clase "externo" se colorearían de azul.

a[href="http://www.ejemplo.com"] { color: blue; } = Se colorearía el link que está entre comillas.
