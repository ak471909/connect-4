# connect-4
Creating a  2-player connect 4 game  with a 6x7 grid in java 

# How the game works 
## Player Turns:
- Players take turns, with Player 1 represented by "O" and Player 2 by "X".
- The program prompts the player to choose a column (1-7) to drop their piece.
  
## Win or Draw Detection:
- After every move, the program checks for a win or a draw.
- If a win is detected, the game ends, and the winning player is announced.
- If all slots are filled without a winner, the game declares a draw.

## New Game Option:
After a game ends, players can opt to start a new game or exit.

# Key features of the program  
- The board is represented as a 2D array of strings (String[][]), with rows and columns corresponding to the grid structure.
- Empty slots are represented by " ".
- Displays the current state of the board with row (R1, R2, etc.) and column (C1, C2, etc.) labels for easy reference.
- Visualizes the horizontal dividers and slot boundaries
- Checks if a player has aligned four consecutive pieces:
- Vertically: Scans each column to find a sequence of four identical pieces.
- Horizontally: Scans each row for four consecutive pieces.
- Diagonally: Checks both left-to-right and right-to-left diagonals.
- If a winning condition is detected, the positions of the four connected pieces are printed.

# Running the game 
To run the program, ensure that java Development kit (JDK) is installed on the device, a text editor or IDE like eclipse is required to compile the program, and run the program in the IDE

