# MAGD-150
This is a collection of labs 3, 4, and 5, from *MAGD 150*

### [Lab 3](https://github.com/KingCreeper262/MAGD-150/blob/main/papenthienBAssignment3.zip)
This lab created a greyscale background alongside a __red__ square that follows the mouse across the canvas, leaving an orange trail and a __blue__ circle that bounces off the edges of the canvas and the __red__ square.

### [Lab 4](https://github.com/KingCreeper262/MAGD-150/blob/main/papenthienBAssignment4.zip)
In this lab, I made a circle class that stores several values about a circle including radius, position, and velocity. The draw function iterates over an array of these circle objects and moves them across the canvas based on their position and velocity.
Once the circles are no longer visible on the canvas, they are assigned a random position on the canvas and a has a *one in two* chance of switching the x and y velocity. (x and y are rolled seperately, meaning __neither__, __either__, or __both__ could be swapped)

### [Lab 5](https://github.com/KingCreeper262/MAGD-150/blob/main/papenthienBAssignment5.zip)
This is the most complex lab of all three. Upon clicking the canvas, your mouse is hidden. Your mouse movements instead dictate the movement of a triangle on the canvas. (*Pressing esc reveals one's mouse again*)
Pressing any key on the keyboard iterates over a list of "BetterColor" objects reassigning the background color to the next one on the list, then reassigns the previous "BetterColor" to a new "BetterColor" with random values for the Red, Green, and Blue fields Upon reaching the end of the list, it moves back to the first element.
Pressing any mouse button iterates over the same "BetterColor" list as the keyboard, but reassigns the color of the triangle moved by the mouse. This one does not create new colors. This does mean that if one presses a key, it could also reassign the color of the triangle.
