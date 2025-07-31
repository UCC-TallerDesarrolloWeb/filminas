---
title: Aplicaciones Web
theme: league
slideNumber: true
---

# Aplicaciones Web
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
<!-- .slide: style="font-size: 0.80em" -->
## Temario
<div class="grid-container2">
<div class="grid-item">

### Aplicaciones web
* Definición
* Ejemplos
* Aplicación web vs. página web
* Ventajas
* Tipo de acceso
* Estructura

</div>
<div class="grid-item">

### Página web
* Estátitca vs Dinámica
* Procesamiento
* Servidor
* Evolución de la web

## Programación
* Lenguajes de programación
* Características de HTML
</div>
</div>


---
## Libros:
![Book](images/book.png)
“Aplicaciones Web” de Javier Zofio Jiménez
(Unidad Teórica N°1 y N°2)

---
## Aplicaciones Web
Software almacenado en una computadora o servidor web, que los usuarios pueden utilizar a través de Internet o
de una Intranet, con un navegador web, para obtener los servicios que ofrezca.

---
## Ejemplos de Aplicaciones Web
* [Web Mails](https://www.gmail.com)
* [Wikis](https://www.wikipedia.com)
* [Tiendas en Línea](https://github.myshopify.com/)
* [Ofimática](https://docs.google.com)
* [Dibujo](https://sketch.io/sketchpad/)
* [Juegos Online](http://browserquest.mozilla.org/)
* Otros Sistemas de Gestión, Diseño, Cálculo, etc)

---
## Aplicación web vs. Página web
Una **página web** es un documento estático al que se accede a través de un navegador (la información sólo se puede leer, no interactuar con ella).

Una **aplicación web** es una página web especial, que tiene información sobre la que se puede interactuar e incluso cambiar.

---
## Ventajas de las Aplicaciones Webs
* Facilidad de acceso (sólo se necesita navegador web)
* Independencia de sistema operativo
* Utilizable desde cualquier plataforma (celular, tablet, PC)
* Facilidad de actualización y mantenimiento (sin redistribuir o instalar software)
* Bajo consumo de recursos

---
## Tipos de Aplicaciones Web
Según el tipo de acceso:
* **Públicas:** Tiendas virtuales, diarios digitales, portales de internet, etc.
* **Restringidas:** Intranets, que ofrecen servicios para mejorar gestiones internas de una empresa (control hs de personal, gestión de proyectos o tareas), etc.

---
## Estructura de Aplicaciones Webs
Normalmente posee 3 capas:
* Capa del Cliente
* Capa Intermedia
* Capa de Servidor

![3 Capas](images/appWeb/modelo3capas.png)

---
## Estructura
* Capa de Presentación, de Usuario/Cliente
<p class="fragment"> <small> 
front-end que es el responsable de proporcionar la lógica de presentación. También es conocida como interfaz gráfica.
</small> </p>
* Capa del Servidor Web o del Negocio o Intermedia
<p class="fragment"> <small> 
es donde residen los programas que se ejecutan, se reciben las peticiones del usuario y se envían las respuestas tras 
el proceso. Aquí es donde se establecen todas las reglas que deben cumplirse. Esta capa se comunica con la capa de 
presentación, para recibir las solicitudes y presentar los resultados, y con la capa de datos, para solicitar al gestor 
de base de datos almacenar o recuperar datos de él. 
</small> </p>
* Capa del Servidor de BD
<p class="fragment"> <small> 
 es donde residen los datos y es la encargada de acceder a los mismos. Está formada por uno o más gestores de bases de 
 datos que realizan todo el almacenamiento de datos, reciben solicitudes de almacenamiento o recuperación de información 
 desde la capa de negocio.
</small> </p>

---
## Tipos de Páginas web
Una **aplicación Web** es un conjunto de páginas Web estáticas y dinámicas.

* **Web Estática:** No cambia cuando un usuario la solicita.
    El servidor Web envía la página al navegador Web solicitante sin modificarla.

* **Web Dinámica:** Contiene elementos que permiten la comunicación activa entre el usuario y la
    aplicación, y cuyo contenido se genera a partir de lo que el usuario introduce.

<!--https://helpx.adobe.com/es/dreamweaver/using/web-applications.html-->

---
## Procesamiento Web Estática

![Web Estatica](images/appWeb/procesamiento_webEstatica.png)

<small> 
1. El navegador Web solicita la página estática. <br>
2. El servidor localiza la página. <br>
3. El servidor Web envía la página al navegador solicitante.
</small>

---
## Procesamiento Web Dinámica

![Web Dinamica](images/appWeb/procesamiento_webDinamica.png)

<small>
1. El navegador web solicita la página dinámica.
2. El servidor web localiza la página y la envía al servidor de aplicaciones.
3. El servidor de aplicaciones busca instrucciones en la página y la termina.
4. El servidor de aplicaciones pasa la página terminada al servidor web.
5. El servidor web envía la página finalizada al navegador solicitante.  
</small>

---
## Procesamiento Web Dinámica+DB

![Web Completo](images/appWeb/procesamiento_webCompleto.png)

---
## Procesamiento Web Dinámica+DB
<!-- .slide: style="font-size: 0.7em" -->
1. El navegador web solicita la página dinámica. 
2. El servidor web localiza la página y la envía al servidor de aplicaciones. 
3. El servidor de aplicaciones busca instrucciones en la página. 
4. El servidor de aplicaciones envía la consulta al controlador de la base de datos. 
5. El controlador ejecuta la consulta en la base de datos. 
6. El juego de registros se devuelve al controlador. 
7. El controlador pasa el juego de registros al servidor de aplicaciones. 
8. El servidor de aplicaciones inserta los datos en una página y luego pasa la página al servidor web. 
9. El servidor Web envía la página finalizada al navegador solicitante.  

---
## Servidor de Aplicaciones
Software que ayuda al servidor Web a procesar las páginas que contienen scripts o etiquetas del lado del servidor. Cuando se solicita al servidor una página de este tipo, el servidor Web pasa la página al servidor de aplicaciones para su procesamiento antes de enviarla al navegador.

---
## Evolución de la Web
* Web 1.0
* Web 2.0
* Web 3.0
* Web 4.0

---
## Web 1.0
El comienzo de la web data de los años 90, donde el usuario es un mero consumidor del contenido que es subido a 
servidores por parte de expertos informáticos. Los navegadores eran solo de texto.

La web 1.0 mejora con la aparición del lenguaje HTML, que proporciona contenido con mejor estructuras y más atractivos 
para leer. Aun así, el usuario aún no podía interactuar y la web era como una especie de libro donde buscar y leer información.

---
## Web 1.0
![Web 1.0](images/appWeb/web1_0.webp)

---
## Web 2.0
A partir del año 2001, surge un cambio importante: el usuario empieza a interactuar con las webs. 
Se siguen tres principios :
* La web como plataforma.
* La inteligencia colectiva.
* La arquitectura de participación.

Aparecen grupos de usuarios, redes sociales, blogs y wikis entre otras. Se fomenta la colaboración entre usuarios. 
El usuario ahora no solo accede a la información, sino que la crea.

---
## Web 2.0
![Web 2.0](images/appWeb/web2_0.webp)

---
## Web 3.0
Surge en 2006 para relacionar las webs de forma semántica, lo que permite que la información pueda ser encontrada de 
forma más rápida y eficiente debido a su estructuración.

Además de navegadores, se accede desde otros dispositivos y tecnologías.

---
## Web 3.0
![Web 3.0](images/appWeb/web3_0.webp)

---
## Web 4.0
En esta etapa la inteligencia artificial aparece como principal tecnología.
 
Algunas de las características de la web 4.0 son:
* Comprensión del lenguaje cotidiano o natural. (comandos de voz ej “llama a un contacto” )
* Comunicación entre dispositivos (m2m, máquina a máquina).
* Uso de información relacionada (GPS, sensores de temperatura, etc.).
* Nuevas formas de interacción con el usuario.

---
## Evolución Web
![Evolución Web](images/appWeb/webEvolution.png)

---
## Lenguajes de Programación Web
* HTML (HyperText Markup Language)
* JavaScript
* Python
* PHP (Hypertext Pre-processor)
* ASP (Active Server Pages)
* ASP.Net
* JSP (Java Server Pages)
* Ruby

---
## Elige tu Propia Aventura xD
<!-- .slide: style="font-size: 0.75em" -->
* **Programador de Servidores o Back-end:** Python, Ruby, PHP, Java, .Net (o JavaScript con nodeJS).
    Conocimientos de bases de datos y de administración de sistemas.

* **Programador de clientes o Front-end:** HTML, CSS, Javascript. Conocimientos de diseño.
* **Programador móvil:** Objective C, Swift, Java (para Android). HTML/CSS para sitios web móviles.
    Conocimientos sobre servidores.

* **Programador 3D o de videojuegos:** C/C++, OpenGL, Animación. Conocimientos de diseño y artísticos.
* **Programador de alto rendimiento:** C/ C++, Java, conocimientos en matemáticas y análisis cuantitativo.

---
##  El mejor lenguaje de programación para empezar depende del tipo de proyectos que se quiera hacer.

---
## Para programación web recomendamos...

![HTML5 JS CSS](images/appWeb/html5jscss.png)

---
## HTML5
HTML5 es la última evolución de la norma que define HTML (HyperText Markup Language)

---
## Características
![HTML5 Areas](images/appWeb/html5-areas.png)

---
## Características
<!-- .slide: style="font-size: 0.90em" -->
* ***Semántica:***
  lo que le permite describir con mayor precisión cuál es su contenido.

* ***Conectividad:***
  lo que le permite comunicarse con el servidor de formas nuevas e innovadoras.

* ***Desconectado y almacenamiento:***
  permite a páginas web almacenar datos, localmente, en el lado del cliente y operar fuera de línea de manera más eficiente.

* ***Multimedia:***
  permite hacer vídeo y audio en la Web abierta.

---
## Características
<!-- .slide: style="font-size: 0.90em" -->
* ***Gráficos y efectos 2D/3D:***
  permite una gama mucho más amplia de opciones de presentación.
    
* ***Rendimiento e Integración:***
  proporcionar una mayor optimización de la velocidad y un mejor uso del hardware del equipo.
    
* ***Dispositivo de Acceso:***
  admite el uso de varios dispositivos de entrada y salida.
    
* ***Styling:***
  deja a los autores escribir temas más sofisticados.
  
---
## SEMÁNTICA
````html
<section>
<article>
<nav>
<header>
<footer>
<aside>
````

---
## SEMÁNTICA
### Formularios
````html
<mark>
<figure>
<figcaption>
<data>
<time>
<output>
<progress>
<progress max="100" value="50"></progress>
````

---
![App Web](images/appWeb/tags.png)

---
## ¿Dudas, Preguntas, Comentarios?
![DUDAS](images/pregunta.gif)
