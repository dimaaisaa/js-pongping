let chanceDeErrar = 0;

//sons do jogo
let ponto;
let raquetada;
let trilha;

function preload (){
  trilha = loadSound ("trilha.mp3");
  ponto = loadSound ("ponto.mp3");
  raquetada = loadSound ("raquetada.mp3");
}

//contar pontos
let minhaPontuação = 0;
let pontuaçãoOponente = 0;

//variáveis da bolinha
let xBolinha = 200;
let yBolinha = 200;
let diametro = 20;
let raio = diametro / 2;

//velocidade da bolinha
let velocidadeXBolinha = 6;
let velocidadeYBolinha = 6;

//variáveis da raquete
let xRaquete = 5;
let yRaquete = 150;
let raqueteComprimento = 10;
let raqueteAltura = 90;

let colidiu = false;

//variáveis do oponente
let xRaqueteOponente = 585;
let yRaqueteOponente = 150;
let velocidadeYOponente;

function setup() {
  createCanvas(600, 400);
}

function draw() {
  background(0);
   stroke('white');
  strokeWeight(2);

  line(305, 400, 300, 1);
  bolinhaAparece();
  bolinhaMovimenta();
  verificaBolinhaBorda();
  raqueteAparece(xRaquete, yRaquete);
  raqueteMovimentaM();
  verificaColisaoRaquete(xRaquete, yRaquete);
  colisaoMinhaBB();
  raqueteAparece (xRaqueteOponente, yRaqueteOponente);
  movimentaRaqueteOponente();
  verificaColisaoRaquete();
  colisaoOponenteBB();
  mostraPlacar();
  marcaPonto();
}

function bolinhaAparece() {
  circle(xBolinha, yBolinha, diametro);
}

function bolinhaMovimenta() {
  xBolinha += velocidadeXBolinha;
  yBolinha += velocidadeYBolinha;
}

function verificaBolinhaBorda() {
  if (xBolinha + raio > width || xBolinha - raio < 0) {
    velocidadeXBolinha *= -1;
  }
  if (yBolinha + raio > height || yBolinha - raio < 0) {
    velocidadeYBolinha *= -1;
  }
}

function raqueteAparece(x,y) {
  rect(x, y, raqueteComprimento, raqueteAltura);
}

function raqueteMovimentaM() {
  
  if(keyIsDown(UP_ARROW)) {
    yRaquete -= 10;
  }
  if(keyIsDown(DOWN_ARROW)) {
    yRaquete += 10;
  }
  
  }
   function verificaColisaoRaquete() {
    colidiu = collideRectCircle(xRaquete,yRaquete,raqueteComprimento, raqueteAltura, xBolinha, yBolinha, raio);
    if (colidiu){
        velocidadeXBolinha *= -1;
      raquetada.play();
    }

   }
//bb = minha raquete biblioteca
function colisaoMinhaBB () {
  colidiu = collideRectCircle(xRaquete, yRaquete, raqueteComprimento, raqueteAltura, xBolinha, yBolinha, raio);
  if (colidiu) {
    velocidadeXBolinha *= -1; 
    raquetada.play();
  }
}

function movimentaRaqueteOponente(){
   velocidadeYOponente = yBolinha -yRaqueteOponente - raqueteComprimento / 2 - 30;
  yRaqueteOponente += velocidadeYOponente + chanceDeErrar
  calculaChanceDeErrar();
}
 
  function colisaoOponenteBB() {
    colidiu = collideRectCircle(xRaqueteOponente,yRaqueteOponente,raqueteComprimento, raqueteAltura, xBolinha, yBolinha, raio);
    if (colidiu){
        velocidadeXBolinha *= -1;
      raquetada.play();
    }
}

function mostraPlacar (){
  stroke (255);
  textAlign (CENTER);
  textSize (20);
  fill (color(128,0,128));
  rect (130,9,40,20);
  fill(255);
  fill (color(128,0,128));
  rect (430,9,40,20);
  fill (255);
  fill (300);
  text (minhaPontuação, 150,26);
  text (pontuaçãoOponente, 450, 26);
}
function marcaPonto (){
  if (xBolinha > 590) {
    minhaPontuação += 1;
    ponto.play();
  }
  if (xBolinha < 10) {
    pontuaçãoOponente += 1;
    ponto.play();
  }
}
function calculaChanceDeErrar() {
  if (pontuaçãoOponente>= minhaPontuação) {
    chanceDeErrar += 1
    if (chanceDeErrar >= 39){
    chanceDeErrar = 40
    }
  } else {
    chanceDeErrar -= 1
    if (chanceDeErrar <= 35){
    chanceDeErrar = 35
    }
  }
}



 
    
  
  
  
  
  



