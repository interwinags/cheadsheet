# Mi hoja de trucos de HTML
## **Estructura basica de HTML**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
## **Componentes del head**
```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style type="text/css">
        /*css code*/
    </style>
    <script> src="script.js" </scritp>
    <script>
        //java script code
    </script>
    <meta name="keywords" content="keywords">
    <meta name="author" content="name">
    <meta name="descripcion" content="descripcion">
</head>
```

## **Componentes del body**
### Cabeceras
<h1>Titulo 1</h1>
<h2>Titulo 2</h2>
<h3>Titulo 3</h3>
<h4>Titulo 4</h4>
<h5>Titulo 5</h5>
<h6>Titulo 6</h6>

```
Sintaxis
<h1>Titulo 1</h1>
<h2>Titulo 2</h2>
<h3>Titulo 3</h3>
<h4>Titulo 4</h4>
<h5>Titulo 5</h5>
<h6>Titulo 6</h6>
```
### Parrafos
<p>Este es el parrafo 1</p>
<span>Este es el parrafo 2</span>

```
Sintaxis:
<p>Este es el parrafo 1</p>
<span>Este es el parrafo 2</span>
```
### Formatos de parrafos
<p>este es un <em>parrafo</em> <strong>importante</strong></p>
<p>esta es una formula: a+b<sup>2</sup>+b<sup>2</sup></p>

```
Sintaxis:
<p>este es un <em>parrafo</em> <strong>importante</strong></p>
<p>esta es una formula: a+b<sup>2</sup>+b<sup>2</sup></p>
```
### Citas
<p><cite>Este libro</cite> es una referencia a un autor</p>
<q cite="url">referencia</q>
<blockquote cite="url">Contenido</blockquote>  
<hr>

```
Sintaxis:
<p><cite>Este libro</cite> es una referencia a un autor</p>
<q cite="url">referencia</q>
<blockquote cite="url">Contenido</blockquote>
```
### Links
<a href="https://www.lanominamasfacil.com.mx/"> InterWin Software </a>
```
Sintaxis:
<a href="https://www.lanominamasfacil.com.mx/"> InterWin Software </a>
```
### Imagenes
```
Sintaxis:
<img src="images/dinosaur.jpg" alt="descripcion" width="300" height="200"/>
<img src="https://www.example.com/images/dinosaur.jpg" />
```

### Bloques
<div> bloque </div>
<span> inline </span>

```
Sintaxis:
<div> bloque </div>
<span> inline </span>
```
### Listas
#### Listas desordenadas
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ul>

```
Sintaxis:
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ul>
```
#### Listas ordenadas
<ol>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ol>
<ol type="a">
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ol>

```
Sintaxis:
<ol>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ol>
<ol type="a">
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ol>
```
### Tablas
<table>
<tr>
    <th>encabezado 1</th>>
    <th>encabezado 2</th>>
    <th>encabezado 3</th>>
</tr>
<tr>
    <td>linea 1,1</td>
    <td>linea 1,2</td>
    <td>linea 1,3</td>
</tr>
<tr>
    <td>linea 2,1</td>
    <td>linea 2,2</td>
    <td>linea 2,3</td>
</tr>
</table>

```
Sintaxis:
<table>
<tr>
    <th>encabezado 1</th>>
    <th>encabezado 2</th>>
    <th>encabezado 3</th>>
</tr>
<tr>
    <td>linea 1,1</td>
    <td>linea 1,2</td>
    <td>linea 1,3</td>
</tr>
<tr>
    <td>linea 2,1</td>
    <td>linea 2,2</td>
    <td>linea 2,3</td>
</tr>
</table>
```
### Formularios
<form action="url">
    <fieldset>
        <legend>Identificate</legend>
        <label for "username"> Nombre de usuario: </label>
        <input type="text" name="username" >
        <hr>
        <label for "password"> Teclee su password: </label>            
        <input type="text" name="password">
        <hr>
        <label for "email"> Teclee su email: </label>
        <input type="text" name="email">
    </fieldset>
</form>

```
Sintaxis:
<form action="url">
    <fieldset>
        <legend>Identificate</legend>
        <label for "username"> Nombre de usuario: </label>
        <input type="text" name="username" >
        <hr>
        <label for "password"> Teclee su password: </label>            
        <input type="text" name="password">
        <hr>
        <label for "email"> Teclee su email: </label>
        <input type="text" name="email">
    </fieldset>
</form>
```



