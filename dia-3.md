# Ejercicios día 2

## Ejercicio 7

Crear un programa para una agencia de viajes, el usuario ingresa la ciudad de origen y la ciudad de destino, el valor del tiquete es 1000, y tiene los siguientes descuentos:
- Si la ciudad de destino es Medellin entonces el tiquete tiene 10% de descuento
- Si la ciudad de destino es Bogota tiene un 15% de descuento
- Si la ciudad de origen es Cartagena tiene un 5% de descuento
  
Los descuentos pueden ser acumulables sobre el valor total del tiquete (1000).

Imprimir el descuento total y el valor final del tiquete si tiene descuentos

Ejemplo 1:

Entradas:
```
Ciudad origen: Medellin
Ciudad destino: Bogota
```

Salidas:
```
Total descuento: 150
Valor del tiquete: 850
```

Ejemplo 2:

Entradas:
```
Ciudad origen: Cartagena
Ciudad destino: Bogota
```

Salidas:
```
Total descuento: 200
Valor del tiquete: 800
```

## Ejercicio 8

Crea una variable llamada `usuario` de tipo objeto literal con las siguientes llaves y valores:

- `nombre` - "Pedro Perez"
- `edad` - 30
- `activo` - true
- `hobbies` - un arreglo con los siguientes elementos: "programar", "piano".

Ahora haz lo siguiente:

1. Imprime en consola el valor de la llave `edad`.
2. Agrega una propiedad con llave `estatura` y valor `1.8`.
3. Elimina la propiedad con llave `activo`.
4. Agrega el hobbie "leer" al arreglo de hobbies.
5. Recorre todas las propiedades e imprímelas en consola (una línea por propiedad y separando la llave y el valor con dos puntos `:`).

El resultado en consola debería ser parecido al siguiente (puede que las propiedades no salgan en el mismo orden):

```
30
nombre: "Pedro Perez"
edad: 30
hobbies: ["programar", "piano", "leer"]
estatura: 1.8
```

## Ejercicio 9

Obtener la el nombre y la edad de las personas que hablen inglés (EN) de un arreglo de 5 objetos Persona. Cada elemento del arreglo tiene la siguiente estructura:

```
[{
  nombre: "Juana",
  sexo: "F",
  edad: 30,
  idiomas: ["EN","ES"]
},{
  nombre: "Mario",
  sexo: "M",
  edad: 20,
  idiomas: ["ES"]
},{
  nombre: "Carla",
  sexo: "F",
  edad: 31,
  idiomas: ["EN"]
}, ...]
```

Respuesta:
```
Juana: 30
Carla: 31
```
