# EscapeLabyrinth
Escape the Labyrinth - CS school project where players navigate a maze using pointers, collect magic items, and escape using given paths. Focus on debugging with gdb.

The objective is to navigate a maze using pointers, identify and collect three magical items (a spellbook, a potion, and a wand), and finally escape. The maze can either be a regular or a twisty maze, and the solution involves simulating movement through the maze based on a given set of directions.

Key features of the project include:

Maze Navigation: The program starts at a specific location in the maze and uses a sequence of moves (North, South, East, West) to explore different cells.
Pointer Usage: The maze is represented using pointers, with each cell in the maze having pointers to its neighboring cells in four possible directions (north, south, east, west).
Item Collection: As the user moves through the maze, the program checks if they encounter any of the magical items (spellbook, potion, wand) and collects them.
Escape Conditions: The player can escape the maze only after collecting all three items. The path out of the maze must be valid based on the maze structure, and the user must avoid walls and dead ends.
Debugging: This project requires the use of the gdb debugger to trace program execution, understand pointer behavior, and ensure proper traversal and item collection.
