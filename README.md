# Lab: Agregando JavaScript a una página web

## Objetivos
- Utilizar las etiquetas de apertura y cierre `<script></script>` para agregar código de javascript a una página web.


## Introducción 
De manera similar a la etiqueta `<style>` utilizada para incrustar código CSS dentro de un archivo HTML, la etiqueta `<script>` se utiliza para incrustar código JavaScript dentro de un archivo HTML. 


## Funcionalidad del Código
En este lab crearemos codigo javascrip dentro de un documento html

## Instrucciones 
Bifurca (fork) y clona (clone) este lab en tu entorno local. Navega a su directorio en la terminal, luego ejecuta el comando `code .` para abrir sus archivos en Visual Studio Code. 

1. En tu código HTML, agrega un elemento script al final de `<body>`. Recuerda incluir la etiqueta de apertura y la etiqueta de cierre.

2. Copia y pega el siguiente código JavaScript dentro de las etiquetas de apertura y cierre `<script>`:

```
const flappyBird = document.querySelector("#flappy-bird")

   flappyBird.addEventListener("click", function() {
       alert("Hola!")
   })

```

3. Guarda tus cambios (Archivo > Guardar)

4. Abre tu archivo html en el navegador.  Da click sobre la imagen de flappy bird que se encuentra en la parte inferior izquierda de la página web. Al dar click, te debe de aparecer una ventana con el mensaje `"Hola desde el elemento <script>!"` 

5. Sube tus cambios a Github y envía por Canvas el enlace a tu repositorio.