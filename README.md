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
Una pseudo-clase es usada para definir un estado especial de un elemento. Se da uso con una clave precedida de dos puntos que se añade al final del sector para indicar que daremos estilo a los elementos seleccionados solo cuando se encuentren en un estado determinado. Por ejemplo:
:active <br>
:any <br>
:checked <br>
:default <br>
:dir() <br>
:disabled <br>
