# Computer Number Guessing Game
A simple Python program with two modes. 
Mode 1:
User tries to guess computer's 
randomly chosen number.
Mode 2:
Computer tries to guess a number chosen by the user.

## How It Works
Mode 1:
The computer chooses a random number. The user tries to 
guess the number. If the user guessed a wrong number, it 
will signify that the number is either lower or higher 
than the computer's number or if the number guessed by the 
user is correct.
Mode 2:
The user chooses a number range, such 
as 1 to 100
The computer guesses the number and 
asks whether it's guess is:
- Too high
- Too low
- Correct
The computer uses the feedback to 
narrow down the possible numbers until 
it finds the correct answer.
The prigram also counts how many 
guesses the computer needed.

## Features
- Two modes of gameplay
- User-defined number range
- Computer-generated guesses
- High/low feedback
- Automatically narrows the search range
- Counts the number of guesses

## Requirements
- Python 3

# How to Run
1. Download or clone this repository.
2. Open the project folder in a terminal.
3. Run:
'''bash python Guessing_game_v2.py

# What I Learned
This project helped me practice:
- Python variables
- input()
- if, elif, and else
- while loops
- Counters
- Integer division
- The basic idea behind binary search