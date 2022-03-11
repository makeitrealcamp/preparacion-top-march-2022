# Ejercicios día 4

## Ejercicio 10
Crea una función llamada `max` que reciba un arreglo de números como argumento y retorne el número mayor.

**Nota:** No utilices el método `Math.max` de JavaScript.

```javascript
// escribe tu solución acá
// código de prueba
console.log(max([1, 2, 3, 4])) // 4
console.log(max([63, 85, 39, 24, 3])) // 85
```

## Ejercicio 11
Crea una función llamada `diasDelMes` que reciba el nombre de un mes del año (en minúsculas) y retorne la cantidad de días que tiene el mes.

```javascript
// escribe tu solución acá

// código de prueba
console.log(diasDelMes("enero")) // 31
console.log(diasDelMes("febrero")) // 28
```

## Ejercicio 12
El factorial de un número entero n es una operación matemática que consiste en multiplicar todos los factores n x (n-1) x (n-2) x ... x 1. Así, el factorial de 5 (escrito como 5!) es igual a: 5! = 5 x 4 x 3 x 2 x 1 = 120.

Escribir una función llamada `factorial` que reciba un número n, y retorne el factorial de ese número.

```javascript
// escribe tu solución acá

// código de prueba
console.log(factorial(5)) // 120
console.log(diasDelMes(3)) // 6
```

## Ejercicio 13
Escribe una función llamada `preciosProductos` que reciba 2 datos:
- Un arreglo de objetos que reciba arreglo de objetos (que representan productos).
- Un número que representa el valor máximos de los productos que quiero

Y retorna un nuevo arreglo con los nombres de los productos cuyo precio es menor al dato ingresado por el usuario. Si no hay ningún producto con un precio menor al dato ingresado entonces retornar un mensaje `"No hay productos que cumplan con la condición"`

```javascript
// escribe tu función acá
// código de prueba
let prods = [
  { nombre: "Arroz", precio: 5 },
  { nombre: "Pan", precio: 3 },
  { nombre: "Tomate", precio: 8 },
  { nombre: "Leche", precio: 15 }
];
console.log(productosBaratos(prods, 7)); // ["Arroz", "Pan"]
console.log(productosBaratos(prods, 3)); // No hay productos que cumplan con la condición
```
