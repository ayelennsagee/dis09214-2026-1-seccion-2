# sesión 04 - 10/04

# Datos Dinámicos y Variables en p5.js

El documento explica cómo crear movimiento e interacción en p5.js usando variables y funciones dinámicas. Se trabaja principalmente con datos que cambian en tiempo real, como la posición del mouse, el teclado o el tamaño de la ventana.

Las variables `mouseX` y `mouseY` permiten detectar la posición del cursor en la pantalla y hacer que figuras reaccionen o sigan el movimiento del mouse.

Ejemplo:
```js
ellipse(mouseX, mouseY, 100, 100);
```

También se presentan variables integradas de p5.js relacionadas con:
- el mouse
- el teclado
- el tiempo
- el tamaño del canvas y la ventana

Algunas de las más usadas son:
- `width`
- `height`
- `windowWidth`
- `windowHeight`
- `frameCount`
- `key`
- `mouseIsPressed`

Luego se enseña cómo crear variables propias usando:
- `let` para valores que cambian
- `const` para valores fijos

Además, se introducen los objetos en JavaScript, que sirven para agrupar información dentro de una sola estructura y así organizar mejor el código.

La función `random()` permite generar números aleatorios para crear movimientos o comportamientos más dinámicos.

Ejemplos:
```js
random();
random(100);
random(20, 50);
```

La función `map()` sirve para transformar un valor de un rango a otro.

Sintaxis:
```js
map(valor, minOriginal, maxOriginal, minNuevo, maxNuevo);
```

Finalmente, el desafío de la clase consiste en tomar un dibujo anterior y agregarle movimiento utilizando todas las herramientas aprendidas:
- variables dinámicas
- movimiento con el mouse
- objetos
- `random()`
- `map()`
- tamaños dinámicos del canvas
