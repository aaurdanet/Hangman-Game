# Hangman Game

This is a simple implementation of the classic Hangman game in Python.

## How to Play

1. Run the script.
2. You will be presented with a series of dashes representing the letters of a random word.
3. Guess a letter.
4. If the letter is correct, it will fill in the corresponding dash(es). If incorrect, you will lose a life.
5. Keep guessing until you either guess the word correctly or lose all your lives.

## Files

- `hangman.py`: The main Python script containing the Hangman game logic.
- `hangman_words.py`: Contains a list of words that the game randomly selects from.
- `hangman_art.py`: Contains ASCII art for the Hangman stages and the game logo.

## How to Run

Ensure you have Python installed on your machine. Run `hangman.py` in your terminal or Python environment.

```bash
python hangman.py

Notes
The game is case-insensitive. All letters are converted to lowercase.
The game provides 6 lives for the player. If the player fails to guess the word within 6 incorrect guesses, the game ends.
