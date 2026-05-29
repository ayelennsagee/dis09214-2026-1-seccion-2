# sesión 06 - 29/05
---
# repaso DIAGRAMA DE FLUJO 
---
- el diagrama de flujo es una representacion grafica del algoritmo 
- se suele hacer antes de hacer las lineas código
- se usan simbologías, tales como el rombo para ciertas cosas etc.
---
### simbología 
- el inicio se pone con un ovalo
- los condicionales son lo rombos, el si o no

## ARRAY (LISTAS)
Es un contenedor donde podemos guardar múltiples datos **{array}** 
### Sintaxis
- let nombreArray = [e0, e1, e2, e3, e4, e5]
- `let colores = ["red", "orange", "green", "blue"]`
---
- ejemplo de la profe, la variable `index` netamente es para que al definirlo que nuestra variable array que creemo recorra todos sus elementos
formato `markdown`

```let Colores = ["red", "orange", "yellow", "green", "blue", "purple"];
let index = 0; 

function setup() {
  createCanvas(400, 400);
  frameRate(1);
}

function draw() {
  //background(Colores[5]);
  
  
  background(Colores[index]); //Acá decimos que nuestra variable Colores se verá intervenido por la variable Index
  index = index + 1; //Acá decimos que index variable que recorre todos los colores de la variable Colores vaya en movimiento colocandole +1, le damo como la función

  if (index >= Colores.length) {
  index = 0; 
 }
}```

