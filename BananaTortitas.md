# Tortitas de Platano

## Ingredientes
```js
let platanos = 2🍌;

let arina = 2🥄;

let huevos = 2🥚;

let martequilla = 1🥄 ;

```

## Preparacion

```js
let cocinamos = new Promise((resolve, reject) => {
  setTimeout(function(){
    resolve("¡ Las tortitas estan listas 😱 !"); // ¡Todo salió bien!
  }, 50000);
});

function preparacion(){
  // Mezclamos nuestros ingredientes en un boule. 
  let mezcla = platanos + arina + huevos;
  // agregamos un poco de aceite y mantequilla al sarten.
  sarten = sarten + mantequilla + aceite;
  // Cuando el sarten este lo suficientemente caliente agregamos las bolitas de platano.
  if ( sarte + fuego == caliente ) {
      sarte += mezcla;       
      cocinamos.then((successMessage) => {
        console.log("¡Sí! " + successMessage);
        return tortitas;
      });      
  }
  return mezcla;
}

```

## Resultado:
