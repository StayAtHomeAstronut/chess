# Overview

This is a 3D chess program, designed for two players to take turns moving pieces on an 8x8 grid. Each player begins with a full set of pieces, including pawns, rooks, knights, bishops, a queen, and a king, with the goal of checkmating the opponent's king. Players can select their pieces by clicking on them, and valid moves for the selected piece are highlighted on the board. Clicking a highlighted square moves the piece, while attempting to move to an invalid location is ignored. If a piece moves to a square occupied by an opponent's piece, it captures and removes that piece from the board. The game progresses with alternating turns until one player achieves checkmate, trapping the opponent's king, or until a stalemate occurs.

My goal in creating this chess program was to deepen my understanding of game development by exploring its core concepts and mechanics. By working on this project, I gained hands-on experience with game design, such as state management, user interaction, and object-oriented programming. I implemented features like move validation, piece selection, and user inputs, which allowed me to strengthen my problem-solving skills while learning how to structure complex systems effectively. This program also introduced me to important game development workflows, including handling visual feedback, managing game states, and integrating user controls, which are essential for building more advanced games in the future. In short, developing this game strengthened and grew my technical knowledge and prepare me for larger, more complex game development.

To access and edit the project in Unity, open the Unity Hub editor and create a new project. You can name it "chess" or whatever else you like. Download the assets, packages, and project settings folders included in this github repo and replace the folders in your new project with the files in this repo. When you open the editor, you should then see the game. You can edit or play the game from the editor. If you would simply like to play the game, an exe file is included.

[Software Demo Video](http://youtube.link.goes.here)

# Development Environment

To develop this chess game, I used the Unity Game Engine. I chose Unity for its user-friendly interface and real-time testing capabilities. Using Unity made it easy to design and implement the game’s core mechanics in 3D. By default, Unity implements features such as scene management, physics simulation, and input handling, which were essential in creating the chess game. Additionally, Unity's integration with C# made it easy to script. This enabled me to efficiently manage the game logic, player interactions, and piece movements.

For the programming portion of the game development, I used C#. I also used the Unity API quite extensively to handle input, instantiate game objects, and manage interactions between the player and the game world. Additionally, I used free assets from Kodeco to incorporate visual elements like chess pieces, the game board, and other graphical components. Kodeco included a tutorial on how to set up the board and peices, which I referenced, but did not use to develop this project. These assets included high-quality, ready-to-use models and textures, scripts mapping the pieces and grid to the board, and other improvements that helped me save time in the development phase, allowing me to focus on the game's functionality and mechanics.

# Useful Websites

* [Kodeco Chess Tutorial](https://www.kodeco.com/5441-how-to-make-a-chess-game-with-unity)
* [Unity](https://unity.com/)

# Future Work

* Introduce an option to play in 2-player mode or against an AI
* Introduce the En-Pessant gamerule.
* Introduce a UI and improve the game environment
