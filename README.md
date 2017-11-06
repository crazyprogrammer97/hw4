# hw4int x1=0;
int y1=0;
int x =25;
int y= 25;
float mappedValue;
float mappedRad;
int multiplier = 1;


void setup() {

  size(600, 600);
  smooth();
}


void draw() {
  background(#FAFAFA);

for (int y1 = 0; y1 <= height; y1 += 20) {
for (int x1 = 0; x1 <= width; x1 += 20) {
  fill(#890606);
ellipse(x1,y1,15,15);
/*
if(mappedRad > 600) {
    multiplier = -1;
    println("greater than 400");
  }
  
  if(mappedRad < 0){
    multiplier = 1;
     println("lower than 0");
  }
mappedRad = mappedRad + 1 * multiplier; 

 
  ellipse(x1,y1,mappedRad,mappedRad);

}
}

*/  //hocam  patternı hareket ettirmek istedim
 //olmadı :(
    ellipse(300,300,x*20,y*20);
     ellipse(300,300,x*19,y*19);
      ellipse(300,300,x*18,y*18);
       ellipse(300,300,x*17,y*17);
        ellipse(300,300,x*16,y*16);
         ellipse(300,300,x*15,y*15);
          ellipse(300,300,x*14,y*14);
   ellipse(300,300,x*13,y*13);
   ellipse(300,300,x*12,y*12);
   ellipse(300,300,x*11,y*11);
  ellipse(300,300,x*10,y*10);
  ellipse(300,300,x*9,y*9);
  ellipse(300,300,x*8,y*8);
  ellipse(300,300,x*7,y*7);
  ellipse(300,300,x*6,y*6);
  ellipse(300,300,x*5,y*5);
  ellipse(300,300,x*4,y*4);
  ellipse(300,300,x*3,y*3);
  ellipse(300,300,x*2,y*2);
  fill(#FF1212);
ellipse(300,300,x,y);
if(mappedRad > 600) {
    multiplier = -1;
    println("greater than 400");
  }
  
  if(mappedRad < 0){
    multiplier = 1;
     println("lower than 0");
  }
mappedRad = mappedRad + 1 * multiplier; 

 
  ellipse(300,300,mappedRad,mappedRad);
  
 }
 
