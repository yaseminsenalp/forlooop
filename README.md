int a = 50;

void setup(){
  size(500,150);
}

void draw(){
  background(#226467);
 
 fill(#A6EFF2);
 for(int i = 0; i<10; i=i+1){
   rect(a*i,0,a,a);
 }
fill(#55D8DE);
 for(int i = 0; i<20; i=i+1){
   ellipse(a*i,a,a,a);
 }
fill(#E873B9);
for(int i = 0; i<10; i = i+1){
  rect(a*i,a*2,a,a);
}
fill(#F2CBE3);
for(int i = 0; i<20; i = i+1){
  ellipse(a*i,a*2,a,a);
}
  
}
