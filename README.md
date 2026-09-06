# fundamentos-web-taller1
# Taller 1 - Fundamentos Web

Nombre: Diego Andres Martinez Ramirez

Este reporsitorio contiene el primer taller de HTML de la asignatura Fundamentos de Programacion Web

## Verificación de codigo

### Caso A

Problema identificado:

```<img href="multimedia/perfil.jpg" alt ="Fotografia del estudiante">```

La etiqueta "img" no utiliza href sino que utiliza src, href que es para enlaces utiliza la etiqueta "a"

Correción realizada:

```<img src="multimedia/perfil.jpg" alt ="Fotografia del estudiante">```

Fuente Consultada:

Taller_1_HTML_Fundamentos_WEB_4303.pdf

### Caso B

Problema identificado:

```<a src="https://developer.mozilla.org"> Consultar MDN </a>```

La etiqueta "a" no utiliza src sino que utiliza href, src que es para imagenes utiliza la etiqueta "img"

Correción realizada:

```<a href="https://developer.mozilla.org"> Consultar MDN </a>```

Fuente Consultada:

Taller_1_HTML_Fundamentos_WEB_4303.pdf

### Caso C

Problema identificado:
```
<video controls>
<source href="multimedia/video.mp4" type="video/mp4">
</video>
```

La etiqueta source no utiliza href sino que utiliza src, href es para imagenes y "source src" se utiliza para contenido multimedia como videos y audios.

Correción realizada:
```
<video controls>
<source src="multimedia/video.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
```

Fuente Consultada:

Taller_1_HTML_Fundamentos_WEB_4303.pdf

### Caso D

Problema identificado:
```
<form>
<input type="correo" name="correo">
</form>
```
La etiqueta "input" no utiliza type="correo", ya que "correo" no es un valor válido para el atributo type. Para crear un campo destinado a ingresar una dirección de correo electrónico se debe utilizar type="email". (no se si tambien le falta un label o no es necesario y sin label no hay id).

Correción realizada:
```
<form>
<input type="email" name="correo">
</form>
```
Fuente Consultada:

Taller_1_HTML_Fundamentos_WEB_4303.pdf

### Caso E

La afirmación:

La etiqueta "image" es la etiqueta estandar de HTML5 para insertar una imagen y siempre debe cerrarse utilizando "image"

Es falsa

Justificación:

La etiqueta "image" no es la etiqueta estándar de HTML para insertar imágenes, en HTML5 se utiliza la etiqueta "img" que además no necesita de un "img" al ser un elemento vacio.


Fuente Consultada:

https://lenguajehtml.com/html/multimedia/etiqueta-html-img/
