Project Overview: iDragon Adventure
iDragon Adventure is a dynamic and engaging web-based game developed using HTML, CSS, and JavaScript. This project showcases fundamental principles of front-end web development and offers a fun, interactive experience. Below is a breakdown of the key components and features of the game.

Key Features:
Interactive Gameplay:

Character Control: The player controls a character, represented as a dinosaur (dino), which can jump and move left or right using keyboard inputs (Arrow Up, Arrow Right, and Arrow Left keys).
Obstacle Avoidance: The game includes a moving obstacle (dragon) that the player must avoid by jumping over it.
Audio Integration:

Background Music: The game starts with background music that enhances the gaming experience.
Game Over Sound: A distinct sound is played when the game ends due to a collision.
Score Tracking:

Real-Time Score Update: The player’s score increases as they successfully avoid obstacles, displayed dynamically on the screen.
Difficulty Scaling: The game’s difficulty increases over time by speeding up the obstacles, challenging the player's reflexes and timing.
Visual and Animation Effects:

Character and Obstacle Animation: The dinosaur (dino) has a jump animation, and the obstacle (dragon) moves across the screen in a looping animation.
Responsive Design: The game adapts to different screen sizes, maintaining its visual appeal and functionality.
Technical Breakdown:
HTML Structure:

The HTML file sets up the basic structure of the game, including a container for the game elements (gameContainer), the character (dino), the obstacle (obstacle), a game over message (gameOver), and a score display (scoreCont).
CSS Styling:

The CSS defines the visual style and layout of the game. It includes styles for the background, the game elements, and the animations.
Key Animations:
@keyframes dino: Controls the jump animation of the dinosaur.
@keyframes obstacleAni: Defines the movement of the obstacle across the screen.
JavaScript Logic:

Event Handling: Captures key presses to trigger actions like jumping and moving left or right.
Collision Detection: Uses precise calculations to detect collisions between the dino and obstacle.
Score Management: Increments the score and updates the display whenever the player successfully avoids an obstacle.
Game Mechanics: Adjusts the speed of the obstacle to increase game difficulty and manages the audio playback for background and game-over scenarios.
Game Flow:
Initialization: When the game starts, background music begins playing after a short delay.
Gameplay: The player uses the arrow keys to control the dino:
Up Arrow (e.keyCode == 38): Makes the dino jump.
Right Arrow (e.keyCode == 39): Moves the dino to the right.
Left Arrow (e.keyCode == 37): Moves the dino to the left.
Collision Detection: The game constantly checks if the dino collides with the obstacle. If a collision is detected, the game stops the obstacle's movement, displays a "Game Over" message, and plays the game-over sound.
Score and Difficulty: The player’s score increases as they avoid obstacles, and the speed of the obstacles gradually increases to make the game more challenging.
How to Play:
Start the Game: Open the HTML file in a web browser.
Control the Dino: Use the Up, Left, and Right arrow keys to jump and move.
Avoid the Obstacle: Time your jumps to avoid colliding with the moving dragon.
Keep Scoring: Try to achieve the highest score possible by avoiding obstacles.
This project is a great example of combining HTML, CSS, and JavaScript to create an interactive and entertaining web application. It's suitable for beginner and intermediate developers looking to practice and enhance their front-end development skills.
