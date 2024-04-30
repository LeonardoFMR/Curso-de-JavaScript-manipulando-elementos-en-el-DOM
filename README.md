# Curso-de-JavaScript-manipulando-elementos-en-el-DOM

Anotaciones del curso:

elemento.addEventListener(evento, callback);

Donde:
elemento: Es el elemento HTML al cual queremos asociar el evento.
evento: Es un string que representa el tipo de evento que queremos capturar.
callback: Es la función que se llamará cuando ocurra el evento.

Para crear un nuevo objeto 'Audio', simplemente podemos utilizar la siguiente sintaxis:

const audioElement = new Audio('ruta/del/archivo-de-audio.mp3');
Controles básicos de audio
play(): inicia la reproducción del audio.
pause: pausa la reproducción del audio.
currentTime: propiedad que devuelve o establece la posición actual de reproducción del audio, en segundos.
volume: propiedad que devuelve o establece el nivel de volumen del audio, variando de 0 a 1.
