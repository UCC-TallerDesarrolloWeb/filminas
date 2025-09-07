---
title: Proyecto
theme: league
slideNumber: true
---

# Proyecto
Created by <i class="fab fa-telegram"></i> 
[edme88]("https://t.me/edme88")

---

<style>
.grid-container2 {
    display: grid;
    grid-template-columns: auto auto;
    font-size: 0.8em;
    text-align: left !important;
}

.grid-item {
    border: 3px solid rgba(121, 177, 217, 0.8);
    padding: 20px;
    text-align: left !important;
}
</style>
<!-- .slide: style="font-size: 0.70em" -->
## Temario
<div class="grid-container2">
<div class="grid-item">

### Proyecto
* Consigna básica
* Link con template base (obligatorio)

### Requisitos del Primer Parcial
* [Sketch](Proyecto.html#/4)
* [Wireframe/Mockup](Proyecto.html#/8)
* [Repositorio](Proyecto.html#/9)
* [Proyecto general](Proyecto.html#/10)
* [HTML](Proyecto.html#/11)
* [Imágenes](Proyecto.html#/14)
* [CSS](Proyecto.html#/15)
* [Accesibilidad](Proyecto.html#/16)
* [JavaScript](Proyecto.html#/17)
* [Documentación](Proyecto.html#/19)
* [Tetsing](Proyecto.html#/20)
* [Correcciones](Proyecto.html#/21)
* [¿Cómo comenzar?](Proyecto.html#/25)

</div>
<div class="grid-item">

### Requisitos del Segundo Parcial
* [React](Proyecto.html#/30)
* [Proyecto General](Proyecto.html#/33)
* [Correcciones](Proyecto.html#/34)

### Requisitos del Final
* [Proyecto General](Proyecto.html#/37)

</div>
</div>

---
## PROYECTO
    
Relizar un proyecto Web de cualquier temática, que cumpla con los requisitos.
* User Interface (HTML5 y CSS3)
* Funcionalidad (Javascript)
* Campos para realizar algún cálculo
* Uso de React

---

## Github Classroom: Proyecto Integrador
[Primer Parcial 2025](https://classroom.github.com/a/OGkZvRfV)

---
### Requisitos del Primer Parcial
#### Sobre el [Sketch](U2_prototipado.html#/20)
<!-- .slide: style="font-size: 0.80em" -->
- [ ] Versión Desktop y Mobile
- [ ] Guardado en formato PNG, JPG ó PDF
- [ ] Dentro de una carpeta llamada "Sketch"
- [ ] Tener en cuenta los mensajes de error para el usuario
- [ ] Debe ser realizado como el template (siguiente diapositiva)

---
### Requisitos del Primer Parcial
#### Sobre el Sketch
![Sketch Móvil](images/proyecto/GTP_sketchMovil.jpg)

---
### Requisitos del Primer Parcial
#### Sobre el Sketch
![Sketch Móvil](images/proyecto/GTP_sketchDesktop.jpg)

---
### Requisitos del Primer Parcial
#### Sobre el Sketch
Tener en cuenta
* ¿Qué opciones debe ofrecer al usuario?
* ¿Qué campos hay para ingresar datos?
* Benchmarking: Investigar sistemas similares
* ¿Qué acciones le permiten al usuario realizar?
* Mensajes de Error

---
### Requisitos del Primer Parcial
#### Sobre el [Wireframe/Mockup](U2_prototipado.html#/26)
<!-- .slide: style="font-size: 0.80em" -->
- [ ] Dibujado con algún programa como: Figma, AdobeXD, Canvas, Draw.io en Drive, Pencil Project, Mockups, NinjaMock, o similares.
- [ ] Diseño de Mensajes de error para el usuario
- [ ] Versión Desktop y Mobile
- [ ] Guardado en formato PNG, JPG ó PDF
- [ ] Dentro de una carpeta llamada "Wireframe" ó "Mockup"

---
### Requisitos del Primer Parcial
#### Sobre el repositorio
<!-- .slide: style="font-size: 0.60em" -->
- [ ] El proyecto debe estar subido al repositorio adecuado "Proyecto2025-ApellidoAlumno1-ApellidoAlumno2" (en gitHub Classroom)
- [ ] Modificar el Readme.MD y colocar información del proyecto/página (mínimamente: título del proyecto, autores, link de gh-pages, contenido de la página,  listado de tecnologías usadas, etc)
- [ ] En el **readme.md** se debe emplear [Markdown](U1_git_avanzado.html#/13) y aplicar negrita, titulo de orden 1, 2 y 3, link, items, tabla, index a cada sección
- [ ] El código debe estar en **gitHubPages** (emplear gh-pages o configurar github para que se tome a la main como la [página a visualizar](Proyecto.html#/24))
- [ ] En caso de haber múltiples branchs, NO debe haber diferencias entre **main/master** y **gh-pages** (verificar de realizar el Merge).
- [ ] Publicar la Web empleando [GitHubPages](Proyecto.html#/24)
- [ ] El repositorio no debe contener archivos innecesarios (no debe contener .idea o .vsc o .DS_Store o node_modules, en todo caso emplear **.gitignore**)

---
### Requisitos del Primer Parcial
#### Sobre el proyecto general
<!-- .slide: style="font-size: 0.60em" -->
- [ ] NO está permitido descargar un TEMPLATE (diseño 100% desde cero)
- [ ] La página principal debe llamarse index
- [ ] La estructura del proyecto debe ser adecuada (crear una carpeta para las imágenes, otra para los sketch/mockups). En un segunda etapa, al emplear react, carpetas: components, pages, styles.
- [ ] Identar correctamente el código (en Webstorm con Ctrol+A se selecciona todo el código y con Ctrl+Alt+L ó menú *Code* > *Reformat Code*)
- [ ] No debe haber errores presentes (en Webstorm *Code* > *Inspect Code* para verificar que no haya errores)
- [ ] Se debe emplear [favicon](U2_CSS.html#/34)
- [ ] Emplear alguna fuente de [google fonts](U2_CSS.html#/35) o subir al proyecto alguna fuente externa (aunque sea para un título)
- [ ] Debe haber navegación entre todas las páginas
- [ ] No debe haber errores de ortografía en el contenido visual
- [ ] "Lorem ipsum" es sólo válido para los prototipos, NO para la página

---
### Requisitos del Primer Parcial
#### Sobre el HTML (1)
<!-- .slide: style="font-size: 0.60em" -->
- [ ] Todas las etiquetas deben estar en minúscula
- [ ] Poner comillas a todos los atributos
- [ ] **Title** debe contener el título de la página
- [ ] En el ```<head></head>``` incluir las etiquetas ```<meta>``` detallando: [autor, descripción y palabras clave](U2_HTML.html#/6)
- [ ] Emplear al menos 3 [etiquetas semánticas](U2_HTML.html#/11) diferentes (header, nav, aside, main, section, article, footer)
- [ ] Emplear ```<header></header>```. En el contenido de la cabecera debe haber un título ```<h1></h1>```, puede tener color de fondo, algún logotipo, etc.
- [ ] La estructura de la página debe estar definida con ```<div></div>```

---
### Requisitos del Primer Parcial
#### Sobre el HTML (2)
<!-- .slide: style="font-size: 0.80em" -->
- [ ] Debe contener al menos 3 [elementos](U2_HTML_avanzado.html#/5) de tipo ```<input>``` o ```<select>``` o ```<button>``` que le permitan al usuario ingresar valores para poder realizar un cálculo de un ejercicio o seleccionar opciones o llamar a una función.
- [ ] Emplear el atributo [**placeholder**](U2_HTML_avanzado.html#/19) (mínimamente en 1 input)
- [ ] Emplear el atributo **size** para que el tamaño de los inputs sea prolijo
- [ ] Emplear el atributo **maxlength** para que el usurario no pueda ingresar valores "muy grandes"

---

### Requisitos del Primer Parcial
#### Sobre el HTML (3)

<!-- .slide: style="font-size: 0.70em" -->

- [ ] No espaciar con excesivos ```<br>```. Utilizar márgenes, paddings, etc.
- [ ] La [anidación de etiquetas](U2_HTML.html#/11) HTML debe ser correcta.
- [ ] No utilizar etiquetas deprecadas.

![TAG Deprecadas](images/proyecto/deprecated_tag.png)

- [ ] Todas las etiquetas que correspondan deben estar correctamente cerradas
- [ ] Los ids de los elementos deben ser unívocos

---
<!-- .slide: style="font-size: 0.80em" -->
### Requisitos del Primer Parcial
#### Sobre las imágenes
- [ ] Debe contener por lo menos una etiqueta ```<img>``` en la página.
- [ ] Todas las imágenes deben ser incluidas en el repositorio dentro de una carpeta llamada **imagenes** (salvo que sean demasiado pesadas. En ese caso, se puede emplear un servidor externo).
- [ ] No se deben subir videos en el repositorio (excepto que sean MUY livianos).
- [ ] Toda imagen debe tener su atributo alt
- [ ] Las imágenes deben poseer un nombre representativo 

---
<!-- .slide: style="font-size: 0.80em" -->
### Requisitos del Primer Parcial
#### Sobre el CSS
- [ ] El estilo de los elementos debe establecerse en un archivo CSS (prohibido poner el atributo style a los elementos o emplear estilos incrustados).
- [ ] El CSS debe contar mínimo con un tipo de cada forma (por Tag, por ID y por clase).
- [ ] Se debe emplear pseudoclase
- [ ] No emplear ```!important```
- [ ] El diseño de la página debe ser consistente
- [ ] Debe existir un único archivo CSS (se debe evitar código duplicado. Se debe aplicar re-utilización de código/estilos)

---
### Requisitos del Primer Parcial
#### Sobre Accesibilidad
- [ ] Toda imagen debe tener su atributo alt
- [ ] Todo ```<input>``` o ```<select>``` debe tener su ```<label>```
- [ ] Los labels deben contener el atributo **for** (el for debe contener el id del input al cual se referencia) 
- [ ] Si hay una tabla en la página, debe contener ```<caption></caption>```

---
### Requisitos del Segundo Parcial
#### Sobre la funcionalidad JavaScript (1)
<!-- .slide: style="font-size: 0.75em" -->
Se debe agregar funcionalidad Js a la página HTML+CSS desarrollada</p>
- [ ] Una función que compruebe si los valores ingresados son correctos, y si no lo son, que le indique al usuario por un alert o dialog, y que blanquee el contenido del campo.
- [ ] Una función que calcule/muestre algo en base a los valores ingresados por el usuario en los inputs.
- [ ] El código Js debe estar en un archivo externo
- [ ] Se debe emplear var, let o const según corresponda para mayor eficiencia

---
### Requisitos del Segundo Parcial
#### Sobre la funcionalidad JavaScript (2)
- [ ] No deben existir funciones innecesarias que no se llamen en ninguna sección del código
- [ ] Las funciones deben estar escritas cómo **función flecha**
- [ ] No debe haber errores JavaScript presentes (F12 > Consola)
- [ ] El funcionamiento de la página debe ser consistente.

---
### Requisitos del Segundo Parcial
#### Sobre la documentación
- [ ] **TODAS** las funciones javaScript deben estar comentadas adecuadamente. [JsDoc](https://jsdoc.app/about-getting-started.html)
````javascript
/**
 * Descripción de que hace la función
 * @method Nombre de la función
 * @param {string} ParámetroA - Explicación de que valor almacena ParámetroA
 * @param {number} ParámetroB - Explicación de que valor almacena ParámetroB
 * @return Valor que retorna
 */
````

---

### Testing 
<!-- .slide: style="font-size: 0.90em" -->
Es sumamente IMPORTANTE probar el funcionamiento de la página con diferentes valores. 
- ¿Qué pasa si presiono calcular sin ingresar nada?
- ¿Y si ingreso solo algunos campos? 
- ¿Y si ingreso todo cero?
- ¿Y si ingreso letras?
- ¿Y si ingreso números negativos?
- ¿Si vacío el carrito de compras?
- ¿Si recargo la página?

Prueba todas las situaciones posibles, no te quedes solo con el **happy path**.

---
### Requisitos del Primer Parcial
#### Sobre las Correcciones
- [ ] Se corregirá el proyecto con el último commit realizado en Github hasta las 23:59 del día anterior a la fecha de entrega
- [ ] Las notas serán de la siguiente manera: (Por ejemplo 55% 4; 59% 5; 67% 6; 75% 7; 82% 8; 89% 9; 97% 10)

---
### Requisitos del Primer Parcial
#### Sobre las Correcciones
- [ ] Todas los errores o la falta de cumplimiento de los requisitos serán reportados a través de la plataforma de GitHub, en la pestaña de ISSUES
![Issues en GitHub](images/correcciones.jpg)

---
### Requisitos del Primer Parcial
#### Sobre las Correcciones
| Items a Evaluar    | %   |
|--------------------|-----|
| Prototipo en papel | 7%  |
| Prototipo Mockup   | 8%  |
| HTML+CSS+Js        | 85% |

Por cada corrección o defecto en el HTML+CSS+Js se descontará un 5% del 85%.

---
#### Como quiere sentirse la Profe al corregir el proyecto
![Over nine thousands](images/proyecto/over9thousand.jpg)

---
## Proyecto - Parte 1
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iay1jxKGqQI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
## Proyecto - Parte 2
<iframe width="560" height="315" src="https://www.youtube.com/embed/p1-5tzJb6CU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
## Proyecto - Parte 3
<iframe width="560" height="315" src="https://www.youtube.com/embed/nMPTkLKy1gg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
### Proyecto: Configuración de Github Pages
<iframe width="560" height="315" src="https://www.youtube.com/embed/aChzT06VBok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

# Proyecto
### Requisitos del Segundo Parcial

---

### Requisitos del Segundo Parcial
#### Sobre React (1)
- [ ] Se debe emplear **Vite** para instalar **React**
- [ ] Se debe emplear **Hooks**, useState, useEffect, useContext, useNavigate
- [ ] Se debe emplear **react-router-dom** para el enrutamiento a otras páginas
- [ ] Se debe emplear **outlet** para que un componente principal renderice componentes de rutas hijas.
- [ ] La estructura del proyecto (carpetas) debe ser el correcto: components, pages, styles
- [ ] Los **imports** deben ser usando con **alias**

---

### Requisitos del Segundo Parcial
#### Sobre React (2)
- [ ] Validaciones en tiempo real con onChange + mensajes de error accesibles.
- [ ] Crear al menos un componente genérico (ej: Button, Card, Input) y reutilizarlo en varias páginas.
- [ ] Guardar algún dato en localStorage (ej: preferencias de tema o un carrito de compras).

---

#### Sobre React (3)
- [ ] En caso de tener backend, emplear **fetch**
- [ ] En caso de no contar con un servicio que nos provea la información necesaria, la misma debe ser leída en formato tipo Json local y renderizar listas dinámicas. Ejemplo:
````javascript
const activities = [
  {
    nombre: "taekwondo",
    descripcion: "Arte marcial coreana",
    horarios: [
      { dia: 2, "hora-inicio": "18:30", "hora-fin": "20:00" },
      { dia: 4, "hora-inicio": "18:30", "hora-fin": "20:00" }
    ]
  },
  {
    nombre: "zumba",
    descripcion: "ritmos latinos",
    horarios: [
      { dia: 1, "hora-inicio": "19:30", "hora-fin": "20:30" },
      { dia: 3, "hora-inicio": "19:30", "hora-fin": "20:30" }
    ]
  }
];
````

---
### Requisitos del Segundo Parcial
#### Sobre el proyecto general
- [ ] Todas las correcciones y mejoras (sugerencias) solicitadas durante el primer parcial deben estar corregidas.
- [ ] No debe haber errores presentes en el código (realizar *Code* > *Inspect Code* para verificar que no haya errores)


---
### Requisitos del Segundo Parcial
#### Sobre las Correcciones
- [ ] Se corregirá el proyecto con el último commit realizado en Github hasta las 23:59 del día anterior a la fecha de entrega
- [ ] Las notas serán de la siguiente manera: (Por ejemplo 55% 4; 59% 5; 67% 6; 75% 7; 82% 8; 89% 9; 97% 10)
- Las sugerencias sobre el HTML, CSS y Js realizadas en el anterior parcial dejen ser corregidas.

---
### Requisitos del Segundo Parcial
#### Sobre las Correcciones

| Items a Evaluar | % |
|-----------------|---|
| Estructura del Proyecto | 10% |
| Navegación con react-router-dom | 15% |
| Uso correcto de Hooks | 20% |
| Renderizado dinámico de datos | 25% |
| Validaciones y mensajes de error | 10% |
| Consistencia del diseño y uso de estilos | 10% |
| Código limpio y sin errores en consola | 10% |

---

# Proyecto
### Requisitos del FINAL

---
### Requisitos del Final
#### Sobre el proyecto general
<!-- .slide: style="font-size: 0.80em" -->
- [ ] Todas las correcciones y mejoras solicitadas durante el primer y segundo parcial deben estar corregidas.
- [ ] No debe haber errores presentes en el código (realizar *Code* > *Inspect Code* para verificar que no haya errores)
- [ ] No debe haber errores JavaScript presentes (F12 > Consola)
- [ ] Debe cumplir con TODOS los requisitos del 1er y 2do Parcial (si se agrego código nuevo en Js, se debe documentar, si hay nuevos inputs de html deben contener su label, etc)
- [ ] El proyecto debe visualizarse correctamente en Desktop y Mobile
- [ ] Incluir al menos 5 tests con Jest + React Testing Library (ejemplo: que un botón renderice un texto esperado).