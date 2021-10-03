# Taller de JavaScript

***

## Ejercicio 2

```javascript
var primero = prompt("Primer número")
var segundo = prompt("Segundo número")
var suma = Number(primero) + Number(segundo) 
console.log("La suma de ambos números: " + suma)
```

## Ejercicio 4

```javascript
var km = prompt("Kilómetros recorridos: ")
var lt = prompt("Litros de combustible gastados: ")
var consumo = Number(km) / Number(lt) 
console.log("El consumo por kilómetro es de: " + consumo)
```

## Ejercicio 6

```javascript
var primero = Number(prompt("Primer número: "))
var segundo = Number(prompt("Segundo número: "))
var tercero = Number(prompt("Tercero número: "))
var promedio = (primero + segundo + tercero) / 3
console.log("El promedio de los números es: " + promedio)
```

## Ejercicio 8

```javascript
var primera = prompt("Primera palabra")
var segunda = prompt("Segunda palabra")
console.log(primera + " " + segunda)
```

## Ejercicio 10

```javascript
var shows = Number(prompt("Shows vistos el último año: "))
var mas_de_3 = shows > 3
console.log(mas_de_3)
```

## Ejercicio 12

```javascript
var fecha = Number(prompt("Ingrese la fecha en formato DDMMAAAA: "))
var aaaa = fecha % 10000
fecha /= 10000
var mm = fecha % 100
fecha /= 100
var dd = fecha
console.log(dd + "/" + mm + "/" + aaaa)
```