# 2023.01
2023.01
void setup(){

size(500,500);

}

void draw(){

for(int i=0;i<width;i++){

for(int j=0;j<height;j++){

stroke(frameCount/pow(255,i+j*width)%255,frameCount/pow(255,i+j*width+1)%255,frameCount/pow(255,i+j*width+2)%255);

point(i,j);

}

}

}
