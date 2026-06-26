# sesión 11

# SONIDO Y SINTESIS DE AUDIO 
Subir el sonido: Agregar un archivo .mp3 o .wav al proyecto, preferiblemente dentro de una carpeta llamada assets.
Cargar el sonido: Declarar una variable global y cargar el archivo con loadSound() dentro de preload(), para que esté listo antes de ejecutar el programa.
Reproducir el sonido: Se usa play(), aunque lo más recomendable es activarlo con mousePressed() para evitar restricciones del navegador.
Controlar el sonido: Funciones principales:

## play() → reproduce.

## loop() → repite en bucle.

## pause() → pausa.

## stop() → detiene.

## setVolume() → cambia el volumen.

## rate() → cambia la velocidad.

Consultar el estado: Se pueden usar funciones como isPlaying(), currentTime(), duration(), getVolume() y getRate() para obtener información del audio.
Síntesis de audio: Con p5.sound() es posible crear sonidos desde código mediante un oscilador, controlando la frecuencia (tono) y la amplitud (volumen).
