# sesión 05 - 17/04

# Transformaciones y condicionales en p5.js
### ¿Qúe son las Radianes?


El documento explica cómo transformar figuras y utilizar lógica condicional en p5.js para crear composiciones más dinámicas e interactivas.

Primero se introducen los radianes y los ángulos. p5.js trabaja por defecto con radianes usando `angleMode(RADIANS)`, aunque también se puede cambiar a grados con:

```js
angleMode(DEGREES);
```

Se presentan referencias importantes como:
- `PI`
- `HALF_PI`
- `QUARTER_PI`
- `TWO_PI`

Luego las transformaciones principales.

La función `rotate()` sirve para rotar elementos alrededor del punto de origen `(0,0)`.

Ejemplo:
```js
rotate(20);
```

La función `translate()` mueve el punto de origen a otra posición del canvas.

Ejemplo:
```js
translate(200, 200);
```

También se enseñan las funciones `push()` y `pop()`, que funcionan como una memoria temporal para guardar y restaurar transformaciones y estilos del lienzo.

Ejemplo:
```js
push();
// transformaciones
pop();
```

La función `scale()` permite cambiar el tamaño de los elementos aumentando o reduciendo su escala.

Ejemplo:
```js
scale(2,2);
```

Después el documento introduce la lógica condicional y las expresiones booleanas, las cuales solo pueden devolver dos resultados:
- `true`
- `false`

Se explican operadores de comparación como:
- `==`
- `!=`
- `<`
- `>`
- `<=`
- `>=`

Y operadores lógicos como:
- `&&` (AND)
- `||` (OR)
- `!` (NOT)

Ejemplo:
```js
2 < 3 // true
2 == 2 // true
```

Luego se presenta la estructura condicional `if`, que permite ejecutar código dependiendo de una condición.

Ejemplo:
```js
if (condicion) {
  // código
}
```

También se explica el uso de:
- `else if`
- `else`

para agregar más posibilidades dentro de una misma decisión.

Ejemplo:
```js
if (condicion1) {

} else if (condicion2) {

} else {

}
```

ENCARGO DESAFÍO CLASE
https://editor.p5js.org/ayelennsagee/sketches/dJfuCy7CY
