# Diario de programacion
## Algunas aclaraciones
Este diario cumple algunos atrasos, es una idea de ahora, improvisado para mi.

#### 17/05/2017
Despues de varios intentos fallidos de intentar estudiar y buscar otros caminos para la programacion llegue a la conclusion de que es casi imposible iniciar de cero algo que quiero. O sea, abri una cuenta en Open Source Society y me fue bien pero senti la inclincion de terminar primero FreeCodeCamp y luego seguir avanzando alli.
Hace exactamente 4 años que inicié mi camino hacia la programacion con un burdo .html que hoy ya domino medio bien pero sin embargo necesito seguir. Ahora, para no caer pesado, debo volver a repasar Javascript desde el principio para poder ponerme a tope con FCC.

##### String
Pero la conchasumadre string y la porqueria que no se puede cambiar, sino que tenes que crear una variable nueva. Alguien por favor lo actualiza asi podemos cambiar cuando querramos? Gracias


#### 18/05/2017
Tengo la mente dispersa y encima estoy re-aprendiendo arrays. Es algo dificil de digerir, dado que deje casi 2 semanas y ahora que retomo, tengo una laguna mental alli.


```javascript
function reusableFunction() {
  console.log("Hi world");
}

reusableFunction();
```

Despues esta `push`, `shift`, `unshift` y `shift`

#### 05/07/2017

Hice nuevamente el Code Golf y esta vez lo hice solo. Para aclarar, una vez lo hice con ayuda, ahora con media ayuda por que fui puliendo mi propio camino. 

```javascript
function golfScore(par, strokes) {
  // Only change code below this line
  if (strokes == 1)
    return "Hole-in-one!";
  else if (strokes <= par -2)
    return "Eagle";
  else if (strokes == par -1)
    return "Birdie";
  else if (strokes == par)
    return "Par";
  else if (strokes == par +1)
    return "Bogey";
  else if (strokes == par +2)
    return "Double Bogey";
  else return "Go Home!";
  ```
  
  Me costo pero I did it..
