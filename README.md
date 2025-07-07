Rock, Paper, Scissors Game
Welcome to the Rock, Paper, Scissors Game ReadMe file! This is a simple command line Python game where you can play against the computer. The game follows the standard rules of Rock, Paper, Scissors:
1.Rock crushes Scissors
2.Scissors cuts Paper
3.Paper covers Rock

Table of Contents:
1.Project Overview
2.Installation
3.How to Play
4.Game Rules

Project Overview:
This project is a basic implementation of the Rock, Paper, Scissors game in Python. The user plays against the computer, and the winner is determined based on the rules of the game. The game will prompt the user for input and display the result of each round.
1. When you run the game, it will prompt you to enter your choice between Rock, Paper, or Scissors.
2. The computer will randomly choose one of the three options.
3. The game will then display both your choice and the computer's choice, and announce the result of the round (win, lose, or tie).
4. The game ends after a single round, but you can run the script again to play more rounds.

Game Rules:
1. Rock beats Scissors.
2. Scissors beats Paper.
3. Paper beats Rock.
4. If both the player and the computer choose the same option, it's a tie.

What I Learned:
1. Random Number Generation:
I learned how to use the random.choice() method in Python to randomly select an item from a list. This is how the computer randomly selects its choice of Rock, Paper, or Scissors.

2. User Input Handling:
I practiced handling user input using input(), and learned how to process and validate the input to ensure the user enters a valid option (Rock, Paper, or Scissors).

3. Conditionals:
I strengthened my understanding of if-else statements to compare the user’s choice and the computer’s choice, and to determine the winner based on the game rules.

4. String Manipulation:
I learned how to use .lower() to convert user input to lowercase to handle case sensitivity (i.e., the user can input "Rock" or "rock" and the program will process it the same way).

5. Looping and Repeating the Game:
I understood how to structure a program that can repeat a specific task (like playing multiple rounds) by wrapping the game logic inside a loop.

6. Basic Program Structure:
I learned how to structure a simple Python program with clear sections: defining the game logic in functions, accepting user input, and displaying output.

Example:
Welcome to Rock, Paper, Scissors!
Enter rock, paper, or scissors: paper
Computer chose: rock
You win!

Credits:
Author: Syeda Hira Fatima

Programming Language: Python 3.x

Game Logic: Based on the classic game of Rock, Paper, Scissors

License:
This project is open-source. Feel free to fork and modify it as needed.
