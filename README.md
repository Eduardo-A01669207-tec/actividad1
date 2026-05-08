# paint.py modified
How to run the game: python3 paint.py

List of changes for this file:

A new color (yellow) was added to the drawing palette.

Completed the function to draw a circle.

Added a function to draw a rectangle.

Added a function to draw an equilateral triangle.

Change 1
A new color and a new shape were implemented. The color yellow was added to the available drawing options and bound to the 'Y' key using an onkey listener with a lambda function. Additionally, the circle() function was completed to draw a filled circle. It uses a for loop that iterates 36 times, moving forward by a fraction of the distance between the start and end points ((end.x - start.x) / 5) and turning left by 10 degrees each time to complete a full 360-degree shape. The circle tool is mapped to the 'c' key.

Author: Alejandro Rodriguez Brito

Change 2
New drawing functions were added to expand the toolset beyond just a square. A rectangle() function was created using a for loop that runs twice, drawing both the width (x difference) and height (y difference). Additionally, a triangle() function was implemented using a for loop that runs three times with an exterior turning angle of 120 degrees (left(120)) to draw a perfect equilateral triangle.

Author: Eduardo Arteaga Camacho
