# Hangman Game

This is a simple Hangman game implemented in Python.

## Overview

Hangman is a word guessing game. The player must guess letters to uncover a hidden word. Each incorrect guess results in the drawing of a part of a gallows and a victim. The game ends either when the player guesses the word correctly or when the full drawing is completed.

## How to Play

1. Run the `hangman.py` file.
2. You will be shown a row of underscores representing the number of letters in the word.
3. Guess a letter by typing it in and pressing Enter.
4. If the letter is in the word, it will be revealed; otherwise, you'll lose a life.
5. Keep guessing until you either uncover the word or lose all your lives.

## Features

- The game randomly selects a word from a predefined list.
- You have a limited number of lives.
- The game provides visual feedback on the progress and remaining lives.

## Dependencies

This game uses the `random` module for word selection. No external libraries are required.

## Files

- `hangman.py`: Contains the main game logic.
- `hangman_words.py`: Contains the list of words to be used in the game.
- `hangman_art.py`: Contains ASCII art for the Hangman stages.

## Acknowledgments

- This game is inspired by the classic Hangman game.
- ASCII art for the Hangman stages is adapted from various sources on the internet.
