# Snakes-and-ladders
DSA PROJECT 
This C program implements a simple Snake and Ladder game. Below is an explanation of its key components:

1. **Node Structure:**
    - The `struct Node` is used to define a node for a linked list. Each node represents a position on the game board and stores information about whether it is a snake or a ladder and the corresponding weight.

2. **Player Structure:**
    - The `struct Player` defines a structure to store player information, including the player's name, current position on the board, score, and the number of rolls.

3. **`rollDie` Function:**
    - Generates a random number between 1 and 6, simulating the roll of a six-sided die.

4. **`printBoard` Function:**
    - Displays the game board, showing the positions of players and empty spaces.

5. **`movePlayer` Function:**
    - Moves the player on the board based on the dice roll.
    - Handles encounters with snakes and ladders, adjusting the player's position and score accordingly.

6. **`declareWinner` Function:**
    - Prints a congratulatory message when a player reaches the final position (position 100) and wins the game.

7. **`freeLinkedList` Function:**
    - Frees the memory allocated for the linked list that represents snakes and ladders on the board.

8. **`createSnakesAndLadders` Function:**
    - Creates a linked list representing the snakes and ladders on the board based on the specified difficulty level. The linked list is then returned.

9. **`main` Function:**
    - Initializes random seed for the `rand` function.
    - Prompts the user to input the number of players and their names.
    - Asks the user to choose the difficulty level (Easy, Medium, Hard) for the game.
    - Creates a linked list representing snakes and ladders based on the chosen difficulty.
    - Runs the main game loop, allowing each player to take turns rolling the die and moving on the board.
    - Checks if a player has reached the final position (100) and declares the winner.
    - Frees the allocated memory for the linked list and player structures.

This program is suitable for a simple text-based Snake and Ladder game and can serve as a starting point for more complex implementations or graphical adaptations. If you plan to use this code in a Git repository, make sure to include proper documentation and a license. Additionally, you might want to organize the code into multiple files for better maintainability.
