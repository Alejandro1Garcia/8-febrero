//# 8-febrero
//1. Generación de números aleatorios y uso de funciones para mostrar las diferentes caras de un dado.

var num;
function setup() {
  createCanvas(400, 400);
}

function draw() {
  	num =int(random(1, 7));
	if(mouseIsPressed){
		if(num==1){
			uno();
		}
		if(num==2){
			dos();
		}
		if(num==3){
			tres();
		}
		if(num==4){
			cuatro();
		}
		if(num==5){
			cinco();
		}
		if(num==6){
			seis();
		}
	
}
}
	
function uno(){
	background(220);
	strokeWeight(20);
	rect(100,100,200,200);
	ellipse (200, 200, 10, 10);
	
}
function dos(){
	background(220);
	strokeWeight(20);
	rect(100,100,200,200);
	ellipse (150, 150, 10, 10);
	ellipse (250, 250, 10, 10);
}
function tres(){
	background(220);
	strokeWeight(20);
	rect(100,100,200,200);
	ellipse (150, 150, 10, 10);
	ellipse (250, 250, 10, 10);
	ellipse (200, 200, 10, 10);
}
function cuatro(){
	background(220);
	strokeWeight(20);
	rect(100,100,200,200);
	ellipse (150, 150, 10, 10);
	ellipse (150, 250, 10, 10);
	ellipse (250, 250, 10, 10);
	ellipse (250, 150, 10, 10);

}
function cinco(){
	background(220);
	strokeWeight(20);
	rect(100,100,200,200);
	ellipse (150, 150, 10, 10);
	ellipse (150, 250, 10, 10);
	ellipse (250, 250, 10, 10);
	ellipse (250, 150, 10, 10);
	ellipse (200, 200, 10, 10);

}
function seis(){
	background(220);
	strokeWeight(20);
	rect(100,100,200,200);
	ellipse (150, 150, 10, 10);
	ellipse (150, 250, 10, 10);
	ellipse (250, 250, 10, 10);
	ellipse (250, 150, 10, 10);
	ellipse (150, 200, 10, 10);
	ellipse (250, 200, 10, 10);


}
