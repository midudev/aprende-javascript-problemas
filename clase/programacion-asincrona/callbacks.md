# Callbacks

Los callbacks son uno de los conceptos fundamentales de la programación asíncrona en JavaScript.

## ¿Qué es un callback?

- Son **funciones que se pasan como parámetros a otras funciones**
- Se ejecutan una vez que la función que las recibe ha terminado su tarea
- Permiten controlar el flujo de ejecución asíncrono

## Ejemplo

```javascript
function saludar(nombre, callback) {
  console.log('Hola, ' + nombre)
  callback()
}

saludar('Mundo', function () {
  console.log('¡Callback ejecutado!')
})
```

## Más información

[Programación asíncrona con callbacks](https://www.aprendejavascript.dev/clase/programacion-asincrona/callbacks)
