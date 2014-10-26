ECE382_Lab4
===========
# Lab4 - "Etch-a-Sketch and Pong"


## Prelab

###Data types

![LCD](https://raw.githubusercontent.com/gytenis98/ECE382_Lab4/master/prelab1.JPG?raw=true "LCD")

###C code definitions

![analyzer]https://raw.githubusercontent.com/gytenis98/ECE382_Lab4/master/prelab2.JPG?raw=true "analyzer")

###Calling/Return Convention

![analyzer](https://raw.githubusercontent.com/gytenis98/ECE382_Lab4/master/prelab3.JPG?raw=true "analyzer")

###Registers

![66](https://raw.githubusercontent.com/gytenis98/ECE382_Lab4/master/prelab4.JPG?raw=true "66")



##Functionality (Completed)

Modify your assembly drawBlock function to take in 3 values: an x coordinate, a y coordinate, and a color. 

Create an etch-a-sketch program using the directional buttons of the LCD booster pack to control the position of the paint brush. The paint brush will draw 8x8 blocks of pixels. The user will change the position of the paint brush by pressing the directional buttons. Each button press will move the cursor 8 pixels in the direction pressed (see table below). Pressing the auxiliary button (SW3) will toggle the mode of the paint brush between filling squares and clearing squares.


##B Functionality (completed)

Create a bouncing block! This block should move across the screen with no more than 8 pixels per jump. It should bounce off the walls appropriately, similar to assignment 6. An adequate delay movement should be added between each block movement. Your starting position and starting x and y velocities should be initialized in your header, or should be randomly generated. 
##A Functionality (not completed)

Create Pong on your display! Create a single paddle that will move up and down on one side of the display, controlled by the up and down buttons. The block will bounce off the paddle like it bounces off the wall. When the block misses hitting the paddle, the game will end. 

Bonus Functionality (round balls + 2 balls completed)

Each bonus functionality can be achieved in conjunction with either A or B functionality. These functionalities must be written in assembly and called by C. Each is worth 5 points.

Circle: Instead of a bouncing block, create a bouncing circular ball!

Fine movement: Instead of having the ball/paddle move in 8-pixel jumps, have it move in 1-pixel jumps.

Inverted display: With a push of the SW3 button, invert the display. Dark pixels will become light pixels, and vice versa. Instead of a bouncing dark ball, you will have a bouncing light ball.

Note: The maximum lab grade cannot exceed 105.


##Grading
Required and functionallity showed to Capt Trimble. B functionallity and bonus functionallity showed to Dr. Coulston.

##Documentation

####Lab

Capt Trible helped me with required functionallity. It was giving me an unknown error. After recreating program project several it started to work. Did not understand why it was not working at first. Also, went to Dr. Coulston to show the functionallity and how an EI about how to complete A functionallity but unfortunatelly could not make it to work fully.
