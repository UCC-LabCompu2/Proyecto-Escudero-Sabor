# proyecto2022

### Grupo
     Escudero y Sabor
### Idea del proyecto
    Realizar una Pokedex a corta escala con toda la informacion detallada del pokemon, incluyendo sus estadisticas variables.
### Tecnologias usadas
    HTML 5
    CSS
    Git
    Github
    Google Imagenes
### Sobre el Repositorio
Link del sitio web: [Pokedex](https://ucc-labcompu2.github.io/Proyecto-Escudero-Sabor/)
    


## Requisitos del Primer Parcial

### Sobre el Repositorio
- [x] El proyecto debe estar subido al repositorio adecuado "Proyecto2022-ApellidoAlumno1-ApellidoAlumno2"
- [x] Modificar el Readme.MD y colocar información del proyecto/página (mínimamente: título del proyecto, autores con nombre y apellido, link de gh-pages, contenido de la página,  listado de tecnologías usadas, etc)
- [x] La estructura del proyecto debe ser adecuada (crear una carpeta para las imágenes, otra para los sketch/mockups/Wireframes). Es importante que contenga SKETCH y MOCKUP/WIREFRAME (debe estar en formato: PDF, PNG o JPG).
- [x] El código debe estar pusheado en el repositorio (emplear gh-pages ó publicar la página desde el main), y no debe haber diferencias entre **main** y **gh-pages** (verificar de realizar el Merge).
- [x] Publicar la Web empleando GitHubPages
- [x] El repositorio no debe contener archivos innecesarios (no debe contener .idea o .vsc, en todo caso emplear **.gitignore**)

### Sobre el Proyecto General
- [x] La página principal debe llamarse index
- [x] Identar correctamente el código (en Webstorm Ctrl+Alt+L)
- [x] No debe haber errores presentes (realizar *Code* > *Inspect Code* para verificar que no haya errores)
- [x] Se debe emplear algún favicon
- [x] Emplear alguna fuente de google fonts o subir al proyecto alguna fuente externa
- [x] Debe haber navegación entre todas las páginas

### Sobre el HTML
- [x] Todas las etiquetas deben estar en minúscula
- [x] Poner comillas a todos los atributos
- [x] Title debe contener el título de la página
- [x] En el ```<head></head>``` incluir las etiquetas ```<meta>``` detallando: autor, descripcion y palabras clave
- [x] Emplear al menos 3 etiquetas semánticas diferentes (header, nav, aside, section, article, footer)
- [x] Emplear ```<header></header>```. En el contenido de la cabecera debe haber un título ```<h1></h1>```, puede tener color de fondo, algún logotipo, etc.
- [x] Debe haber por lo menos una etiqueta ```<img>``` en la página.
- [x] La estructura de la página debe estar definida con ```<div></div>```
- [x] Debe contener al menos 3 elementos de tipo ```<input>``` o ```<select>``` ó ```<button>``` que le permitan al usuario ingresar valores para poder realizar un cálculo de un ejercicio.
- [x] Debe contener un ```<canvas>```, para que posteriormente (en la 2da etapa) se grafique alguna imagen representativa del ejercicio. (el desarrollo del gráfico se realizará cuando se vea la unidad de “Orientación a Eventos”)
- [x] No espaciar con excesivos ```<br>```. Utilizar márgenes, paddings, etc.
- [x] No utilizar etiquetas deprecadas.
- [x] Todas las etiquetas deben estar correctamente cerradas
- [x] Los ids de los elementos deben ser unívocos

### Sobre el CSS
- [x] El estilo de los elementos debe establecerse en un archivo CSS (prohibido poner el atributo style a los elementos o emplear estilos incrustados).
- [x] El CSS debe contar mínimo con un tipo de cada forma (por Tag, por ID y por clase).
- [x] Se debe emplear pseudoclase
- [x] No emplear !important

### Sobre Accesibilidad:
- [x] Toda imagen debe tener su etiqueta alt
- [x] Todo ```<input>``` o ```<select>``` debe tener su ```<label>```
- [x] Los labels deben contener el atributo **for** (el for debe contener el id del input al cual se referencia) 
- [x] Si hay una tabla en la página, debe contener ```<caption></caption>```

### Sobre las correcciones
* Se corregirá el proyecto con el último commit realizado en Github hasta las 23:59 del día anterior a la fecha de entrega
* Las notas serán de manera logarítmica: (Por ejemplo 60% 4; 70% 5,5; 80% 7; 90% 8,5)



## Requisitos del Segundo Parcial

### Sobre el proyecto general
- [ ] Todas las correcciones y mejoras solicitadas durante el primer parcial deben estar corregidas.
- [ ] No debe haber errores presentes en el código (realizar Code > Inspect Code para verificar que no haya errores)
- [ ] No debe haber errores JavaScripts presentes. (ver con F12 si hay errores)

### Sobre la funcionalidad JavaScript
Se debe agregar funcionalidad Js a la página HTML+CSS desarrollada
- [ ] Una función que compruebe si los valores ingresados son correctos, y si no lo son, que le indique al usuario por un alert, y que blanquee el contenido del campo.
- [ ] Una función que calcule algo en base a los valores ingresados por el usuario en los inputs.
- [ ] Una función que realice un dibujo sobre un canvas (debe ser representativo y acorde a los valores ingreados).

### Sobre la documentación
- [ ] TODAS las funciones javaScript deben estar comentadas adecuadamente. [JsDoc](https://jsdoc.app/about-getting-started.html)
   ```/**
     * Descripción de que hace la función
     * @method Nombre de la función
     * @param {string} ParámetroA - Explicación de que valor almacena ParámetroA
     * @param {number} ParámetroB - Explicación de que valor almacena ParámetroB
     * @return Valor que retorna
     */
   ```
   
### Sobre las correcciones
* Se corregirá el proyecto con el último commit realizado en Github hasta las 23:59 del día anterior a la fecha de entrega
* Las notas serán de manera logarítmica: (Por ejemplo 60% 4; 70% 5,5; 80% 7; 90% 8,5)
* Las sugerencias sobre el HTML y CSS realizadas en el anterior parcial dejen ser corregidas.

   
## Requisitos del FINAL
- [ ] Todas las correcciones y mejoras solicitadas durante el primer y segundo parcial deben estar corregidas.
- [ ] No debe haber errores presentes en el código (realizar Code > Inspect Code para verificar que no haya errores)
- [ ] No debe haber errores JavaScript presentes (F12 > Consola)
- [ ] Debe cumplir con TODOS los requisitos del 1er y 2do Parcial (si se agrego código nuevo en Js, se debe documentar, si hay nuevos inputs de html deben contener su label, etc)
- [ ] El Canvas debe poseer animación con setInterval() o requestAnimationFrame()
- [ ] El cálculo del ejercicio de física/etc debe ser el correcto, independientemente de los valores ingresados.
