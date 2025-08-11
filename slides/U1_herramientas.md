---
title: Herramientas de Desarrollo
theme: league
slideNumber: true
---

# Herramientas de Desarrollo
Created by <i class="fab fa-telegram"></i>
[edme88]("https://t.me/edme88")

---
<style>
.grid-container5 {
    display: grid;
    grid-template-columns: auto auto auto auto auto;
    font-size: 0.8em;
    text-align: left !important;
}

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
<!-- .slide: style="font-size: 0.60em" -->
## Temario
<div class="grid-container5">
<div class="grid-item">

### Herramientas de Desarrollo
* Definición
* Tipos de herramientas
</div>
<div class="grid-item">

### IDE
* Definición 
* Editor de código
* Construcción aut.
* Debugger
* Compilador
* Intérprete
* Ejemplos de IDEs
</div>
<div class="grid-item">

### VSC
* Definición
* Función
* Ventajas
* Ejemplo de herramientas
</div>
<div class="grid-item">

### Documentación
* Funcionalidad
* Nivel de documentación
* Recomendaciones


### Bug Tracker
* Definición
* Ejemplo de herramientas
* Recomendaciones
</div>
<div class="grid-item">

### Testing
* Pruebas de desempeño
* Ejemplo de herramientas

### Integración Continua
* Definición
* Ejemplo de herramientas
</div>
</div>

---
## Herramientas de Desarrollo

Conjunto de recursos que facilitan y agilizan el desarrollo, mantenimiento y prueba del software.

Acompañan al desarrollador desde la escritura del código hasta su despliegue y monitoreo.

Una aplicación o programa puede contar con múltiples herramientas que se encarguen de funciones específicas y afines para realizar una tarea.

---
## Tipos de Herramientas
* IDE
* Control de Versiones
* Bug Tracker
* Pruebas de desempeño, carga, stress
* Documentación
* Integración Continuo

![Herramientas](images/herramientas/herramientas.png)

---
## Ambiente de Desarrollo Integrado o IDE
Es un software que proporciona servicios integrales para facilitarle al programador el desarrollo de software.

Un IDE combina varias herramientas en una sola interfaz: editor, compilador, depurador y más. Esto mejora la productividad y reduce errores al centralizar el desarrollo.

---
## Ambiente de Desarrollo Integrado o IDE
Normalmente, un IDE consiste de:
* Editor de código fuente
* Herramientas de construcción automáticas
* Depurador o Debugger
* Compilador
* Intérprete

---
## Editor de código fuente
Es un "editor especializado" orientado para escribir código fuente de aplicaciones en general en lenguajes de programación.

Generalmente los editores de código soportan varios lenguajes y son capaces de abrir varios archivos a la vez, resaltar su sintaxis y ofrecer ayudas contextuales a la hora de escribir o visualizar el código de las aplicaciones.

---
## Depurador o Debugger
Permite probar y eliminar los errores del programa.

El depurador permite detener el programa en un punto determinado o en un momento determinado para que el usuario pueda 
examinar y modificar la memoria y las variables del programa, cambiar punto de ejecución, ejecutar una instrucción o 
partes determinadas de código.

---
## Depurador o Debugger
![Debuggin](images/herramientas/debugging.png)

---
## Compilador
Traduce del lenguaje de programación al lenguaje máquina, código intermedio o texto.

* **Lenguajes compilados:** C, C++, Go, Rust, Fortran, Pascal, Visual Basic.
* **Lenguajes interpretados:** Python, JavaScript, Ruby, PHP.

---
![Time Compilation](images/herramientas/time_compilation.jpg)

---
## Interprete
Realiza la traducción a medida que sea necesaria, instrucción por instrucción y no guardan el resultado de la traducción.

Los programas interpretados suelen ser más lentos que los compilados debido a la necesidad de traducir el programa 
mientras se ejecuta, pero son más flexibles permitiendo reemplazar partes del programa.

Uno de los entornos más comunes de uso de los intérpretes es en los navegadores web, debido a que se ejecutan independientemente de la plataforma.

