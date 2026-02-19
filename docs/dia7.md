# Día 7 — Objetos

---

## Objetivo

Hoy aprenderás a estructurar datos complejos usando objetos.

Vas a dominar el 20% que usarás el 80% del tiempo:

- Crear objetos
- Acceder a propiedades
- Modificar valores
- Usar objetos dentro de arrays

Si entiendes esto, puedes representar información real como usuarios, productos o pedidos.

⏱ Tiempo estimado: 25–30 minutos.

---

## Metodología

Hoy no vamos a ver conceptos avanzados.

Vamos a enfocarnos en:

1. Qué problema resuelven los objetos.
2. Cómo se estructuran.
3. Cómo acceder y modificar datos.
4. Cómo combinarlos con arrays.

Recuerda:

> Las aplicaciones reales no manejan datos sueltos.  
> Manejan estructuras.

---

### ¿Qué es un objeto?

Un objeto es una colección de datos relacionados organizados en pares:

clave: valor

Ejemplo:

```js
let usuario = {
  nombre: "Carlos",
  edad: 25,
  activo: true
};
```

Aquí:

- `nombre`, `edad`, `activo` son propiedades.
- Cada propiedad tiene un valor.

---

### Acceder a propiedades

Hay dos formas principales.

**Notación con punto**

```js
console.log(usuario.nombre);
```

**Notación con corchetes**

```js
console.log(usuario["edad"]);
```

La notación con puntos es la más común.

---

### Modificar valores

Podemos cambiar propiedades fácilmente:

```js
usuario.edad = 30;
usuario.activo = false;

console.log(usuario);
```

También podemos agregar nuevas propiedades

```js
usuario.email = "carlos@email.com";
```

---

### Objetos dentro de arrays

Aquí es donde todo cobra sentido.

```js
let usuarios = [
  { nombre: "Ana", edad: 22 },
  { nombre: "Luis", edad: 35 },
  { nombre: "Marta", edad: 28 }
];
```

Ahora puedes:

- Recorrer el array.
- Acceder a cada objeto.
- Usar condicionales.
- Usar `filter` o `map`.

Ejemplo:

```js
let mayores = usuarios.filter(usuario => usuario.edad >= 30);

console.log(mayores);
```

Esto es programación real.

---

### Concepto clave

Un objeto responde a esta pregunta:

¿Necesito representar algo del mundo real con varias características?

Si la respuesta es sí → usa un objeto.

Ejemplos reales:

- Usuario → nombre, email, edad
- Producto → nombre, precio, stock
- Pedido → cliente, productos, total

Casi todas las aplicaciones modernas están construidas con arrays de objetos.

---

## Practicar

Ya sabes:

- Variables
- Condicionales
- Bucles
- Funciones
- Arrays
- map y filter

Hoy agregas la última pieza esencial.

Si combinas todo lo aprendido, puedes construir la base de cualquier aplicación.

Ahora te toca aplicar.

---

### Ejercicio

```js
1. Crea un array llamado productos con al menos 4 objetos.
 Cada objeto debe tener:
- nombre
- precio
- disponible (true/false)

2. Usa filter para obtener solo los productos disponibles.
3. Usa map para crear un nuevo array con solo los nombres de los productos disponibles.
4. Muestra el resultado en consola.
```

Bonus:  
Crea una función que reciba el array y devuelva el precio total de todos los productos disponibles.

No copies. Escríbelo desde cero.

---

### Enviar solución

Cuando termines:

- Ejecuta tu código en consola.
- Verifica que funcione sin fallas.
- [Sube la solución](https://frontendclubgh.github.io/7daysofjavascript/tarea.html) para recibir feedback

No enviar = no completar.

Este es el cierre del reto.

---

## Cuestionario

Responde sin mirar arriba:

1. ¿Qué es una propiedad en un objeto?
2. ¿Cuál es la diferencia entre notación punto y corchetes?
3. ¿Por qué la mayoría de aplicaciones usan arrays de objetos?

Si puedes explicarlo con tus palabras → dominaste el núcleo.

---

## Conclusión

En 7 días aprendiste el 20% que realmente importa:

- Variables
- Condicionales
- Bucles
- Funciones
- Arrays
- Métodos modernos
- Objetos

Ese es el núcleo que genera el 80% del trabajo real en JavaScript.

Lo demás es profundidad, herramientas y práctica.

Ahora ya no eres alguien que "ve código".
Eres alguien que puede construir lógica.

Sigue practicando.

La consistencia transforma principiantes en desarrolladores.

---

>"La mejor manera de aprender JavaScript es practicando todos los días."