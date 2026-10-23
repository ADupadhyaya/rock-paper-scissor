Rock Paper Scissors in C 🎮

A simple Rock Paper Scissors game built using C where you play against the computer for 5 rounds. The computer randomly selects a move, and the winner is determined according to the classic game rules.

📌 About the Project

This project is a beginner-level C programming project created to practice fundamental programming concepts through a simple interactive game.

🛠️ Technologies Used
C Programming Language
Standard C Libraries: stdio.h, stdlib.h, and time.h
🎮 How to Play

When you run the program, enter a number corresponding to your choice:

Number	Choice
1	Rock 🪨
2	Paper 📄
3	Scissors ✂️

The game runs for 5 rounds, and the scores are updated according to the results.

Game Rules
Rock beats Scissors.
Paper beats Rock.
Scissors beats Paper.
If both the player and computer choose the same move, the round is a draw.

After all 5 rounds, the program compares the scores and announces the overall winner.

🚀 Getting Started
Prerequisites

You need a C compiler, such as GCC, installed on your system.

Installation and Execution

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git


2. Navigate to the project folder

cd YOUR-REPOSITORY


3. Compile the program

Assuming your C file is named main.c:

gcc main.c -o rock_paper_scissors


4. Run the game

On Linux or macOS:

./rock_paper_scissors


On Windows:

rock_paper_scissors.exe

📂 Project Structure
.
├── main.c
└── README.md


Replace main.c with your actual C source filename if it is different.

📖 Concepts Practiced
Variables and data types
Conditional statements (if, else if, else)
Loops using for
Random number generation using rand() and srand()
User input using scanf()
Score tracking and comparison
🔮 Future Improvements
Display the computer's choice after each round.
Add input validation for incorrect choices.
Improve the game's output formatting.
Allow users to select the number of rounds.
👨
