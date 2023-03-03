# Reto 1: Notas

## Funciones: 
Se usan para realizar una tarea específica y pueden recibir uno o más argumentos y pueden devolver un valor como resultado.

``` Javascript
    function miFuncion(parametro1, parametro2) {
    // Código de la función
}
```

## Null: 
Representa un valor vacío o nulo.

``` Javascript
    const nombre =null;
    console.log(nombre); // imprime "null"
```
## Undefined: 
Representa un valor que aún no ha sido asignado o que no tiene un valor válido.

``` Javascript
    let nombre;
    console.log(nombre); // imprime "undefined"
```
## Symbol: 
Se utiliza para crear valores únicos e inmutables que se pueden utilizar como identificadores de propiedades de objetos.
Un Symbol se crea usando la función Symbol(). Cada símbolo que se genera es único y no se puede duplicar, lo que lo hace ideal para evitar colisiones de nombres de propiedades en objetos.

``` Javascript
    const propiedad1 = Symbol(); // declaración de Symbol 1
    const propiedad2 = Symbol(); // declaración de Symbol 2

    let obj = {}; // declaración de objeto

    obj[propiedad1] = "Valor de la propiedad 1"; // asignaión de propiedad
    obj[propiedad2] = "Valor de la propiedad 2"; // asignaión de propiedad

    console.log(obj[propiedad1]); // "Valor de la propiedad 1"
    console.log(obj[propiedad2]); // "Valor de la propiedad 2"
```
## BigInt: 
Se utiliza para representar números enteros de tamaño arbitrario.
BigInt se crea mediante la adición del sufijo n a un número entero literal o utilizando la función BigInt().

``` Javascript
    const entero1 = 9007199254740991n; // declaración Bigint con 'n'
    const entero2 = BigInt("9007199254740992"); // declaración Bigint con 'función'

    console.log(typeof entero1); // "bigint"
    console.log(typeof entero2); // "bigint"

    const suma = entero1 + entero2;
    console.log(suma); // 18014398509481983n
```