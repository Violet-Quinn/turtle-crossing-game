**Description:**

This Turtle Crossing game is an engaging project developed using Python’s `turtle` graphics library. The objective is to guide the player’s turtle safely across a busy road while avoiding moving cars. It’s a fun way to explore Python, learn game development concepts, and practice collision detection and level progression.


**Objective:**

The goal of the game is to safely guide the player-controlled turtle from the bottom to the top of the screen while avoiding the cars. Each time the turtle successfully crosses, the game increases in difficulty, with cars speeding up or becoming more frequent.


**Components:**

- **Player (Turtle):** You control the turtle with the Up arrow key. The turtle moves upwards with each key press, trying to reach the top of the screen without being hit by a car.

- **Cars:** Cars of random colors and sizes move horizontally across the screen from right to left. The number and speed of cars increase as the player progresses.

- **Scoreboard:** The scoreboard keeps track of the player’s level. Each time the player successfully crosses the road, the level increases, and the cars move faster.


**How the Game Works:**

- The game window is 600x600 pixels.
- The player controls the turtle’s movement with the Up arrow key to move it forward.
- The `CarManager` generates new cars at random intervals, and these cars move from right to left across the screen.
- Collision detection is key: if the player-controlled turtle gets too close to a car (less than 20 units), the game ends, and "Game Over" is displayed.
- If the turtle reaches the top, it resets to the starting position, the game difficulty increases, and the level goes up on the scoreboard.
- The game loops continuously, with increasing difficulty until the turtle collides with a car.


**Key Concepts:**

- **Collision Detection:** The game checks for collisions between the turtle and the cars to end the game.
- **Level Progression:** Every time the turtle crosses the road successfully, the difficulty increases by making the cars faster.
- **Game Loop:** The game runs in a loop, updating the screen and managing both the turtle’s movement and the cars.
