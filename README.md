
🕹️ Tic-Tac-Toe Game – C++ with GTK
A simple 2-player Tic-Tac-Toe game built in C++ using the GTK library for the graphical user interface.

📌 Features
3x3 grid-based Tic-Tac-Toe board

Player X and Player O take alternate turns

Automatic win/draw detection

Status display showing current player's turn

Reset button to restart the game

🧰 Technologies Used
Language: C++

GUI Library: GTK (GIMP Toolkit)

Build Tool: gcc / g++

▶️ How to Run
1. Install GTK+ (if not already installed)
On Ubuntu/Debian:
bash
Copy
Edit
sudo apt update
sudo apt install libgtk-3-dev
On Fedora:
bash
Copy
Edit
sudo dnf install gtk3-devel
2. Compile the code
bash
Copy
Edit
g++ -o tictactoe tictactoe.cpp `pkg-config --cflags --libs gtk+-3.0`
3. Run the game
bash
Copy
Edit
./tictactoe
🧠 How It Works
Each button on the grid is linked to a specific row and column.

When clicked, it marks the move with either "X" or "O" and disables that button.

check_winner() checks for any winning combination or a draw.

The Reset Game button clears the board and resets the game state.

📄 File Structure
tictactoe.cpp – Main source code file containing game logic and GUI setup.
