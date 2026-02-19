# Día 3 — Bucles

---

## Objetivo

Hoy aprenderás a repetir acciones automáticamente.

Vas a dominar el 20% de los bucles que usarás el 80% del tiempo:

- `for`
- `while`

Si entiendes esto, tu código podrá ejecutar tareas repetitivas sin duplicar líneas.

⏱ Tiempo estimado: 20–25 minutos.

---

## Metodología

Hoy no vas a memorizar estructuras largas.

Vas a:

1. Entender qué problema resuelve un bucle.
2. Analizar cómo funciona paso a paso.
3. Escribirlo tú mismo.
4. Aplicarlo en un ejercicio práctico.

Recuerda:

> No nos pagan por repetir código.  
> Nos pagan por automatizar soluciones.

---

### ¿Qué es un bucle?

Un bucle permite ejecutar un bloque de código varias veces.

En lugar de escribir esto:

```js
console.log("Hola");
console.log("Hola");
console.log("Hola");
```

Podemos automatizarlo.

---

### for

Se usa cuando sabes cuántas veces quieres repetir algo.

```js
for (let i = 0; i < 5; i++) {
  console.log("Hola");
}
```

Qué significa:

- `let i = 0` → punto de inicio
- `i < 5` → condición
- `i++` → incremento

Se ejecutará 5 veces.

**Ejemplo real**

Mostrar los números del 1 al 5:

```js
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```

Aquí el bucle repite una acción cambiando el valor en cada iteración.

---

### while

Se usa cuando no sabes exactamente cuántas veces se repetirá,
solo sabes que debe cumplirse una condición.

```js
let contador = 1;

while (contador <= 5) {
  console.log(contador);
  contador++;
}
```

El bucle continúa mientras la condición sea verdadera.

---

### Concepto clave

Un bucle responde a esta pregunta:

¿Necesito repetir algo más de una vez?

Si la respuesta es sí → usa un bucle.

La mayoría de los programas reales:

1. Reciben datos.
2. Evalúan condiciones.
3. Repiten procesos.

Hoy aprendiste la tercera parte.

---

## Practicar

Repetir manualmente código no es eficiencia.

Automatizar sí.

Cada bucle que escribes es una forma de pensar en procesos.

Si puedes controlar la repetición, puedes controlar el flujo del programa.

Ahora te toca aplicar.

---

### Ejercicio

```js
1. Muestre los números del 1 al 10 usando for.
2. Muestre los números del 10 al 1 usando while.
```

No copies el ejemplo. Escríbelo desde cero.

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

1. ¿Cuándo es mejor usar for?
2. ¿Cuál es el riesgo principal de un while?
3. ¿Qué hace exactamente i++?

Si puedes responder sin copiar → entendiste.

---

## Conclusión

Hoy tu código aprendió a repetir acciones.

Eso significa:

- Menos código duplicado.
- Más automatización.
- Más eficiencia.

La mayoría de los programas hacen esto:

- Guardan datos.
- Toman decisiones.
- Repiten procesos.

Ese es el 20% que genera el 80% del trabajo real.

Mañana aprenderás a organizar mejor tu código usando funciones.

Paso a paso.

Entrenamos lógica, no solo sintaxis.

---

>"La mejor manera de aprender JavaScript es practicando todos los días."