function setup() {
  createCanvas(400, 400);
}

function colorir(){
  background(color(random(0, 255), 0, random(255, 0)));
  fill("white")
  textSize(55)
  textAlign(CENTER, CENTER)
}

function draw() {
  colorir();
  let minimo = 0
  let maximo = width
  let palavra ="wildest dreams"
  let quantidade = map(mouseX, 0, width, 1, palavra.length)
  let parcial = palavra.substring(0,quantidade);
  text(parcial, 200, 200)
}