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

- Ciclo de vida de una página web
- Eventos del Ciclo de Vida
- Optimización
- DevTools

</div>
<div class="grid-item">


</div>
</div>

---

## Ciclo de Vida de una Página Web

1. Ingreso de la URL y resolución DNS
2. Conexión TCP/TLS
3. Solicitud HTTP/HTTPS
4. Respuesta del servidor
5. Parseo y construcción del DOM y CSSOM
6. Generación del Render Tree
7. Layout (Reflow)
8. Pintado (Painting)
9. Composición (Compositing)
10. Interacción y ciclo dinámico

----

### 1. Ingreso de la URL y resolución DNS

El ciclo comienza cuando el usuario escribe una URL en el navegador o hace clic en un enlace.
- El navegador consulta al DNS (Domain Name System) para traducir el nombre de dominio (ej: www.ejemplo.com) en una dirección IP.
- Con la dirección IP, puede ubicar el servidor que aloja el sitio.

----

### 2. Conexión TCP/TLS
- El navegador abre una conexión TCP con el servidor.
- Si la conexión es HTTPS, ocurre el handshake TLS:
    - Intercambio de certificados.
    - Negociación de claves de cifrado.
    - Establecimiento de un canal seguro.

----

### 3. Solicitud HTTP/HTTPS

Una vez establecida la conexión, el navegador envía una solicitud HTTP o HTTPS al servidor correspondiente. Esta solicitud puede incluir cabeceras, cookies o tokens que identifican al cliente.

----

### 4. Respuesta del servidor

El servidor procesa la petición y responde con un código de estado HTTP y los recursos solicitados, que incluyen:
- El documento HTML principal.
- Archivos adicionales: CSS, JavaScript, imágenes, fuentes, videos, etc.

----

### 5. Parseo y construcción del DOM y CSSOM

Una vez recibido el HTML, el navegador lo interpreta paso a paso:
- Construye el DOM (Document Object Model), que es una representación en memoria de la estructura del documento HTML.
- Descarga y procesa los archivos CSS para crear el CSSOM (CSS Object Model).
- Si encuentra un `<script>` bloqueante, puede pausar el parseo hasta que lo ejecute.

----

### 6. Generación del Render Tree

El DOM y el CSSOM se combinan para formar el árbol de renderizado (Render Tree), que contiene la información de qué elementos deben mostrarse y cómo deben hacerlo.

----

### 7. Layout (Reflow)

El navegador calcula la posición y tamaño exactos de cada elemento en la página (layout). Aquí se determinan dimensiones, márgenes, alineaciones y relaciones entre los elementos.

----

### 8. Pintado (Painting)

Con el layout definido, el navegador pinta los píxeles en la pantalla, aplicando colores, bordes, imágenes y tipografías.

----

### 9. Composición (Compositing)

En esta etapa final, el navegador organiza las capas de la página (ej. un menú fijo sobre el contenido, una animación, etc.) y las combina en la pantalla del usuario.

----

### 10. Interacción y ciclo dinámico

Una vez renderizada la página, comienza la interacción con el usuario:
- El JavaScript puede modificar el DOM, hacer nuevas solicitudes (AJAX, fetch) o generar cambios dinámicos.
- Esto puede disparar nuevamente procesos de layout, paint o incluso compositing parcial.

---

### Eventos clave del ciclo de vida

- **DOMContentLoaded:** el DOM está construido (sin esperar imágenes o estilos).
- **load:** se cargaron todos los recursos.
- **beforeunload / unload:** cuando se abandona la página.

---

### Optimización (performance)

- El **Reflow** es costoso. Cambios en dimensiones disparan recalculados completos.
- El **Repaint** es menos costoso, solo cambia lo visual (ej. color).
- El **Compositing** puede mover capas sin recalcular layout ni repintar.

Usar técnicas como:
- will-change, transform y opacity para animaciones.
- Scripts con defer/async para no bloquear el parseo.
- Minimizar CSS y JS innecesario.

---

### DevTools

Son un conjunto de herramientas para desarrolladores web que están integradas directamente en el navegador. Esto permite editar páginas renderizadas y diagnosticar problemas con rapidez, lo que te ayuda a crear mejores sitios web en menos tiempo.

---

### Dev Tools
<!-- .slide: style="font-size: 0.80em" -->
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
