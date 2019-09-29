What code draws the blades of grass?
 stroke(random(60, 70), 100, 90);
What code makes the "lawnmower" come by? How often does it come by?
 if (random(100) > 99.9) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  }
What's the point of the h variable?
It repersent the height of the "lawnmower"
What does the -10 do in the second and fourth arguments of the line function, height-10-random(h) ? Why is it there?
10 is the height of the "flowerpot". -10 makes the bottom of "lawnmower" touch the top of the "flowerpot"
height -10 - random(h) 
(height -10) means the height of the "lawnmower" and (- random(h)) means generation a random height of the "lawnmower"
