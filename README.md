# Snake-Game
This code implements a basic snake game using Python's turtle graphics and the freegames library. Here's a brief breakdown of its functionality:
**Functions:**
1. change(x, y): Changes the snake's movement direction based on keyboard input.
2. inside(head): Checks if the snake's head is within the game boundaries.
3. move(): Handles the game logic:
   Moves the snake forward.
   Checks for collisions (with walls or itself).
   Adds a segment if the snake eats the food.
   Updates the display.
**Game Logic:**
1. The snake moves continuously in the current direction.
2. The game ends if the snake hits a wall or itself (head turns red).
3. If the snake eats the food, the snake grows, and the food is relocated randomly.
**This game is built using the following modules:**
▪ Turtle: It’s a pre-installed Python library that lets users create shapes and pictures using a virtual canvas.
▪ Time: Use this function to count how many seconds have passed since the epoch.
▪ Random: This function generates random numbers in Python by using the random module.
