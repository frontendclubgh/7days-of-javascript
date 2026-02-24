# Día 1 — Variables y Operadores

---

## Objetivo

Hoy aprenderás el fundamento de toda la programación:

- Guardar información
- Entender qué tipo de información estás guardando
- Comparar valores
- Tomar una decisión simple

Si dominas esto, dominas el 20% de JavaScript que usarás el 80% del tiempo.

⏱ Tiempo estimado: 20–25 minutos.

---

## Metodología

Hoy no vas a memorizar.

Vas a:

1. Entender qué problema resuelve cada herramienta.
2. Ver ejemplos simples.
3. Escribir tu propio código.
4. Aplicarlo en un pequeño ejercicio.

Recuerda:

> No nos pagan por escribir código.  
> Nos pagan por resolver problemas.

---

### Variables

Una variable es un contenedor de información.

```js
const nombre = "Ana";
let edad = 25;
```

Regla de oro:

- Usa `const` por defecto.
- Usa `let` solo si el valor cambiará.

Si algo no debe cambiar, protégelo.

**Ejemplo real:**  
Imagina un sistema de registro:  

```js
const usuario = "Carlos";
let intentos = 1;

intentos = intentos + 1;
```
El nombre no cambia.  
Los intentos sí.

Eso define qué usar.

---

### Tipos de datos

JavaScript puede guardar distintos tipos de información.

```js
let numero = 42;          // Number
let texto = "Hola";       // String
let activo = true;        // Boolean
let nulo = null;          // Null
let indefinido;           // Undefined
```

No necesitas memorizar todos.  

Solo entiende:

- Números → cálculos
- Texto → mensajes
- Booleanos → decisiones

Eso cubre casi todo lo que usarás al inicio.

---

### Operadores y comparaciones

Los operadores permiten trabajar con datos.

```js
const a = 10;
const b = 5;

console.log(a + b);     // 15
console.log(a > b);     // true
console.log(5 === "5"); // false
```

Regla importante:  

Usa siempre `===`

Compara valor y tipo.

Evita errores silenciosos.

---

### Operador ternario

Forma corta de tomar una decisión.

```js
// OPERADOR TERNARIO
const edad = 20;
const resultado = edad >= 18 ? "Mayor de edad" : "Menor de edad";
console.log(resultado);
```

Traducción mental:

Si la condición es verdadera → opción A  
Si no → opción B

Eso es lógica básica.

---

## Practicar

Leer no te convierte en programador.

Escribir sí.

El conocimiento no se acumula.
Se construye practicando.

Si hoy solo lees y no escribes código, mañana olvidarás el 80%.

Si escribes, aunque te equivoques, estás entrenando tu lógica.

Ahora te toca aplicar.

---

### Ejercicio

```js
1. Crea una variable con tu nombre (`const`)
2. Crea una variable con tu edad (`let`)
3. Crea un mensaje usando template literals
4. Usa un operador ternario para verificar si eres mayor de edad
```

No copies ejemplos anteriores. Escríbelo desde cero.

Resuelve este ejercicio en [Codepen](https://codepen.io/) y comparte la URL cuando envíes la tarea.

---

### Enviar solución

Cuando termines:

- Ejecuta tu código en consola.
- Verifica que funcione sin fallas.
- [Sube la solución](https://frontendclubgh.github.io/7daysofjavascript/tarea.html) para recibir feedback

No enviar = no completar.

Aquí entrenamos en serio.

---

## Cuestionario

Responde sin mirar arriba:

1. ¿Cuál es la diferencia entre `let` y `const`?
2. ¿Qué retorna `5 === "5"` y por qué?
3. Escribe un operador ternario que retorne "Par" o "Impar".

Si puedes responder sin copiar → entendiste.

---

## Conclusión

Hoy aprendiste lo esencial de JavaScript:

- Variables
- Tipos básicos
- Comparaciones
- Decisiones simples

Eso es el núcleo del lenguaje.

La mayoría de los programas hacen esto:

1. Guardan datos.
2. Los evalúan.
3. Toman decisiones.

Ese es el 20% que genera el 80% de los resultados.

Mañana tu código empezará a tomar decisiones más complejas.

Paso a paso.

Entrenamos lógica, no solo sintaxis.

---
> "La mejor manera de aprender JavaScript es practicando todos los días."