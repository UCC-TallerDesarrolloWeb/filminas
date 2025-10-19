---
title: Backend
theme: league
slideNumber: true
---

# Backend & APIs
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

- API

</div>
<div class="grid-item">


</div>
</div>

---

### ¿Qué es una API?

- Son las siglas de **Application Programming Interface**.
- Es un conjunto de funciones y procedimientos (métodos) que se usan para diseñar e integrar el software de diferentes aplicaciones.
- Permite que varias aplicacines se puedan comunicar entre sí, por más que estén desarrolladas en lenguajes de programación completamente distintos.

---

### API REST
- La forma más común de implementación de una API es mediante **REST** (Representational State Transfer)
- **REST** es un tipo de servicio que se caracteriza por no tener estado alguno y por lograr interconexiones mediante el protocolo HTTP con mensajes de tipo *XML o JSON*.

![REST](images/api/rest.png)

---

### ¿Qué es el protocolo HTTP?

Un protocolo es un conjunto de reglas que se deben seguir para poder obtener o lograr un determinado resultado o acceder a un determinado recurso o servicio.

**HTTP** significa "Hypertext Transfer Protocol", es decir, protocolo de transferencia de hipertexto.

HTTP permite que las solicitudes (Requests) y respuestas (Responses) entre clientes y servidores tengan un deterinado formato a seguit y respetar para que puedan comunicarse sin inconvenientes.

![Cliente-Servidor](images/api/cliente-servidor.png)

---

### Solicitud o Request
Una solicitud o request que se realiza en una comunicación que utiliza el **protocolo HTTP** tiene una serie de partes, donde cada una de ellas cumple con una funcionadad distitna respecto a la transmisión del mensaje que se desea dar a conocer desde el cliente hacia el servidor.

- **Método:** Establece un verdo o modo de comunicación en HTTP
- **URL:** Dirección con la que queremos comunicarnos
- **Header o cabecera:** Van especificaciones, mensajes que se quieren enviar: ej. nombre en formato json
- **Body o cuerpo:** Campo opcional, para solicitar más datos.

----

### Solicitud o Request

![Request](images/api/request.png)

---

### Response

Las responses tienen un formato particular que les permiten transportar la información necesaria para atender a las solicitudes recibidas.

- **Status Code:** Códigos que permiten al cliente entender la respuesta obtenida
- **Header o Cabecera:** 
- **Body o Cuerpo:**

----

### Response

![Response](images/api/response.png)

---
### HTTP - Protocolo

<!-- .slide: style="font-size: 0.80em" -->

- HTTP especifica varios métodos, los que más vamos a utilizar son:
  - **GET** (obtener datos)
  - **POST** (enviar datos)
  - **PUT** (actualizar datos)
  - **DELETE** (eliminar datos)
- HTTP es solo el canal de transporte, no define cómo deben estructurarse los datos ni cómo organizarlos.
- HTTP utiliza los siguientes códigos:
  - **2xx** = Operaciones exitosas
  - **4xx** = Errores del cliente
  - **5xx** = Errores del servidor

---

### [Postman](https://www.postman.com/downloads/)

Es una herramienta que permite:

- Probar APIS
- Documentarlas
- Testear APIs
- Monitorear servicios, etc

---

### PokeApi

Para los siguientes ejercicios vamos a usar la [pokeApi](https://pokeapi.co/)

---

### Ejercicio
1. Ingresar a https://pokeapi.co/api/v2/pokemon/1


---
## ¿Dudas, Preguntas, Comentarios?
![DUDAS](images/pregunta.gif)
