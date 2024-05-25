Introduction
The program is a simple two-player snake game implemented in C, designed to run on a Windows console.
The game involves two snakes controlled by different players, who navigate the screen to consume food and grow in length.
The goal is to score 5 points first to win the game, while avoiding collisions with the walls or themselves.
The game features adjustable difficulty levels, providing varying speeds for the snakes.

Features
Two-Player Mode: Players control their snakes using different sets of keys (WASD for Player 1 and IJKL for Player 2).
Adjustable Difficulty: Players can choose from three difficulty levels (Easy, Medium, Hard), which affect the speed of the snakes.
Dynamic Gameplay: The game includes real-time snake movement, food generation, and score tracking.
Collision Detection: The game detects collisions with walls, snake bodies, and food, determining the winner based on the scores.

Tool Technologies
Windows API: Utilizes the Windows API for console handling, including cursor positioning (SetConsoleCursorPosition) and screen clearing (system("cls")).
Multithreading: Employs multithreading to handle simultaneous snake movement and player input using the Windows CreateThread function.
Standard C Libraries: Makes use of standard C libraries (stdio.h, stdlib.h, string.h, stdbool.h, conio.h) for various functionalities like input handling, random number generation, and boolean operations.
Console Graphics: The game's visuals are managed through simple console graphics, drawing the snakes, food, and game frame directly in the console.
Mutex: Uses mutex for synchronization to ensure safe access to shared resources, preventing race conditions and ensuring the integrity of the game state.

Conclusion
This two-player snake game provides a fun and interactive experience for players, combining elements of competition and strategy.
The use of multithreading ensures smooth gameplay, allowing both snakes to move independently while responding to player inputs.
The implementation showcases basic game development principles using console graphics and Windows-specific functionalities.
Overall, the game serves as a good example of how classic games can be recreated using modern programming techniques and basic tools available in the C programming language.
