Chess Game with Engine Integration
Overview
This project is a simple chess game implemented in C++ that utilizes the Stockfish chess engine for move calculations. The game features a graphical interface using SFML (Simple and Fast Multimedia Library) and allows users to play against the engine or make moves manually.

Features
Graphical User Interface: A user-friendly interface to play chess.
Engine Integration: Connects to the Stockfish chess engine to calculate optimal moves.
Drag and Drop: Players can drag and drop pieces to make moves.
Move History: Keeps track of the moves made during the game.
Castling Support: Implements special moves like castling.

Requirements
C++ Compiler (e.g., g++, clang++)
SFML Library
Stockfish Chess Engine (downloadable from Stockfish's official site)
Windows OS (due to the use of Windows-specific APIs)

Installation
Clone the Repository:

bash

Verify

Open In Editor
Run
Copy code
git clone https://github.com/yourusername/chess-game.git
cd chess-game
Install SFML:

Follow the instructions on the SFML website to install SFML for your platform.
Download Stockfish:

Download the Stockfish executable and place it in the project directory.
Compile the Project:

Use the following command to compile the project:
bash

Verify

Open In Editor
Run
Copy code
g++ main.cpp -o chess-game -lsfml-graphics -lsfml-window -lsfml-system
Usage
Run the compiled executable:

bash

Verify

Open In Editor
Run
Copy code
./chess-game
The game window will open, displaying the chessboard and pieces.

Use the mouse to drag and drop pieces to make your moves.

Press the SPACE key to let the engine calculate and make its move.

To undo the last move, press the Backspace key.
