# Juego-Amigo-Secreto 

<p>

</p>

 ##Funciones y temas aplicados:

**Variables y Arrays:**
```
let listaDeAmigos = []; → Almacena los nombres.
```
**Funciones:**
```
agregarAmigo() → Agrega nombres a la lista.
renderizarLista() → Muestra la lista en la página.
sortearAmigo() → Selecciona un amigo al azar.
```
**Manipulación del DOM:**
```
document.getElementById("id") → Obtiene elementos del HTML.
document.createElement("li") → Crea elementos de lista.
innerHTML = "" → Limpia listas antes de actualizar.
```
**Validaciones:**
```
if (!nombreIngresado) {} → Evita agregar nombres vacíos.
if (listaDeAmigos.includes(nombreIngresado)) {} → Evita nombres repetidos.
if (listaDeAmigos.length === 0) {} → Verifica que haya amigos antes de sortear.
```
**Métodos de Arrays:**
```.
push(nombre) → Agrega un nombre a la lista.
.includes(nombre) → Verifica si un nombre ya existe.
```
**Número aleatorio:**
```
Math.random() y Math.floor() → Generan un índice aleatorio para el sorteo.
```
**Mensajes de alerta:**
```
alert("mensaje") → Notifica errores o advertencias.
```

>Funcionalidad :fa-cogs:
Agregar amigos: Los usuarios ingresan nombres, los cuales se validan para evitar vacíos o repeticiones.
Mostrar lista: Los nombres ingresados se muestran en una lista en la página.
Sorteo: Se selecciona un amigo al azar de la lista y se muestra en la página.
Validaciones: Asegura que no haya nombres vacíos, repetidos y que haya amigos antes de sortear.
Es un juego interactivo de "Amigo Secreto" donde los usuarios gestionan una lista y sortean amigos al azar.
