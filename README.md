# Hangman
Hangman game

Game involves several components, including word selection, game flow, user input handling, and displaying the game state. 

1. Word Selection: 

The game uses a dictionary with levels (easy, medium, hard) where each level has a list of words.

2. ASCII Art: 

The hangman_stages list contains ASCII representations of the hangman for different stages of the game.

3. Game Logic:
   - The user is prompted to select a difficulty level, and a random word from the corresponding list is chosen.
   - The user is informed of their remaining lives and the current state of the word.
   - The game checks for valid input and repeats guesses.
   - The game continues until the user either guesses the word or runs out of lives.

4. Exit Option: 

The player can type 'quit' to exit the game at any time.

