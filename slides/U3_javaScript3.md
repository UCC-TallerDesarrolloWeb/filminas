---
title: javaScript
theme: league
slideNumber: true
---

# JavaScript: 3ra Parte
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
<!-- .slide: style="font-size: 0.60em" -->
## Temario
<div class="grid-container2">
<div class="grid-item">

- Métodos para Strings
- Arrays
- Métodos para Arrays
  - Push
  - Splice
[Ejercicio: Vaciar Carrito](U5_javaScript3.html#/8)


</div>
<div class="grid-item">

[Ejercicio: Filter](U5_javaScript3.html#/10)
[Ejercicio: Formateo de Precio](U5_javaScript3.html#/11)
[Ejercicio: Total y Cantidad](U5_javaScript3.html#/12)


</div>
</div>

---

## Métodos para Strings
````javascript
var nombreMateria = 'LabCompu2';
nombreMateria.length;
nombreMateria[0]; //Devuelve L, primera letra
nombreMateria[nombreMateria.length-1]; //Devuelve 2, última letra
nombreMateria.indexOf('Compu2'); //Encuentra una subcadena dentro de una cadena y la extrae, da como resultado 3
nombreMateria.indexOf('pepe'); //Resultado -1, subcadena no encontrada
nombreMateria.slice(0,3); //Esto devuelve Lab
nombreMateria.slice(3); //Esto devuelve Compu2
nombreMateria.toLowerCase(); //Conversión a minúsculas
nombreMateria.toUpperCase(); //Conversión a Mayusculas
nombreMateria.replace('Lab','Laboratorio');
````

---

## Métodos para Strings
````javascript
var saludo1 = 'Hola';
var saludo2 = 'Mundo!';
var texto = saludo1 + saludo2;
var nombreMat = "Laboratorio de Computacion 2";
nombreMat.split('a'); //Se crea el siguiente array: ['L','bor','torio de Comput','cion 2'];
````

---

### [Arrays](https://www.w3schools.com/jsref/jsref_obj_array.asp)
Es una estructura de datos que permite almacenar una colección ordenada de elementos. Estos elementos pueden ser de diferentes tipos (números, cadenas, objetos, etc.) y se acceden a través de un índice, que es un número entero que indica su posición en la lista.

```js
let frutas = ["manzana", "banana", "naranja"];
let numeros = new Array(1, 2, 3, 4, 5);
```

---

### Arrays: Métodos
Existen MUCHOS métodos de arrays. Los más usados:
- filter
- find
- flat
- forEach
- length
- pop
- push
- slice
- splice

---

### Array: Push
Agrega un elemento al final del array.
```js
let frutas = ["manzana", "banana", "naranja"];
frutas.push("arandano");
console.log(["manzana", "banana", "naranja", "arandano"])
```

---

### Array: Splice
Permite añadir o remover elementos de un array.
```js
let frutas = ["manzana", "banana", "naranja"];
frutas.splice(2,1); //a partir del elemento 2, borra 1 elemento
console.log(["manzana", "banana"])
```

---

### Ejercicio: Vaciar Carrito y Eliminar Producto

1. Crear un botón para "Vaciar el Carrito" (usar localstorage.removeItem)
2. Agregar en cada producto un botón para "Eliminar el producto" (usar array.splice)

---

### Ejercicio: Vaciar Carrito y Eliminar Producto

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ln7tgVrHuSw?si=vksPGWWNMja1L7UD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

### Ejercicio: Filter
1. Empleando de base el ejercicio anterior agregue en el html:
    - Un input de tipo texto que permita realizar búsqueda de **palabras**.
    - Dos inputs de tipo number que permita filtrar en un rango de **precios**
    - Un `<select>` con `<option>` para filtrar por marca.
    - Un `<checkbox>` para filtrar por **categoría** de Producto.

----

### Ejercicio: Filter

2. Emplea **filter** y permite al usuario:
   - Filtrar por palabra
   - Filtrar por rango de precio
   - Filtrar por marca
   - Filtrar por categoría de productos

----

### Ejercicio: Filter (parte 1)

<iframe width="560" height="315" src="https://www.youtube.com/embed/VqFQqsjN_yc?si=MVMOp20ELtSdvtIZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

----

### Ejercicio: Filter (parte 2)

<iframe width="560" height="315" src="https://www.youtube.com/embed/zDW_YW38EHo?si=nZiouMqewqfVpd2x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

### Ejercicio: Formatear Precio

1. Agregar una función que permita visualizar el precio de la siguiente manera: $3.123,45

Este formato debe ser usado tanto en el **catálogo** como en el **carrito**.

Emplear [Intl.NumberFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/NumberFormat)

2. Agregar un contador de productos al lado del botón de carrito de compras

----

### Ejercicio: Formatear Precio

<iframe width="560" height="315" src="https://www.youtube.com/embed/P0NFLkClrVA?si=D0mOks3cbg6TrAyJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

### Ejercicio: Total y Cantidad de Productos

1. Mostrar el total a pagar en carrito de compras.
2. Agregar la "Cantidad" de cada producto (en caso de que el usuario agregue varias veces el mismo producto).

----

### Ejercicio: Total y Cantidad de Productos

<iframe width="560" height="315" src="https://www.youtube.com/embed/bXRPcyJAg6c?si=Ggg1QEIfYmRgeTxK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

### [Sort](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)

Permite ordenar los elementos de un array o un objeto por diferentes criterios.

---

### Ejercicio: Ordenar el catálogo

1. En el HTML agrega un `<select>` con `<option>` para permitir al usuario ordenar el catálogo por precio (de menor a mayor y de mayor a menos) u ordenar por nombre de producto (A-Z ó Z-A)
2. Crea una función javaScript que permita realizar el orden indicado por el usuario.

----

### Ejercicio: Ordenar el catálogo

<iframe width="560" height="315" src="https://www.youtube.com/embed/Cifbb_lo7WU?si=B4jJdvgSTHVZ-MZ5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---
## Bibliografia xD
[![W3 School](images/html/logo_w3schoolscom.png)](http://www.w3schools.com/js/default.asp)

[![MDN](images/html/logo_MDN.png)](https://developer.mozilla.org/es/docs/Web/JavaScript)

---
## Cursos Online
[![CodeCademy](images/Eventos/codecademy.png)](https://www.codecademy.com/)

[![Acamica](images/Eventos/acamica.jpg)](https://www.acamica.com/)

---
## ¿Dudas, Preguntas, Comentarios?
![DUDAS](images/pregunta.gif)
