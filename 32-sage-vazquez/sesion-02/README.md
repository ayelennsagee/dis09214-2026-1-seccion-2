# sesión 01_02_03
# 01 Breve historia de la computación y el arte computacional

## Introducción

La computación no solo ha servido para hacer cálculos o resolver problemas técnicos, sino que también se transformó en una forma de crear arte, imágenes e interacción. Con el tiempo, distintas personas comenzaron a experimentar mezclando tecnología, diseño y creatividad.

---

## Primeros avances

Uno de los primeros antecedentes importantes fue el **Telar de Jacquard**, una máquina que utilizaba tarjetas perforadas para crear patrones en telas. Esto se considera uno de los primeros acercamientos a la lógica de programación.  

Más adelante aparecieron **Charles Babbage** y **Ada Lovelace**, quienes imaginaron máquinas capaces de seguir instrucciones. Ada Lovelace es considerada la primera programadora porque entendió que estas máquinas podían hacer mucho más que cálculos matemáticos.

---

## Arte y computación

Durante los años 60 comenzaron a aparecer artistas que usaban computadores para crear imágenes y obras visuales mediante programación.  

El computador empezó a verse no solo como una máquina técnica, sino también como una herramienta artística y experimental.

En esta época surgieron exposiciones importantes relacionadas con arte y tecnología, donde se mostraban obras creadas con sistemas computacionales.

---

## Nuevas herramientas digitales

Con el tiempo aparecieron herramientas que facilitaron la relación entre personas y computadores, como:

- el mouse
- las ventanas
- los programas para dibujar digitalmente

Todo esto ayudó a que la tecnología fuera más visual e interactiva.

---

## Processing y p5.js

Más adelante surgieron herramientas pensadas para enseñar programación de forma más simple a artistas y diseñadores.  

Primero apareció **Processing**, creado para hacer gráficos, animaciones e interacción visual mediante código.  

Después surgió **p5.js**, una herramienta más accesible y amigable para trabajar programación creativa en internet utilizando JavaScript.

Actualmente p5.js es muy utilizado para crear piezas visuales interactivas, arte digital y proyectos experimentales.

---

## Conclusión

La historia de la computación demuestra que programar no solo sirve para lo técnico, sino también para crear, experimentar y expresar ideas visualmente.  

Gracias a herramientas como Processing y p5.js, hoy es posible combinar arte, diseño y programación de una manera mucho más accesible y creativa.


---
#02 
# GitHub y Markdown

## ¿Qué es GitHub?

GitHub es una plataforma donde se pueden guardar proyectos, códigos y archivos en internet.  

Sirve para organizar trabajos, compartir proyectos y mantener versiones de los archivos mientras se van modificando.

También es muy utilizado para programación, diseño y proyectos colaborativos.

---

## ¿Qué es Markdown?

Markdown es una forma simple de escribir y ordenar texto usando símbolos.  

Se utiliza mucho en GitHub para crear archivos README, apuntes o documentación de proyectos.

Por ejemplo:

- `#` crea títulos
- `**texto**` pone texto en negrita
- `*texto*` pone texto en cursiva

---

## Formatos básicos en Markdown

### Títulos
# Título grande
## Subtítulo
### Texto más pequeño
**Negrita**

*Cursiva*

Listas 
- Elemento 1
- Elemento 2
- Elemento 3

1. Paso uno
2. Paso dos
3. Paso tres

Links e imágenes

Para agregar links:

[Nombre](https://url.com)


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

```javascript id="7yz5iu"
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
