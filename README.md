# OOPCA_SciFi
This is the repository for the first CA in Object Oriented programming 

In this project I model an animation from the game Horizon Zero Dawn.
There are 9 divisions that spin around the center circle.
If any of the subdivisions are clicked you here a sound (from the game. Its called a focus)and then the color variables are changed for the division clicked. 
I use the Minim Library for the focus sound and load in a purple background image.
The rotation animation was one of the trickiest bits of the code as I had pay attention to where I translated the shapes to or else the rotated or were drawn outside of the screen (window).

I use a class called Hexagons which describes the divisions of each hexagon spinning. 
Another obstacle I encountered was making the hexagons buttons (clickable), so I drew invisible circles around each one and had code to check if the mouseX and mouseY variables were inside the circles(or hexagons in this case).

Youtube Video:
