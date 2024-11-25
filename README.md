
<body>
  <header>
    <h1>Bailey's Portfolio</h1>
  </header>

<br>
<br>


    <p>Hello! My name is Bailey Stern, and I'm from San Francisco, California. Being from an area so well versed in technology, I have always been inspired to dive more into that world. I am currently a Creative Computing Major at Southern Methodist University. I hope to work in video game development once I graduate in 2026. I have coding, animating, and writing experience. I am currently taking CRCP3320 in order to widen my understanding of software applications and development. </p>

  <footer>
    <p>bpstern@smu.edu</p>
  </footer>
</body>

<h2>P5 Art Graphic</h2>
<script>
  
function setup() { createCanvas(1000, 1000); //1000x1000 square canvas background(225); //white background }

void setup() {
size(600, 600);
background(209, 250, 250);
}

color headColor = color(238, 198, 181);
color neckColor = color(238, 198, 181);
color hairColor = color(249, 209, 116);
color hairClipColor = color(238, 166, 235);
color eyebrowColor = color(87, 60, 14);
color eyeColor = color(255);
color pupilColor = color(0);
color noseColor = color(238, 198, 181);
color mouthColor = color(209, 92, 115);
color teethColor = color(255);

function mouseClicked() {
headColor = color(random(255), random(255), random(255));
neckColor = color(random(255), random(255), random(255));
hairColor = color(random(255), random(255), random(255));
hairClipColor = color(random(255), random(255), random(255));
eyebrowColor = color(random(255), random(255), random(255));
eyeColor = color(random(255), random(255), random(255));
pupilColor = color(random(255), random(255), random(255));
noseColor = color(random(255), random(255), random(255));
mouthColor = color(random(255), random(255), random(255));
teethColor = color(random(255), random(255), random(255));
}

function draw() {
background(209, 250, 250);
fill(headColor);
noStroke();
circle(300, 300, 400); 
fill(neckColor);
rect(222, 469, 150, 100); 
fill(hairColor);
noStroke();
ellipse(300, 150, 400, 150); 
ellipse(100, 400, 150, 500); 
ellipse(500, 400, 150, 500); 
fill(hairClipColor);
stroke(209, 250, 250);
triangle(140, 152, 134, 211, 73, 178); 
triangle(451, 152, 463, 211, 510, 178); 
fill(eyebrowColor);
stroke(255, 50, 0);
rect(330, 273, 90, 15); 
rect(180, 273, 90, 15); 
fill(eyeColor);
stroke(0);
circle(230, 320, 40); 
circle(369, 320, 40); 
fill(pupilColor);
stroke(87, 60, 14);
circle(230, 320, 20); 
circle(369, 320, 20); 
fill(noseColor);
triangle(300, 322, 285, 403, 315, 403); 
fill(mouthColor);
noStroke();
triangle(230, 423, 300, 470, 300, 439); 
triangle(360, 423, 300, 470, 300, 439); 
stroke(255, 255, 255);
line(232, 425, 298, 453); 
line(299, 455, 355, 426); 
}
