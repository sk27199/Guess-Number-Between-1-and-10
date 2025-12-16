# Guess-Number-Between-1-and-10

This project is a console based game using Object-Oriented Programming (OOP) principles. The player must guess a randomly generated number between 1 and 10 within 5 attempts.

The goal of this project is to demonstrate a strong understanding of Python fundamentals, program flow, and clean maintainable code design rather than focusing on graphics or user interface elements.

# How the Game Works

1. A random number between 1 and 10 is generated at the start of the game.
2. The user is given 5 attempts to guess the number.
3. After each guess, the program provides feedback:
   * Too high
   * Too low
   * Correct
4. The game ends when:
   * the user guesses the correct number, or
   * all attempts are used.
5. The user is given the option to play again.

# Key Features 

* Object-Oriented design using a dedicated game class
* Encapsulation of game logic within class methods
* Input validation to prevent crashes from invalid input
* Clear and user friendly feedback
* Replay functionality
* Randomised gameplay for repeatability

# Technical Concepts Demonstrated

# Object-Oriented Programming (OOP)
* Use of a class to represent the game
* Instance variables to store game state
* Methods to seperate responsibilities (input,checking, replay logic)

# Core Python Fundamentals
* Loops (``` while ```)
* Conditional statements (``` if, elif, else ```)
* Exception handling (``` try/ except ```)
* Type conversion (``` int ```)
* Random number generation (``` random ``` module)

# Defensive Programming
* Prevents invalid user input from crashing the program
* Handles incorrect input gracefully
* Ensures predictable program behaviour

# How to Run the Project

Ensure Python is installed, then run:

``` python guess_game.py ```

# Possible Future Improvements
* Difficulty levels (easy / medium / hard)
* Score tracking across multiple games
* Logging instead of print statements
* Unit tests for game logic
* Configuration file for game setting


   
  
* 

