int value = 0;
float angle = 0.0;

void setup() {
  size(1200, 800);
  frameRate(100);
  smooth();
  background(0);
} 

void draw() {
  stroke(value + mouseX/5, value + mouseY/2, value + mouseX*mouseY/4, 50);
  strokeWeight(5);
  noFill();

  //translate(mouseX, mouseY);
  //rotate(angle);
  bezier(100, 100, mouseX, mouseY, 1000, 600, 1100, 700);
  //angle += 10;

  if (keyPressed) {
    if (key == 'p' || key == 'P') {
      background(0);
    }
  }
}

void mouseDragged() {
  value = value - 25;
}

void mouseReleased() {
  value = 0;
}
