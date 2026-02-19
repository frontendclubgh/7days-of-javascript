# Día 5 — Arrays (Parte 1)

---

## Objetivo

Hoy aprenderás a trabajar con listas de datos.

Vas a dominar el 20% de arrays que usarás el 80% del tiempo:

- Crear arrays
- Acceder a posiciones
- Modificar valores
- Propiedad `length`

Si entiendes esto, podrás manejar múltiples datos sin crear mil variables.

⏱ Tiempo estimado: 20–25 minutos.

---

## Metodología

Hoy no vas a memorizar todos los métodos de arrays.

Vas a entender:

1. Qué problema resuelven.
2. Cómo acceder a la información.
3. Cómo modificarla.
4. Cómo recorrerlos (con lo que ya sabes de bucles).

Recuerda:

> Si sabes usar arrays, puedes manejar datos reales.

---

### ¿Qué es un array?

Un array es una lista ordenada de elementos.

Ejemplo:

```js
let frutas = ["manzana", "banana", "naranja"];
```

En lugar de hacer esto:

```js
let fruta1 = "manzana";
let fruta2 = "banana";
let fruta3 = "naranja";
```

Lo agrupamos en una sola estructura.

---

### Acceder a elementos

Cada elemento tiene una posición (índice).

Importante:

Los arrays empiezan en 0.

```js
let frutas = ["manzana", "banana", "naranja"];

console.log(frutas[0]); // "manzana"
console.log(frutas[1]); // "banana"
```

Posiciones:

0 → manzana  
1 → banana  
2 → naranja  

---

### Modificar valores

Podemos cambiar un valor usando su índice:

```js
frutas[1] = "pera";

console.log(frutas);
// ["manzana", "pera", "naranja"]
```

---

### length

Nos dice cuántos elementos tiene el array:

```js
let numeros = [10, 20, 30, 40];

console.log(numeros.length); // 4
```

Muy importante cuando usamos bucles.

---

### Recorrer un array

Aquí conectamos con el Día 3.

```js
let numeros = [10, 20, 30, 40];

for (let i = 0; i < numeros.length; i++) {
  console.log(numeros[i]);
}
```

Esto hace:

- Empieza en 0.
- Continúa mientras i sea menor que la longitud.
- Muestra cada elemento.

Este patrón lo usarás constantemente.

---

### Concepto clave

Un array responde a esta pregunta:

¿Necesito almacenar múltiples valores relacionados?

Si la respuesta es sí → usa un array.

La mayoría de aplicaciones reales manejan:

- Listas de usuarios
- Productos
- Mensajes
- Resultados

Y todo eso son arrays.

---

## Practicar

Hasta ahora manejabas datos individuales.

Hoy empiezas a manejar colecciones.

Eso cambia completamente lo que puedes construir.

Cuando sabes combinar:

- Arrays
- Bucles
- Condicionales
- Funciones

Ya puedes crear lógica real.

Ahora te toca aplicar.

---

### Ejercicio

```js
1. Crea un array con 5 números.
2. Recorre el array y muestra cada número en consola.
3. Crea una función que reciba un array y devuelva la suma total de sus elementos.
```

No copies. Escríbelo desde cero.

---

### Enviar solución

Cuando termines:

- Ejecuta tu código en consola.
- Verifica que funcione sin fallas.
- [Sube la solución](https://frontendclubgh.github.io/7daysofjavascript/tarea.html) para recibir feedback

No enviar = no completar.

La repetición consolida el aprendizaje.

---

## Cuestionario

Responde sin mirar arriba:

- ¿En qué índice empieza un array?
- ¿Para qué sirve `.length`?
- ¿Por qué usamos `i < array.length` en el bucle?

Si puedes explicarlo con claridad → lo entendiste.

---

## Conclusión

Hoy tu código aprendió a manejar múltiples datos.

Eso significa:

- Más poder.
- Más organización.
- Más posibilidades.

El núcleo real de JavaScript es:

- Variables
- Condicionales
- Bucles
- Funciones
- Arrays

Ese es el 20% que usarás el 80% del tiempo.

Mañana veremos métodos esenciales de arrays que hacen tu código más limpio y moderno.

---

>"La mejor manera de aprender JavaScript es practicando todos los días."