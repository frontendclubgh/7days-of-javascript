# Día 2 — Condicionales

---

## Objetivo

Hoy aprenderás a hacer que tu código tome decisiones.

Vas a dominar el 20% de las condicionales que usarás el 80% del tiempo:

- `if`
- `else`
- `else if`
- `switch` (básico)

Si entiendes esto, tu código deja de ser estático y empieza a pensar.

⏱ Tiempo estimado: 20–25 minutos.

---

## Metodología

Hoy no vas a memorizar estructuras.

Vas a:

1. Entender qué problema resuelve una condicional.
2. Ver ejemplos simples.
3. Analizar qué condición se está evaluando.
4. Aplicarlo en un ejercicio práctico.

Recuerda:

> No nos pagan por escribir `if`.  
> Nos pagan por usar lógica para resolver problemas.

---

### ¿Qué es una condicional?

Una condicional permite ejecutar código solo si se cumple una condición.

Esa condición siempre devuelve:

- `true`
- `false`

Eso es todo.

---

### if y else

```js
let edad = 20;

if (edad >= 18) {
  console.log("Mayor de edad");
} else {
  console.log("Menor de edad");
}
```

Qué está pasando:

- Se evalúa `edad >= 18`
- Si es verdadero → ejecuta el primer bloque
- Si es falso → ejecuta el segundo

Eso es una decisión.

---

### else if

Cuando existen más de dos posibles resultados.

```js
let nota = 85;

if (nota >= 90) {
  console.log("Excelente");
} else if (nota >= 70) {
  console.log("Aprobado");
} else {
  console.log("Reprobado");
}
```

Aquí el programa evalúa condiciones en orden.

Cuando una se cumple, deja de evaluar las demás.

---

### switch

Se usa cuando comparas un mismo valor con múltiples opciones.

```js
let dia = 2;

switch (dia) {
  case 1:
    console.log("Lunes");
    break;
  case 2:
    console.log("Martes");
    break;
  default:
    console.log("Día inválido");
}
```

Es más claro cuando hay muchos casos posibles.

---

### Concepto clave

Programar con condicionales es hacer preguntas lógicas.

Ejemplo real:

Un sistema necesita saber si un usuario puede acceder.

Dato → edad  
Pregunta → ¿edad >= 18?  
Resultado → Permitir o bloquear  

Eso es exactamente lo que estás aprendiendo.

---

## Practicar

Leer sobre decisiones no te enseña lógica.

Tomar decisiones escribiendo código sí.

Cada if que escribes es una pregunta lógica.

Cada error que corriges fortalece tu pensamiento.

Ahora te toca aplicar.

---

### Ejercicio

```js
1. Declare una variable llamada `numero`.
2. Si el número es mayor que 0 → muestre "Positivo".
3. Si es menor que 0 → muestre "Negativo".
4. Si es 0 → muestre "Cero".
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

1. ¿Cuál es la diferencia entre `if` y `else if`?
2. ¿Cuándo usarías `switch` en lugar de múltiples `if`?
3. ¿Qué ocurre si una condición en `if` es falsa y no existe `else`?

Si puedes responder sin copiar → entendiste.

---

## Conclusión

Hoy tu código dio un paso importante.

Dejó de ejecutar instrucciones en línea.

Ahora puede evaluar condiciones y tomar decisiones.

La mayoría de los programas hacen esto:

1. Reciben datos.
2. Evalúan condiciones.
3. Ejecutan acciones según el resultado.

Ese es el 20% que genera el 80% de la lógica en programación.

Mañana aprenderás a repetir decisiones automáticamente.

Paso a paso.

Entrenamos lógica, no solo sintaxis.

---
> "La mejor manera de aprender JavaScript es practicando todos los días."