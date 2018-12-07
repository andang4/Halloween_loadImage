PImage img;

void setup() {
  size(800, 500);
  img = loadImage("pumpkins.png");
  image(img,0,0);
}

void draw()
{
  save("Anthony.Halloween.png");
}

void mouseDragged()
{
  //"carves" the pumpkins
  blendMode(OVERLAY);
  noStroke();
  fill(255,200,25);
  ellipse(mouseX,mouseY, 5, 5);
} 






