# ProgramacionWebDesdeCero

## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Introduccion](#paso-1-introduccion)
4. [Idea inicial](#paso-2-idea-inicial)
5. [Intorduccion a HTML 5](#paso-3-intorduccion-a-html-5)
6. [Manipulando HTML](#paso-4-manipulando-html)
7. [Intorduccion a CSS](#paso-5-css)

***

### General Info
Programacion Web Desde Cero (HTML, CSS, Js) - 2023
***
### Screenshot

***
### Technologies
List of technologies used within the project:
* [HTML]: Version HTML 5
* [CSS]: Version CSS3
* [JavaScrpt]: Version ES9
***

### Paso #1: Introduccion

Vamos a utilizar Visual Studio Code como editor de código.

[1]: https://code.visualstudio.com/

### Los requisitos mínimos para instalar Visual Studio Code son:

Requisitos:
------------------
1. 1.6 GHz de procesador, o más
2. 8 GB de RAM
3. Windows 10 u 11 (32-bit y 64-bit)
4. macOS - con la nueva versión de seguridad de Apple instalada 
5. Linux (Debian): Ubuntu Desktop 16.04, Debian 9
6. Linux (Red Hat): Red Hat Enterprise Linux 7, CentOS 7, Fedora 34

***

### Paso #2: Idea inicial

Piensa en una idea que deseas plasmar en un pagina web.

***

### Paso #3: Intorduccion a HTML 5

Crea un archivo index.html y genera la estructura básica de un documento HTML dentro del mismo. Esto significa que debe incluir las etiquetas:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Título del sitio Web</title>
    </head>
    <body>
    </body>
</html>
```

***

### Paso #4: Manipulando HTML!

![Html Semantico](PortafolioWebJEHM/media/recursos/htmlSemantico.png)

La estructura HTML permite definir paginas web que sean mas legibles:

![Estructura HTML](PortafolioWebJEHM/media/recursos/estructuraHTML.png)

***

### Paso 5: CSS
¡Introducción a las hojas de estilo!

Permite cargar los estilo de la pagina Web.

### Selectores:

| Tipos de selectores| Descripcion Selectores|
| :-------- | --------:|
| ID | Identificador Unico de un elemento |
| Clase | Composicion de estilos sobre un elemento HTML y compartido |

#### Selector por ID:

Se utiliza para referenciar a aquellos atributos que esten marcados con el ID:

```HTML
<p id="header"> Hola Mundo </p>
```
```CSS
#header {
   background-color: rgb(230, 230, 230);
}
```
#### Selector por clase:

Se utiliza para referenciar las clases de los componentes que esten marcados con la clase:

```HTML
<p class="header"> Hola Mundo </p>
```
```CSS
.header {
    background-color: rgb(230, 230, 230);
}
```