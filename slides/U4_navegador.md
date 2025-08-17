---
title: Navegador
theme: league
slideNumber: true
---

# Funcionamiento del Navegador
Created by <i class="fab fa-telegram"></i>
[edme88]("https://t.me/edme88")

---
<!-- .slide: style="font-size: 0.60em" -->
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
## Temario
<div class="grid-container2">
<div class="grid-item">

(en desarrollo)

</div>
<div class="grid-item">


</div>
</div>

---
## Ciclo de Vida de una Página Web

1. Ingreso de la URL y resolución DNS
2. Solicitud HTTP/HTTPS al servidor
3. Respuesta del servidor
4. Parseo y construcción del DOM y CSSOM
5. Generación del Render Tree
6. Layout (Reflow)
7. Pintado (Painting)
8. Composición (Compositing)
9. Interacción y ciclo dinámico

----

### 1. Ingreso de la URL y resolución DNS

El ciclo comienza cuando el usuario escribe una URL en el navegador o hace clic en un enlace.
- El navegador consulta al DNS (Domain Name System) para traducir el nombre de dominio (ej: www.ejemplo.com) en una dirección IP.
- Con la dirección IP, puede ubicar el servidor que aloja el sitio.

----

### 2. Solicitud HTTP/HTTPS al servidor

El navegador envía una solicitud HTTP o HTTPS al servidor correspondiente. Esta solicitud puede incluir cabeceras, cookies o tokens que identifican al cliente.

----

### 3. Respuesta del servidor

El servidor procesa la petición y responde con un código de estado HTTP y los recursos solicitados, que incluyen:
- El documento HTML principal.
- Archivos adicionales: CSS, JavaScript, imágenes, fuentes, videos, etc.

----

### 4. Parseo y construcción del DOM y CSSOM

Una vez recibido el HTML, el navegador lo interpreta paso a paso:
- Construye el DOM (Document Object Model), que es una representación en memoria de la estructura del documento HTML.
- Descarga y procesa los archivos CSS para crear el CSSOM (CSS Object Model).

----

### 5. Generación del Render Tree

El DOM y el CSSOM se combinan para formar el árbol de renderizado (Render Tree), que contiene la información de qué elementos deben mostrarse y cómo deben hacerlo.

----

### 6. Layout (Reflow)

El navegador calcula la posición y tamaño exactos de cada elemento en la página (layout). Aquí se determinan dimensiones, márgenes, alineaciones y relaciones entre los elementos.

----

### 7. Pintado (Painting)

Con el layout definido, el navegador pinta los píxeles en la pantalla, aplicando colores, bordes, imágenes y tipografías.

----

### 8. Composición (Compositing)

En esta etapa final, el navegador organiza las capas de la página (ej. un menú fijo sobre el contenido, una animación, etc.) y las combina en la pantalla del usuario.

----

### 9. Interacción y ciclo dinámico

Una vez renderizada la página, comienza la interacción con el usuario:
- El JavaScript puede modificar el DOM, hacer nuevas solicitudes (AJAX, fetch) o generar cambios dinámicos.
- Esto puede disparar nuevamente procesos de layout, paint o incluso compositing parcial.

---

### Dev Tools

- **Elements:** inspección y edición de HTML/CSS.
- **Console:** ejecución de JavaScript, visualización de logs y errores 
- **Sources:** depuración de JavaScript, puntos de interrupción (breakpoints), navegación entre archivos de código 
- **Network:** monitoreo de las solicitudes de red, tiempos de carga, recursos, etc. 
- **Performance:** análisis detallado del rendimiento (carga, interacciones, CPU, memoria, frames) 
- **Application:** gestión del almacenamiento local, IndexedDB, service workers, cachés 
- **Security:** verificación de seguridad, certificados, contenido mixto 
- **Otros paneles:** Lighthouse, Memory, Accessibility, CSS Overview y más

---

## [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)

Es un conjunto de herramientas incorporadas en el navegador que permiten editar páginas en tiempo real, diagnosticar problemas y optimizar el desarrollo web.

---
## ¿Dudas, Preguntas, Comentarios?
![DUDAS](images/pregunta.gif)
