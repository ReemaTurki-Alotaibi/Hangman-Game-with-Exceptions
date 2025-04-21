# Hangman Game - Python

## **Overview**

This is a simple implementation of the classic **Hangman** game in Python. The game randomly selects a word from a predefined list, and the player has to guess the word by suggesting letters one at a time. The player has a limited number of attempts to guess the correct word. If the player guesses all the letters correctly before running out of attempts, they win. Otherwise, they lose.

## **Features**

- **Random Word Selection**: The game selects a random word from a predefined list.
- **Interactive Gameplay**: The player can input letters to guess the word.
- **Input Validation**: The game ensures that the player enters a single valid letter (a-z, A-Z).
- **Win/Lose Conditions**: The player wins if they guess all the letters in the word before running out of attempts. They lose if they exhaust all attempts.
- **Play Again Option**: After winning or losing, the player can choose to play again or exit the game.

## **How to Play**

1. The game starts with a hidden word, and you will be given a number of chances to guess the letters.
2. Each time you guess a correct letter, it will be revealed in the word.
3. If you run out of chances before guessing the entire word, you lose the game.
4. The game will automatically end if you win or lose, with a message showing the result.

## **Contributing**

If you want to contribute to the game, you can modify the word list or add new features such as:

- **Add New Words**: Modify the word list in the code to suit your preferences.
- **Add Difficulty Levels**: Adjust the number of allowed guesses based on the difficulty level.
- **Add a Graphical User Interface**: Use libraries like `tkinter` to make the game more interactive.

## **Notes**

- Make sure to input **one letter only** at a time.
- If you repeat a letter guess, the game will notify you.


