# jin
//1st Day of ICM

function setup() {
  createCanvas(400,400);
  background(133,82,128);//(30,225,234);
  noStroke(0);
 
  //face
  fill(129,47,30);
  ellipse(115,150,95,110);
  fill(89,22,0,52);
  //background
  
  fill(29,147,30,20);
  ellipse(2,150,125,10);
  ellipse(255,87,60,80);

  
    //body
  fill(249,147,30);
  ellipse(146,235,123,200);
  fill(249,47,30);
  ellipse(86,235,73,50);
  
  fill(129,172,130);
  ellipse(42,35,173,150);
  
  //plate
  fill(249,147,80,115);
  ellipse(86,245,60,45);
  //shade plate
  fill(249,147,80,115);
  ellipse(86,245,60,45);
  
   
  
  //left eyes
  fill(255);
  ellipse(93,150,12,25);
  fill(0);
  ellipse(93,150,12,12);
  //right eyes
  fill(255);
  ellipse(140,150,12,30);
  fill(0);
  ellipse(140,150,12,12);
  
  //nose
  fill(0);
  ellipse(110,170,14,9);
  //mouse
  fill(255,87,60);
  arc(100, 190, 37, 27, 0, PI+QUARTER_PI, CHORD);
  fill(255,37,70);
  arc(100, 190, 27, 17, 0, PI+QUARTER_PI, CHORD);
  
  //ears
  fill(129,67,170);
  rect(125,55,45,45);
  fill(129,47,30);
  rect(85,85,15,15);
  
  fill(129,47,30);
  rect(125,85,15,15);
  fill(129,67,170,54);
  rect(55,55,45,45);
  

  //2nd eyes
 
  fill(255);
  ellipse(300,150,25,12);
  fill(120,45,240);
  ellipse(300,150,12,12);
  
   fill(255);
  ellipse(340,150,25,12);
  fill(120,45,240);
  ellipse(340,150,12,12);
  
  //2nd body
  fill(39,67,30);
  ellipse(246,215,83,70);
  fill(79,197,30);
  ellipse(346,235,123,100);
  fill(169,47,30);
  ellipse(276,235,73,110);
  
  //table
  fill(29,147,30);
  rect(9,247,230,30);
  fill(29,147,30);
  rect(9,279,230,10);
  //table legs
  fill(29,147,30);
  rect(9,279,10,230);
  
  fill(29,147,30);
  rect(230,247,10,155);
  
  fill(129,347,30);
  rect(340,155, 5, 25);
  //triangle(340,155, 8, 80, 86,75);
}
  
function draw() {
  
}
