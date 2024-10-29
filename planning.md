## Planning

- The two shapes I am going to make interact with one another is an ellipse and a square
- Simple Statement: Whenever these two shapes meet when moving around the perameters of the screen, I want to them rebound off of eachother.
    - Collision Detection: To check if the ellipse and square are touching, I will need to measure the distance between the ellipse’s center and the square’s edges. 
        - Take the ellipse's radius and the square's side length.
        - Calculate the horizontal (x) and vertical (y) distances between the center of the ellipse and the square’s center.
    - Collision Response: To simulate a bounce effect:
        - I will need to swap the x and y velocities (dx and dy) of each object, reversing their direction along the collision axis.
- I will need to define the boundaries of each shape:
    - Ellipse: use its center point and radius
    - Square: define it by its center point and half its side length (giving you boundaries for left, right, top, and bottom edges). 
