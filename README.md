# Aulas2024
Repositório para as aulas do Alura e Scrath
function setup() {
  createCanvas(600, 600);
}

function draw() {
  background("pink");
  fill("red");
  textSize(64);
  textAlign(CENTER, CENTER);
  
  let maximo = width;
  let minimo = 0;
  // mouseX, 0, width ==> 0, palavra.length
  let palavra = " Ayla";
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0, quantidade);
  text(parcial, 300, 100);
  
  
}
