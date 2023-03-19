# JAVASCRIPT - Reto 30 días
Reto de 30 días para resolver 30 problemas en JavaScript. 


## Reto 1
#### [Apuntes](https://github.com/ElizabethLeonPerez/JAVASCRIPT-reto30dias/blob/420e092506b71be2a27bf8224cae5023847686b6/Notas-Reto1.md)

En este desafío encontrarás una función llamada `solution` que recibe un parámetro llamado `valor`. Debes encontrar el tipo de dato del parámetro `valor` y retornarlo desde la función `solution`.

Recuerda que el parámetro `valor` será distinto por cada distinta forma en que ejecutemos la función `solution`.

Dados los siguientes llamados a la función `solution`:
```JavaScript
  solution(1)
  solution("Dieguillo")
  solution(true)
```
Debes obtener los siguientes resultados:
```JavaScript
"number"
"string"
"boolean"
```
### Respuesta:
```JavaScript
export function solution(valor) {
  return typeof valor;
}
```

## Reto 2
#### [Apuntes]()

En este desafío tendrás que calcular la propina que deben dejar los clientes de un restaurante en función de su consumo.

Recibirás 2 parámetros:

- billAmount: El costo total de lo que hayan consumido.
- tipPercentage: El porcentaje de propina que deban dejar.
- Ambos valores serán de tipo Number.
- Los valores serán siempre positivos incluyendo el 0.
- deberá devolver el valor de la propina como un número.
Tendrás inputs y outputs como los siguientes 👇

Ejemplo 1:
```JavaScript
Input: calculateTip(100, 10);
Output: 10;
```
Ejemplo 2:
```JavaScript
Input: calculateTip(1524.33, 25);
Output: 381.0825;
```

### Respuesta:
```JavaScript
    export function calculateTip(billAmount, tipPercentage) {
      return billAmount * (tipPercentage / 100)
    }
```

## Reto 3
#### [Apuntes]()

En este desafío, debes crear la lógica de la función isLeapYear, que determina si un año es bisiesto o no. Un año es bisiesto si cumple con las siguientes condiciones:

Es divisible por 4, pero no por 100.
Si es divisible por 100 debe serlo por 400 también.
La función isLeapYear recibe un único parámetro: el año a evaluar. Debe devolver true si el año es bisiesto o false en caso contrario.

Toma en cuenta que la función debe ser capaz de manejar valores no enteros o negativos.

Ejemplo 1:
``` Javascript
Input: 2000;
Output: true;
```

Ejemplo 2:
``` Javascript
Input: -2024;
Output: false;
```

Ejemplo 3:
``` Javascript
Input: 1984.25;
Output: false;
```

### Respuesta:
```JavaScript

```
## Reto 4
#### [Apuntes]()


### Respuesta:
<!-- ```JavaScript
  export function isLeapYear(year) {
    if (year < 0 && Number.isNaN(year) && Number.isInteger(year)) {
      if (year % 4 === 0)
        return true
    }
    if (year % 100 === 0 && year % 400 === 0) {
      return true
    }
    if (year % 100 === 0) {
      return false
    }
    else {
      return false
    }
  }

export function isLeapYear(year) {
  if (year < 0 && Number.isNaN(year) && Number.isInteger(year)) {
    if (year % 4 === 0 && (year % 100 !=== 0))
    return true
  }
  else if (year % 100 === 0 && year % 400 === 0) {
    return true
  }
  else {
    return false
  }
}
``` -->
## Reto 5
#### [Apuntes]()

### Respuesta:
```JavaScript

```

## Reto 6
#### [Apuntes]()

### Respuesta:
```JavaScript

```

## Reto 7
#### [Apuntes]()

### Respuesta:
```JavaScript

```

## Reto 8
#### [Apuntes]()

### Respuesta:
```JavaScript

```

## Reto 9
#### [Apuntes]()

### Respuesta:
```JavaScript

```

## Reto 10
#### [Apuntes]()

### Respuesta:
```JavaScript

```

## Reto 11
#### [Apuntes]()

### Respuesta:
```JavaScript

```
