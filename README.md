README for Bouncing Balls Animation
Overview
This project consists of an HTML document that allows users to dynamically add bouncing balls (represented as images) to the page and animate their motion. The user can create multiple balls and move them within defined boundaries, where they will bounce off walls and floor.
Features
•	Add Ball: Users can click a button to add a new ball (image) at a random position on the screen.
•	Move Balls: Users can click another button to start the movement of all added balls. The balls will bounce off the edges of the window.
Files
•	index.html: The HTML file that contains the structure and script necessary for the animation.
Instructions to Run
1.	Setup: Ensure that you have an image file named PacMan1.png available in the same directory as your index.html file. This image will be used as the ball.
2.	Open the HTML file: Open index.html in a web browser of your choice.
3.	Add balls: Click the "add" button to create balls at random positions on the screen.
4.	Move balls: Click the "move" button to start the animation. The balls will move, bouncing off the walls and floor of the browser window.
Code Explanation
•	The script begins by initializing empty arrays to hold the images of the balls (imgs), their positions (x_pos and y_pos), and their velocities (x_vel and y_vel).
•	The ballCount function creates a new <img> element representing the ball, assigns it a random starting position, and pushes its data into the respective arrays.
•	The moveBall function updates the position of each ball based on its velocity and checks for collisions with the edges of the window. If a ball hits an edge, its velocity is inverted to create a bouncing effect.
•	The balls' positions are applied to their respective style properties, creating a visible animation.
Future Enhancements
•	Allow users to remove balls.
•	Change the velocity and gravity dynamically.
•	Add more visual effects or sound.
•	Implement better collision detection for corners.
License
This project is open source and free to use. Enjoy adding and animating your bouncing balls!
