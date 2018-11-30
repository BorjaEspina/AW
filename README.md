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
	
