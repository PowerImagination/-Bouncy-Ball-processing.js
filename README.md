# -Bouncy-Ball-processing.js

var y = 0;
var speed = 2;
void draw() {
  background(51);
  fill(250,250,0);
  ellipse(50, y, 20, 20);
  
   if (y > 98){
   speed = -2;
   }
   if (y < 0){
   speed = 2;
   }
   y = y+speed;
    }
    
