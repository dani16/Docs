# Arrays

- Son estructuras que nos permiten almacenar varios datos y agruparlos.
- Se pueden llenar con cualquier tipo de dato válido en JavaScript y deben ir separados por comas
- Se pueden mezclar tipos de datos, pero no es recomendable.
- Se declaran con llaves cuadradas o corchetes []
- Pueden declararse vacíos o con un contenido ya establecido
- Pueden añadirse o eliminarse elementos en el momento que queramos
- En Javascript array no es un tipo de datos, si no que son objetos que poseen métodos para iterarlos. Los objetos no tienen estos métodos

# Creation

```js
const array = [1, 2, 3, 4];
const array = ["a", "b", "c", "d"];
```

Crear array con un determinado numero de elementos

```js
const array = Array(5); // [empty x 5]
```

En Js, podemos crear array con distintos tipos de datos.

```js
const myArray = [
  "Hola",
  5,
  true,
  undefined,
  { a: 2, b: 3 },
  () => "Hola",
  [1, 2, 3],
];

console.log(myArray);
```

# Access to array elements

```js
console.log(myArray[0]); // Devuelve la primera posicion del array
```

# Modify array elements

```js
myArray[3] = "Pepe";
console.log(myArray);
```
