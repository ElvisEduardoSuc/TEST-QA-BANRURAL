# Plan de ataque
Durante la revisión de los posibles errores que habrían en el proyecto, el ver la consola del navegador web, leer y entender bien los requerimientos de la lógica del juego hace más fácil cambiar/arreglar dichos errores.

| No. Linea | Descripción del error | Solución respectiva |
| --- | --- | --- |
| 44 | La variable randomNumber solo podía tomar números de 1 a 10 y devolvía números decimales entre ese rango. | Se cambió el rango de valores hasta 100 y se redondió el número para que solo tomarán números enteros. |
| 45 | ATTEMPS = 5, indica las veces que se puede adivinar el número, y las instruciones indicaban otro número. | Se cambió ATTEMPS=5 a ATTEMPS=10, que es el número de intentos que se pueden probar para adivinar el número |
| 48 | Al momento de indicar a que clase se le hace referencia, faltaba signo. | Al hacer referencia a la clase lowOrHi dentro del querySelector faltaba el punto(.) para invocar correctamente la clase. |
| 58 | Teniamos que corroborar que algunos requerimientos que indicaban en las instrucciones se cumplieran. | Se hizo una condición que confirmaba que el valor ingresado por el usuario estuviera entre 1 y 100, que fuera un número y no una palabra, y que fuera un número entero y positivo. |
| 58 | Teniamos que corroborar que algunos requerimientos que indicaban en las instrucciones se cumplieran. | Se hizo una condición que confirmaba que el valor ingresado por el usuario estuviera entre 1 y 100, que fuera un número y no una palabra, y que fuera un número entero y positivo. |
| 59 | No había alerta para indicar si el valor era entero | Se creo el alert() indicando si el valor no estaba correctamente ingresado cumpliendo con alguna de las validaciones de la linea anterior. |
| 66 | No comparaba correctamente los datos. | Se cambio de triple igual(===) a doble igual (==) para poder hacer correctamente la comparación, ya que triple igual comparaba el tipo de dato de la variable mientras que doble igual compara el valor.
| 67, 72 | Los mensajes no estaban correctamente ubicados correctamente. | Se cambio los mensajes de "Felicitaciones" y "Perdiste" a sus condiciones correspondientes, ya que según el tipo de mensaje no encajaba con la condición. |
| 68, 77 | Los colores que se mostraban no eran los correspondientes. | Los colores según la condición no era lo que correspondia, cuando adivinaba el usuario el número se cambio de negro a verde, y cuando el valor ingresado no era el que tenía que adivinar y aún le quedaban intentos se cambio el color del mensaje de verde a negro. |
| 89, 97 | El nombre del método de guessSubmit no estaba escrito correctamente. | Se cambió el nombre del método addEventListener estaba mal escrito.|
| 115 | Para obtener un número random solo devolvía el valor de 1. | Se cambio el valor de randomNumber para que pudiera devolver un valor random entre 1 y 100, cambiando el rango y haciendo que esta solo devolviera valores enteros. |