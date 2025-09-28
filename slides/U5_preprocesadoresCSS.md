---
title: PreProcesadoresCSS
theme: league
slideNumber: true
---

# Pre Procesadores CSS
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

- Framework en CSS
- Ventajas y Desventajas
- Bootstrap
- Ejercicios Bootstrap
- TailwindCSS

</div>
<div class="grid-item">

- Preprocesadores CSS
- Ventajas y Desventajas
- Ejercicios SASS

</div>
</div>

---

### Frameworks CSS

Los frameworks CSS proporcionan un conjunto de estilos, componentes y utilidades predefinidas que permiten crear interfaces modernas de manera rápida y consistente. 

- Bootstrap
- TailwindCSS

Con ellos, los desarrolladores pueden enfocarse más en la funcionalidad y menos en la escritura repetitiva de estilos desde cero.

---

### Ventajas y desventajas de los frameworks CSS
<!-- .slide: style="font-size: 0.80em" -->
Ventajas:
- Aceleran el desarrollo inicial.
- Aseguran consistencia visual.
- Ofrecen componentes listos para usar.
- Amplia comunidad y documentación.

Desventajas:
- Código extra (estilos que no siempre se usan → CSS bloat).
- Sitios que lucen demasiado similares si no se personalizan.
- Curva de aprendizaje (en especial en Tailwind).

---

### [Bootstrap](https://getbootstrap.com/)
Es uno de los frameworks más utilizados, ofrece un sistema de rejilla (grid system), componentes listos para usar (botones, formularios, menús) y utilidades que facilitan el diseño responsivo.

---

### Ejercicio: Instagram
Empleando Ejercicios-CSS el template ej_instagram, el contenido debe visualizarse:
- Se deben mostrar 3 columnas las imagenes si la pantalla es mediana
- Se debe mostrar 1 columna si la pantalla es pequeña
- Las imagenes deben ocupar el 100% de su columna

---

### [TailwindCSS](https://tailwindcss.com/)
Está basado en clases utilitarias, permite aplicar estilos directamente en el HTML de forma modular y altamente personalizable, lo que fomenta un flujo de trabajo ágil y flexible.

---

## Preprocesadores CSS

El CSS juega un papel central para definir la presentación y la experiencia visual de una página.

A medida que los proyectos se vuelven más complejos, mantener y escalar el código CSS puede resultar difícil. 

Para afrontar este desafío surgieron herramientas que **optimizan** y **aceleran** el trabajo con estilos, entre ellas los frameworks CSS y los preprocesadores CSS.
---

### Ventajas y desventajas de los preprocesadores
<!-- .slide: style="font-size: 0.80em" -->
Ventajas:
- CSS más organizado y mantenible.
- Reutilización de estilos (mixins, funciones).
- Permite trabajar con variables antes de que fueran estándar en CSS.

Desventajas:
- Necesitan un paso de compilación (no se interpretan directo en el navegador).
- Agregan complejidad al flujo de trabajo.
- Algunas funciones ya fueron incorporadas en CSS moderno (ej. variables nativas --var).

---

### Preprocesadores CSS

<!-- .slide: style="font-size: 0.80em" -->
Los preprocesadores CSS como [SASS](https://sass-lang.com/) y [LESS](https://lesscss.org/) extienden las capacidades nativas de CSS, añadiendo características propias de lenguajes de programación, tales como:
- Variables para colores, fuentes o medidas.
- Anidamiento de reglas para mejorar la legibilidad.
- Mixins y funciones para reutilizar bloques de estilo.
- Herencia y modularización que permiten mantener el código más limpio y organizado.

Estos archivos se escriben en sintaxis SASS o LESS y luego se compilan a CSS estándar para ser interpretados por los navegadores.

---

## ¿Qué es Sass?

Sass (**Syntactically Awesome Stylesheets**) es un **preprocesador CSS** que extiende el lenguaje con:
- Variables
- Anidación
- Mixins y funciones
- Módulos reutilizables (`@use` / `@forward`)

Al final, **Sass se compila en CSS estándar** que entiende cualquier navegador.

---

### Variables

Permiten **almacenar valores** (colores, tamaños, tipografías) para reutilizarlos.

```scss
$color-principal: #3498db;
$padding-base: 16px;

body {
  background: $color-principal;
  padding: $padding-base;
}
```

---

### Mixins

Un mixin agrupa reglas CSS reutilizables.

Se pueden parametrizar para mayor flexibilidad.

```scss
@mixin boton($color, $radius: 4px) {
  background: $color;
  border-radius: $radius;
  padding: 8px 12px;
  color: white;
}
```

---

### Include

Para usar un mixin, se lo invoca con @include.
```scss
.btn-primario {
  @include boton(#3498db, 8px);
}

.btn-secundario {
  @include boton(#2ecc71);
}
```

Evita duplicar código y mejora la mantenibilidad.

---

### Módulos con @use

Sass recomienda organizar el código en módulos.

@use importa un archivo Sass y le asigna un namespace.

```scss
// _variables.scss
$color-fondo: #f4f4f4;

// estilos.scss
@use 'variables';

body {
  background: variables.$color-fondo;
}
```

@use reemplaza a @import (deprecado) y evita conflictos de nombres.

---

### Ejercicio
1. Instala [NodeJs](https://nodejs.org/en) o asegurate de tenerlo instalado `node --version` y `npm --version`
2. Instala sass `npm install -g sass` y verica `sass --version`
3. Crea un archivo **styles.scss**
4. Ejecuta **sass --watch styles.scss styles.css** en la consola del proyecto

---
## ¿Dudas, Preguntas, Comentarios?
![DUDAS](images/pregunta.gif)
