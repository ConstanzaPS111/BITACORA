# BITACORA
bitacora workshop

// doble eslash para tomar apuntes, esto no afecta a la programación. (2024 workshop) 
let velocidadX;

let direccionX;

let positionX;

function setup() {
  createCanvas(900, 400);
  //Tamaño del lienzo.
  posicionX = 100;
  posicionY = 200;
  velocidad = 3
  direccion = 5;
  ancho = 50
}

function draw() {
  background(243, 202, 215);
  //Color del fondo, lienzo 
  
  
  ellipse(posicionX, posicionY, ancho, 50);
   
   posicionX = posicionX + velocidad;
  //crean el movimiento y velocidad

  console.log(posicionX);


  if (posicionX > width - ancho/2) {
  direccion = 20;
  }
  else if (posicionX < width - ancho*2){
    direccion = 20
  }

}
