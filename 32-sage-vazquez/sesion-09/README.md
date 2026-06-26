# sesión 09 - 05/06

# CÓMO ENTENDER LA LÓGICA DE CREAR ESTADOS 
---
1. ## Estados

Aprendimos a utilizar una variable de estado para controlar qué pantalla o escena se muestra en cada momento.
Los estados permiten organizar mejor una experiencia interactiva separando cada parte del proyecto en funciones distintas.
Se pueden controlar mediante estructuras condicionales como if o switch.

2. ## Cambio de estados

Vimos distintas formas de pasar de un estado a otro.
Una de ellas es mediante clics del mouse sobre la pantalla.
Otra opción es utilizar botones HTML creados con p5.js, lo que permite generar interfaces más ordenadas y profesionales.

3. ## Zonas de clic

También se pueden crear botones dibujados con figuras como rect() o ellipse().
Para ello se evalúa si el mouse se encuentra dentro de una zona determinada cuando ocurre el clic.

4. ## Interacciones automáticas

Se revisó el uso de temporizadores para cambiar de estado automáticamente después de un tiempo determinado.
Esta técnica es útil para pantallas de introducción o transiciones automáticas.

5. ## Interacción con el mundo físico

Se introdujo el concepto de utilizar dispositivos físicos del computador como fuente de interacción.
En esta clase se trabajó específicamente con la cámara web.

6. ## Cámara web en p5.js

Aprendimos a activar la cámara mediante createCapture(VIDEO).
Se explicó cómo definir una variable para almacenar la captura de video.
También vimos cómo configurar su tamaño y ocultar la ventana de video original utilizando hide().

7. ## Dibujar la cámara en el lienzo

La imagen capturada por la cámara puede mostrarse dentro del canvas utilizando image().
Esto permite integrar el video en tiempo real dentro de experiencias interactivas y proyectos creativos.

8. ## Ejemplos de aplicaciones

Se mostraron ejemplos de filtros visuales.
Manipulación de píxeles mediante loadPixels().
Sistemas interactivos que reaccionan al sonido o a la presencia del usuario.
Aplicaciones creativas que combinan cámara, imagen y programación interactiva.

9. ## Aplicación al proyecto

Estos contenidos permitieron construir una experiencia basada en estados, donde cada pantalla presenta una interacción diferente.
Además, se incorporó la cámara web y el reconocimiento facial para generar una respuesta visual en tiempo real según la posición del rostro de la usuaria.