---
<!-- .slide: data-background="images/herramientas/IDES.png" -->
## IDE's
Ejemplos de IDE's para desarrollo Web:
* [Cursor (The AI Code Editor)](https://cursor.com/)
* [JetBrains Web Storm](https://www.jetbrains.com/es-es/webstorm/download/#section=windows)
* [Microsoft Visual Studio Code](https://code.visualstudio.com/)
* [Sublime Text](https://www.sublimetext.com/)
* [Eclipse](https://www.eclipse.org/downloads/)
* [Net Beans](https://netbeans.apache.org/download/index.html)
* [Aptana](http://www.aptana.com/)
* [NotePad ++](https://notepad-plus-plus.org/downloads/)

---

### Extensiones o plugins

Los IDEs modernos permiten instalar extensiones que agregan soporte para nuevos lenguajes, linters, herramientas de testing, snippets, etc.

Ejemplos: Prettier, ESLint, Live Server (en VSCode)

---
<!-- .slide: data-background="images/herramientas/Busydesk-desarrollo.png" -->
## IDE's
No existe un IDE perfecto. El mejor será el que se adapte a tu flujo de trabajo, tus herramientas y tu nivel de experiencia.

---

### Actividad 1.1: Instalación de VSCode

1. Ingresa a https://code.visualstudio.com/
2. Descarga el instalador del **Visual Studio Code**
3. Instálalo!
4. Abrí VSCode y explorá brevemente la interfaz: barra lateral, explorador, terminal y sección de extensiones.

----

### ¿Por qué usar VSCode?

* Directo y fácil de seguir.
* Ideal para comenzar con un IDE liviano y muy popular.

---

### Actividad 1.2: Instalación de WebStorm

1. Ingresa a https://www.jetbrains.com/webstorm
2. Descarga el instalador del **WebStorm**
3. Instálalo!
4. En la página de **WebStorm** ingresa a **Education** -> Free Licenses (For students)
5. Click en "Request now"
6. Completa los datos para aplicar a la licencia! Es importante que uses el email institucional que contiene **.edu**
7. Abrí WebStorm y explorá brevemente la interfaz

----

### ¿Por qué usar WebStorm?

* Análisis estático de código más profundo.
* Integración nativa con herramientas frontend.
* Refactorización más robusta.

---

### Actividad 2.1: Instalación de Extensiones

1. Abre el **Visual Studio Code**
2. Ingresa a la sección de **Extensiones** (puedes presionar Ctrl+Shift+X)
3. Busca e instala las siguientes extensiones:
   * Color the tag name
   * ESLint
   * GitLens
   * HTML CSS Support
   * Material Icon Theme
   * Prettier

---

### Linter
Es un analizador de código estático, es una herramienta de software que verifica y analiza el código fuente de un programa en busca de posibles errores, problemas de estilo y faltas de las convenciones de codificación.

Su propósito es mejorar la calidad y legibilidad del código.

En **JavaScript** la herramienta más empleada es **ESLint**

----

### ESLint: características
<!-- .slide: style="font-size: 0.75em" -->
- **Análisis estático de código:** Busca de errores, problemas de estilo, inconsistencias y patrones sospechosos. Mejora la calidad y la mantenibilidad del software.
- **Reglas configurables** según las necesidades del proyecto y las preferencias del equipo de desarrollo. Proporciona reglas predefinidas y permite crear reglas personalizadas.
- **Integración flexible** con diferentes CI y diversos IDEs.
- **Mensajes de error y advertencias descriptivos** que ayudan a los desarrolladores a comprender y solucionar los problemas de código de manera eficiente. 
- **Configuración basada en archivos**, el **.eslintrc.js** ó **eslint.config.js**, esto permite mantener configuraciones diferentes para proyectos individuales y compartir configuraciones entre equipos de desarrollo.
- **Compatibilidad con plugins y extensiones**, lo que amplía su funcionalidad y permite agregar reglas adicionales.

----

### ESLint: Reglas
<!-- .slide: style="font-size: 0.80em" -->
- *no-unused-vars*: Detecta variables declaradas pero no utilizadas en el código.
- *no-undef*: Detecta el uso de variables no declaradas.
- *no-console*: Advierte sobre el uso de sentencias console.log()
- *no-extra-semi*: Detecta puntos y comas innecesarios en el código.
- *eqeqeq*: Exige el uso de operadores de igualdad estricta (=== y !==) en lugar de igualdad débil (== y !=).
- *camelcase*: Requiere el uso de convenciones de nomenclatura en estilo camelCase para variables y propiedades.
- *semi*: Exige el uso de punto y coma al final de las declaraciones.
- *quotes*: Establece el uso consistente de comillas simples o dobles para delimitar cadenas de texto.
- *indent*: Establece la regla de indentación para el código.
- *comma-dangle*: Establece si se debe permitir o exigir una coma final en listas y objetos.

---

### Ejercicio: ESLint
1. Crear una carpeta para un proyecto de código nuevo
2. Crear un archivo **.eslintrc**
3. En el archivo configurar las siguientes reglas:
```js
{
  "rules": {
    "no-unused-vars": "warn",
    "no-undef": "error",
    "no-console": "warn",
    "no-extra-semi": "error",
    "eqeqeq": ["error", "always"],
    "camelcase": ["warn", { "properties": "always" }],
    "semi": ["error", "always"],
    "quotes": ["error", "single", { "avoidEscape": true }],
    "indent": ["error", 2, { "SwitchCase": 1 }],
    "comma-dangle": ["error", "only-multiline"]
  }
}
```

----

### Ejercicio: ESLint
4. Crear un archivo js de ejemplo como el siguiente
```js
function hola() {
  nombre='Agus'
  console.log('Hola'+nombre)
}
```
5. Guardar. ¿Qué ocurrio con el archivo? ¿Algo cambió?

---

### Prettier
Es un formateador de código, que permite que todo el equipo de desarrollo cumpla con los estándares de codificación definidos sin necesidad de acciones manuales.s

Prettier es compatible con múltiples frameworks de JavaScript (Angular, React, Vue y Svelte) y también funciona con TypeScript.

---

### Prettier: Configuración
1. Instalar la extensión **Prettier** en el VSC.
2. En el archivo de configuración del **.eslintrc**
```json
"extends": ["plugin:prettier/recommended"],
"plugins": ["prettier"],
```
3. En el menú de la izquierda presionar la rueda e ir a **Settings**
4. Buscar **formatter**
5. Seleccionar **ESLint**
6. Se recomienda checkear **Format on save**

---
![CommitStrip](images/herramientas/CommitStrip-IDE.jpg)

---
## Gestión de Versiones o VCS
Permiten gestionar los cambios en los archivos de un proyecto a lo largo del tiempo, facilitando el trabajo colaborativo
y el acceso remoto al código fuente.

---
## Gestión de Versiones o VCS
Los usuarios pueden:
* Clonar o descargar archivos del repositorio
* Editar y guardar cambios localmente
* Publicar (subir) sus cambios al repositorio remoto
* Consultar el historial y volver a versiones anteriores 
* Crear ramas (branches) para desarrollar nuevas funcionalidades
* Unificar cambios provenientes de diferentes ramas

---

### Un VCS funciona como una máquina del tiempo para tus archivos. Podés ver, comparar o volver a cualquier momento del proyecto.

---
<!-- .slide: data-background="images/herramientas/subversionado.png" -->
## Ventajas de VCS:
* Permite llevar cuenta de los cambios de un conjunto de archivos digitales en el tiempo.
* Cada conjunto de cambios registrados en un momento específico se denomina revisión o commit.
* Permite tanto a un desarrollador como a un grupo de desarrolladores, gestionar el código del proyecto.
* Facilita la colaboración sin sobrescribir el trabajo de otros/as, gracias al control de ramas.

---
## Herramientas de VCS
* Git
* SVN
* Mercurial
* Bazaar

---
![Historieta Versionado](images/herramientas/comicVersionado.png)

---
## Documentación de Código
   
Permite:
* Entender **qué** se está haciendo y por qué
* Mantener el código a lo largo del tiempo

**Documentar ayuda tanto al equipo como a tu “yo del futuro”**

![JsDoc](images/html/jsdoc.png)

---
## Niveles de Documentación
* **Por clase:** incluir una descripción general, autor, fecha y última modificación.
* **Por método:** detallar su función, parámetros y lo que retorna.
* **Variables importantes:** especialmente si son complejas o no evidentes.
* **Limitaciones del código:** advertencias o restricciones relevantes.
* **Algoritmos implementados:** describir la lógica general si no es trivial.

---
## Formato de Documentación (JSDoc)
```javascript
/**
* @fileoverview Librería con funciones de utilidad
* @author Jose
* @version 0.1
*/
   /**
   * Muestra un mensaje de texto
   * @param {String} método nombre del método
   * @param {String} mensaje mensaje a mostrar
   * @returns {integer} el codigo de retorno 0
   */
   function trazas(metodo, mensaje){
       alert("["+metodo+"]:"+mensaje);
       return 0;
   }
```

---
![SPJS](images/herramientas/spjs_3301.jpg)

---
## Documentación...A tener en cuenta
* No uses solo una línea, divídela en párrafos para que sea mas legible
* Tabular los comentarios de líneas consecutivas
* No comentar obviedades
* Se profesional (No insultes o coloques frases fuera de contexto)
* Revisa la ortografía

---
## Documentación...A tener en cuenta
* No comentes si no es necesario
* Comentarios simple y directo
* Documenta mientras desarrollas
* Manten los comentarios actualizados

---
````javascript
return 1; # returns 1
stop(); // Hammertime!
long long ago; /* in a galaxy far far away */
//This code sucks, you know it and I know it.
//Move on and call me an idiot later.
/////////////////////////////// this is a well commented line
// I don't know why I need this,
//but it stops the people being upside-down
x = -x;
````

[más ejemplos](http://stackoverflow.com/questions/184618/what-is-the-best-comment-in-source-code-you-have-ever-encountered%3E)

---

### Ejercicio: JsDoc
1. Asegúrate de tener [nodeJs](https://nodejs.org/es/) instalado. Para eso puedes ejecutar en el cmd:
```shell
node --version
```
2. Instala la dependencia [jsdoc](https://www.npmjs.com/package/jsdoc)
```shell
npm install -g jsdoc
```

----

### Ejercicio: JsDoc
3. Crea un archivo .js básico con algunas funciones. Ejemplo:
```js
/**
 * Calcula el área de un rectángulo.
 * @param {number} ancho - El ancho del rectángulo
 * @param {number} alto - El alto del rectángulo
 * @returns {number} El área del rectángulo
 */
function calcularArea(ancho, alto) {
  return ancho * alto;
}

/**
 * @param {string} nombre - Nombre del usuario
 * @param {number} [edad] - Edad del usuario (opcional)
 * @param {Object} opciones - Opciones de configuración
 * @param {boolean} opciones.activo - Estado del usuario
 * @param {string} opciones.rol - Rol del usuario
 */
function crearUsuario(nombre, edad, opciones) {
  // Implementación
}
```

----

4. En la terminal ejecutar:
```shell
jsdoc ejemplo-doc.js
```

5. Verificar el contenido de la carpeta **out**


* Recomendación: Si empleas **VSC** es recomendable tener la extensión **Better Comments** para visualizar los comentarios con el highlight adecuado.

---
![Comenario de Gatito](images/herramientas/coment_code.jpg)

---
![Comentarios Actualizados](images/herramientas/comentarios_actualizados.jpg)

---
## Bug Tracker o BTS
En proyectos de cierta complejidad o trabajo colaborativo, es fundamental usar una herramienta de seguimiento de errores 
**Bug Tracker o BTS** para registrar, clasificar, asignar y resolver defectos detectados durante el desarrollo o prueba del software.

Un buen BTS no solo organiza errores, también ayuda a establecer prioridades, gestionar tiempos de resolución y comunicar avances.

---
## Ejemplos de Bug Tracker
* Jira
* Bugzilla
* Flyspray
* Trac
* The bug Genie
* MantisBT
 
---
![Bug Tracker](images/herramientas/bug-tracker_jira.png)

---
![Bugzilla](images/herramientas/bug-tracker_bugzilla.png)

---
![FlySpray](images/herramientas/bug-tracker_flyspray.png)

---
![Strip](images/herramientas/Strip-Depart-en-weekend-650-finalenglish.jpg)

---

### Ejercicio: Jira 1
1. Ingresar a la página de [Jira](https://www.atlassian.com/es/software/jira)
2. Click en "Ingresar"
3. Colocar el email y password
4. Crear un espacio de trabajo/proyecto

----

### Ejercicio: Jira 2
1.  Crea **Story** por cada tarea que se desea desarrollar: Título, descripción
2. Asignale un **responsable**
3. Coloca **tags** relacionados
4. Asegurate de que la tarea esté en la columna correspondiente

---
## Prueba de Desempeño o Performance
Tipos principales:

- **Load Test:** Evalúa cómo responde el sistema ante una carga esperada, simulando condiciones reales de producción.
- **Stress Test:** Aplica una carga mayor a la esperada para detectar el punto de ruptura del sistema.
- **Endurance (Resistencia):** Analiza el rendimiento cuando el sistema está bajo carga continua durante un período prolongado.

---
## Prueba de Desempeño o Performance
Estas pruebas ayudan a:
- Identificar cuellos de botella.
- Medir el consumo de recursos.
- Garantizar estabilidad bajo presión.

---
## Herramienta para Stress Test
* Apache JMeter
* SmartMeter.io
* LoadUI
* WebLOAD
* LoadRunner
* Appvance
* NeoLoad
* LoadComplete

---
![JM16](images/herramientas/jm16.png)

---
![JMeter](images/herramientas/jmetertestvso-progress.png)

---
![Response Graph](images/herramientas/response_time_graph.png)

---

### Otras herramientas de pruebas...
Una herramienta de prueba sumamente sencilla de usar el **Axe**, que permite encontrar defectos
relacionados con accesibilidad.

---

### Otras herramienta de pruebas...
Empleando **Lighthouse** se pueden encontrar errores de:
- Performance
- Accesibilidad
- Buenas Prácticas
- SEO (Search Engine Optimization)

---
## Integración Continua
Es una práctica del desarrollo de software en la que los cambios de código se integran frecuentemente en un repositorio 
compartido y luego se verifican automáticamente mediante pruebas, builds u otros procesos.

---
## Integración Continua

<div class="grid-container2">
<div class="grid-item">

### Servidor Propio
* GitLab CI
* Jenkins
* Drone.io

</div>
<div class="grid-item">

### Cloud
* Github Actions
* Travis CI
* Codeship
* CircleCI

</div></div>

---
[Ejemplo de Construcción con GitHub Actions de las filminas](https://github.com/UCC-LabCompu2/filminas/actions)

---
![ci-flujo](images/herramientas/ci-flujo.png)

---
![Git-ci](images/herramientas/Git-CI.png)

---
![ci-laba](images/herramientas/ci-laba.jpg)

---
[![ci-build](images/herramientas/ci-build.jpg)](https://en.wikipedia.org/wiki/Build_light_indicator)

---

### SonarQube 
Es una plataforma de análisis de código estático de código abierto que ayuda a los desarrolladores a identificar y corregir problemas de calidad y seguridad en su código. Se integra con herramientas de desarrollo y pipelines.

---

### SonarQube: Beneficios
<!-- .slide: style="font-size: 0.80em" -->
- **Análisis de calidad de código:** Detecta errores, vulnerabilidades, code smells, duplicaciones, cobertura de pruebas y complejidad. 
- **Seguridad del código:** Identifica vulnerabilidades de seguridad en el código. 
- **Integración con herramientas:** Se integra con IDEs, sistemas de construcción y plataformas CI/CD. 
- **Informes y paneles de control:** Genera informes detallados sobre la calidad del código y permite la creación de paneles personalizados. 
- **Mejora continua:** Permite a los equipos de desarrollo mejorar continuamente la calidad de su código con retroalimentación en tiempo real. 

---

![SonarQube](images/herramientas/SonarQube.png)

---
## ¿Dudas, Preguntas, Comentarios?
![DUDAS](images/pregunta.gif)
