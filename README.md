# JAVASCRIPT - Reto 30 días
Reto de 30 días para resolver 30 problemas en JavaScript. 


### Reto 1

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
#### Respuesta:
```JavaScript
export function solution(valor) {
  return typeof valor;
}
```
### Reto 2
