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
Opción 1
```JavaScript
    export function calculateTip(billAmount, tipPercentage) {
      return billAmount * (tipPercentage / 100)
    }
```
Opción 2
```JavaScript
    export function calculateTip(billAmount, tipPercentage) {
      return billAmount * (tipPercentage / 100)
    }
```

## Reto 3
#### [Apuntes]()


### Respuesta:
```JavaScript

```
## Reto 4
#### [Apuntes]()


### Respuesta:
```JavaScript

```
## Reto 5
#### [Apuntes]()

### Respuesta:
```JavaScript

```
