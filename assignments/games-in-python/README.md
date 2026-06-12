
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python that uses strings, loops, conditionals, and user input to let players guess a hidden word.

## 📝 Tasks

### 🛠️ Game Setup

#### Description
Create a Hangman game that selects a random word from a list and initializes the game state for the player.

#### Requirements
Completed program should:

- Use a predefined list of possible words.
- Randomly select one word at the start of the game.
- Show the hidden word as blanks, for example `_ _ _ _`.
- Track the letters guessed so far and remaining attempts.

### 🛠️ Letter Guessing and Progress Display

#### Description
Implement the core guessing loop that accepts player letters, reveals correct guesses, and updates the game display.

#### Requirements
Completed program should:

- Accept letter guesses from the player.
- Reveal matching letters in the hidden word while keeping unguessed letters hidden.
- Display the current progress after each guess.
- Prevent repeated penalties for letters that were already guessed.

### 🛠️ Win/Lose Conditions

#### Description
Complete the game by checking for win or loss conditions and showing the appropriate final message.

#### Requirements
Completed program should:

- End with a win message when the player guesses the full word.
- End with a lose message when attempts run out.
- Show the correct word at the end of the game.
- Display the number of incorrect guesses remaining throughout play.
