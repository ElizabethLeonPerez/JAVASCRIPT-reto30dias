# Condicionales

## IF
La estructura de control `if` sirve para tomar decisiones en función de si una determinada condición es verdadera o falsa. El código dentro de un bloque `if` sólo se ejecutará si la condición es verdadera, mientras que el código en un bloque `else` sólo se ejecutará si la condición es falsa.

``` Javascript
    if (condicion) {
      // código a ejecutar si la condición es verdadera
    } else {
      // código a ejecutar si la condición es falsa
    }
```

También es posible utilizar varias condiciones en una estructura `if` utilizando la palabra clave `else if`.
``` Javascript
    let calificacion = 75;

    if (calificacion >= 90) {
      console.log("Obtuviste una A");
    } else if (calificacion >= 80) {
      console.log("Obtuviste una B");
    } else if (calificacion >= 70) {
      console.log("Obtuviste una C");
    } else {
      console.log("Obtuviste una calificación insuficiente");
    }
```
