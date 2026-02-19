# Día 6 — Arrays (Parte 2)

---

## Objetivo

Hoy aprenderás a manipular arrays con métodos esenciales.

Vas a dominar el 20% de métodos que usarás el 80% del tiempo:

- `push`
- `pop`
- `map`
- `filter`

Si entiendes estos cuatro, puedes resolver la mayoría de problemas reales con listas.

⏱ Tiempo estimado: 25–30 minutos.

---

## Metodología

No vamos a ver todos los métodos de arrays.

Vamos a enfocarnos en los que realmente importan.

Primero entenderás qué hace cada uno.  
Luego verás ejemplos reales.  
Después lo aplicarás tú mismo.

Recuerda:

> Saber recorrer arrays es básico.  
> Saber transformarlos es profesional.

---

### push

Agrega un elemento al final del array.

```js
let numeros = [1, 2, 3];

numeros.push(4);

console.log(numeros);
// [1, 2, 3, 4]
```

Se usa cuando necesitas añadir información nueva.

Ejemplo real: agregar un nuevo usuario a una lista.

---

### pop

Elimina el último elemento del array.

```js
let numeros = [1, 2, 3];

numeros.pop();

console.log(numeros);
// [1, 2]
```

Se usa cuando necesitas quitar el elemento más reciente.

---

### map

Crea un nuevo array transformando cada elemento.

No modifica el original.

```js
let numeros = [1, 2, 3];

let dobles = numeros.map(numero => numero * 2);

console.log(dobles);
// [2, 4, 6]
```

`map` responde a esta pregunta:

¿Necesito transformar cada elemento en algo nuevo?

Ejemplo real: convertir precios a otra moneda.

---

### filter

Crea un nuevo array con los elementos que cumplen una condición.

```js
let numeros = [10, 25, 30, 5];

let mayores = numeros.filter(numero => numero > 20);

console.log(mayores);
// [25, 30]
```

`filter` responde a esta pregunta:

¿Necesito quedarme solo con algunos elementos?

Ejemplo real: filtrar productos disponibles.

---

### Concepto clave

Antes:

- Usabas `for` para recorrer.

Ahora:

- Usas `map` para transformar.
- Usas `filter` para seleccionar.

Esto hace tu código:

- Más limpio.
- Más legible.
- Más profesional.

---

## Practicar

Si combinas lo que sabes:

- Funciones
- Condicionales
- Arrays
- map
- filter

Ya puedes construir lógica avanzada.

Hoy dejas de pensar en "recorrer manualmente"
y empiezas a pensar en "transformar inteligentemente".

Ahora te toca aplicar.

---

### Ejercicio

```js
1. Crea un array con 6 números.
2. Usa filter para crear un nuevo array solo con los números mayores a 10.
3. Usa map para multiplicar por 2 los números filtrados.
4. Muestra el resultado final en consola.
```

Bonus:  
Crea una función que reciba un array de precios y devuelva solo los precios mayores a 50 con un 10% de descuento aplicado.

No copies ejemplos. Escríbelo desde cero.

---

### Enviar solución

Cuando termines:

- Ejecuta tu código en consola.
- Verifica que funcione sin fallas.
- [Sube la solución](https://frontendclubgh.github.io/7daysofjavascript/tarea.html) para recibir feedback

No enviar = no completar.

La práctica construye confianza.

---

## Cuestionario

Responde sin mirar arriba:

1. ¿Qué diferencia hay entre `map` y `filter`?
2. ¿`map` modifica el array original?
3. ¿Cuándo usarías `push`?

Si puedes responder con claridad → entendiste el núcleo.

---

## Conclusión

Hoy aprendiste a manipular arrays de forma moderna.

Eso significa:

- Transformar datos.
- Filtrar información.
- Escribir código más limpio.

El núcleo real de JavaScript que ya dominas:

- Variables
- Condicionales
- Bucles
- Funciones
- Arrays
- Métodos esenciales (map, filter)

Ese es el 20% que usarás el 80% del tiempo.

Mañana podemos cerrar el ciclo entrando en:

- Objetos (estructuras más complejas)
- DOM (hacer todo esto visible en pantalla)

Ya tienes base sólida.

---

>"La mejor manera de aprender JavaScript es practicando todos los días."