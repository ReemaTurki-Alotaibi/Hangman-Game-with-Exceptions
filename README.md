**🎮 Hangman Game - Python**


**📌 Overview**


A simple implementation of the classic Hangman game using Python.
The game selects a random word from a predefined list, and the player must guess the word one letter at a time. You win if you guess the full word before running out of attempts.


**✨ Features**


🔤 Random Word Selection – Chooses a word from a predefined list.

🎮 Interactive Gameplay – Input letters via a simple UI or console.

✅ Input Validation – Accepts only valid single alphabetical characters.

🏆 Win/Lose Conditions – Win by guessing the full word, lose by running out of attempts.

🔁 Play Again Option – After a game ends, start a new one easily.


**▶️ How to Play**


The game starts with a hidden word (e.g., *****).

Guess one letter at a time.

Correct letters will be revealed in their positions.

Incorrect guesses reduce your remaining attempts.

The game ends when:

✅ You guess all letters correctly (you win).

❌ You run out of attempts (you lose).


**🛠️ Contributing**


Want to contribute or enhance the game? Here are some ideas:

➕ Add New Words – Update the word_list with more diverse vocabulary.

🔢 Add Difficulty Levels – Vary the number of allowed attempts.

🖼️ Add GUI – Use libraries like tkinter, PyQt, or web frameworks.

🧪 Unit Tests – Already included using unittest. You can expand them.


**📝 Notes**


Please input only one letter at a time.

If you guess a letter more than once, you’ll be notified.

This version is optimized for Google Colab (interactive UI with widgets).

Make sure to run in a supported environment (e.g., Google Colab).
