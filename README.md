# hw3

What code draws the blades of grass?

-function draw() {
  stroke(random(60, 70), 100, 90);
  line(x, height-10, x + random(-1, 100), height-10-random(h));
  

What code makes the "lawnmower" come by? How often does it come by?

- if (random() > .999) {
    noStroke();
    fill(255);
    rect(-1, -1, width+2, height-15);
    h = 10;


What's the point of the h variable?

-It is the height that the grass reaches before it is cut.


What do the three numerical arguments of colorMode do?

-It is in HSB which ceates the different hues of green in the different blades of grass.


What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?

-It makes the grass go upwards on the x-axis


If an array has 5 elements in it, what are the valid index values for the array? 

-All of the elements are added.


What is the difference between a for loop and a while loop?

-For loops have a set number of loops until it becomes false, while loops dont require you to make new variables for each statement.


Use Google or your favorite search website to figure out what the three parts of a for loop are called in JavaScript.

-initializer (var i = 1), test condition (i <= 50), updater (i++)


How does code refer to the number of elements in an array? 

-It doesnt change the code, it just adds more elements,"data change".


