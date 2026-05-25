# sesión 03

---
#03
# Introducción a p5.js

## ¿Qué es p5.js?

p5.js es una herramienta basada en JavaScript que sirve para crear dibujos, animaciones e interacciones visuales mediante programación.  

Se utiliza mucho en diseño, arte digital y programación creativa porque permite trabajar de forma más visual y experimental.

---

## Algoritmo

Un algoritmo es una lista de pasos ordenados para realizar una tarea o solucionar un problema.  

Para que funcione correctamente debe:

- tener un orden lógico
- ser claro
- tener un inicio y un final

---

## Input, proceso y output

Todo sistema funciona mediante:

- **Input:** información que entra
- **Proceso:** lo que ocurre con esa información
- **Output:** resultado final

Por ejemplo:

- mover el mouse = input
- el código procesa el movimiento = proceso
- las figuras se mueven = output

---

## Funciones principales

### `setup()`

Se ejecuta una sola vez al inicio.  

Aquí normalmente se:
- crea el canvas
- cargan imágenes
- configuran colores o tamaños

---

### `draw()`

Se ejecuta constantemente muchas veces por segundo.  

Aquí ocurre:
- el movimiento
- la animación
- la interacción

---

## Canvas

javascript id="7yz5iu"
createCanvas(700,700);
Colores
background()
background(0);

Sirve para darle color al fondo del canvas.

También se puede usar transparencia usando un cuarto valor.

Figuras geométricas

En p5.js se pueden crear figuras básicas como:

line()
rect()
ellipse()
triangle()
arc()

Estas figuras funcionan mediante coordenadas dentro del canvas.

Bordes y relleno
stroke()

Define el color del borde o línea.

strokeWeight()

Define el grosor de la línea.

fill()

Define el color interior de las figuras.

Conclusión

p5.js permite combinar programación y creatividad de una forma más visual y accesible.

Gracias a herramientas simples como figuras, colores, interacción y movimiento, es posible crear piezas gráficas interactivas usando código.
