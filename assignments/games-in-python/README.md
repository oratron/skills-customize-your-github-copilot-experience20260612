
# 📘 Assignment: 🎮 Hangman Game Challenge

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. You'll practice string manipulation, loops, conditionals, and random selection while creating an interactive game where players guess letters to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Task 1: Set Up the Game

#### Description
Initialize the game with a word list and set up the game state variables needed to track the game progress.

#### Requirements
Completed program should:

- Import necessary modules (e.g., `random`)
- Define a list of words to choose from
- Randomly select a word at the start of each game
- Initialize variables to track guesses, attempts, and game state

### 🛠️ Task 2: Implement Guess Handling

#### Description
Create the core game loop that accepts letter guesses and displays the current progress of the word.

#### Requirements
Completed program should:

- Accept letter guesses from the player
- Show current progress with underscores for unrevealed letters (e.g., `_ _ _ format`)
- Track incorrect guesses and remaining attempts
- Prevent duplicate guesses

### 🛠️ Task 3: Add Win/Lose Logic

#### Description
Implement game-ending conditions and display appropriate messages when the game concludes.

#### Requirements
Completed program should:

- End when the word is correctly guessed
- End when attempts are exhausted
- Display win/lose messages
- Ask player if they want to play again
