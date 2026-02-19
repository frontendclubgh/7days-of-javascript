# Día 4 — Funciones

---

## Objetivo

Hoy aprenderás a encapsular lógica.

Vas a dominar el 20% de funciones que usarás el 80% del tiempo:

- Declaración de funciones
- Parámetros
- Retorno (`return`)
- Arrow functions

Si entiendes esto, tu código dejará de ser una lista de instrucciones sueltas  
y empezará a tener estructura.

⏱ Tiempo estimado: 20–30 minutos.

---

## Metodología

Hoy no vamos a memorizar sintaxis.

Vamos a entender:

1. Qué problema resuelven las funciones.
2. Cómo dividir código en bloques reutilizables.
3. Cómo pasar información.
4. Cómo devolver resultados.

Recuerda:

> Un programador profesional no escribe más código.  
> Escribe código reutilizable.

---

### ¿Qué es una función?

Una función es un bloque de código que:

- Tiene un nombre.
- Puede recibir datos.
- Puede devolver un resultado.
- Se puede ejecutar cuando tú quieras.

Ejemplo básico:

```js
function saludar() {
  console.log("Hola");
}

saludar();
```

La función no se ejecuta hasta que la llamas.

---

### Parámetros

Las funciones pueden recibir información.

```js
function saludar(nombre) {
  console.log("Hola " + nombre);
}

saludar("Carlos");
```

Aquí:

- `nombre` es un parámetro.
- `"Carlos"` es el argumento.

---

### Retorno (return)

Una función puede devolver un resultado:

```js
function sumar(a, b) {
  return a + b;
}

let resultado = sumar(5, 3);
console.log(resultado);
```

`return`:  
- Detiene la función.  
- Devuelve un valor.  

Regla importante:

Si no usas `return`, la función no devuelve nada.

---

### Arrow functions

Forma moderna y más usada.

```js
const sumar = (a, b) => {
  return a + b;
};
```

Versión corta (cuando solo hay una línea):

```
const sumar = (a, b) => a + b;
```

Hoy en día verás esta sintaxis en casi todos los proyectos modernos.

---

### Concepto clave

Una función responde a esta pregunta:

¿Esta lógica se repite o merece tener un nombre propio?

Si la respuesta es sí → crea una función.

Las funciones permiten:

- Reutilizar código.
- Organizar lógica.
- Facilitar mantenimiento.
- Evitar duplicación.

---

## Practicar

Hasta ahora has:

- Guardado datos.
- Evaluado condiciones.
- Repetido procesos.

Hoy vas a combinar todo eso dentro de funciones.

Esto es un punto de inflexión.

Empiezas a pensar como programador.

---

### Ejercicio

```js
1. Crea una función llamada esMayorDeEdad que:
  - Reciba una edad.
  - Devuelva true si es mayor o igual a 18.
  - Devuelva false si no lo es.

2. Crea una función llamada calcularDescuento que:
  - Reciba un precio.
  - Si el precio es mayor a 100, aplique 10% de descuento.
  - Devuelva el precio final.
```

No copies ejemplos anteriores. Escríbelo desde cero.

---

### Enviar solución

Cuando termines:

- Ejecuta tu código en consola.
- Verifica que funcione sin fallas.
- [Sube la solución](https://frontendclubgh.github.io/7daysofjavascript/tarea.html) para recibir feedback

No enviar = no completar.

La práctica es lo que consolida el aprendizaje.

---

## Cuestionario

Responde sin mirar arriba:

1. ¿Qué diferencia hay entre parámetro y argumento?
2. ¿Qué ocurre si no usas return?
3. ¿Cuándo conviene crear una función?

Si puedes explicarlo con tus palabras → lo entendiste.

---

## Conclusión

Hoy tu código dejó de ser lineal.

Ahora puedes:

- Agrupar lógica.
- Reutilizar procesos.
- Crear estructuras limpias.

El 80% de JavaScript real se basa en:

- Variables
- Condicionales
- Bucles
- Funciones

Ese es el núcleo.

Lo demás es profundidad y herramientas.

Sigue construyendo base sólida.

Mañana avanzamos hacia estructuras de datos más poderosas.

---

>"La mejor manera de aprender JavaScript es practicando todos los días."