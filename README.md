# QuickStart-for-P5.js
Includes P5 libraries and simple quickstart template for creating P5.js project 

Here we have 2 file as "index.html" and "sketch.js"
We are actually importing p5 libraries and "sketch.js" to index.html as sources, nothing here is complicated as well. 

Basic Ellipse

There are "setup" and "draw" functions in "sketch.js". These are main elements, create a canvas in "setup" function and draw some stuff 
on canvas with "draw" function.

*
function setup(){
createCanvas(500,500);
}

function draw(){
	background(255,255,0);
	ellipse(200,200,50,50);
}
*
