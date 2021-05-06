# hangman
Attempt at OOP, using Python to create a Hangman game 


"""
Attempt at OOP, using Python to create a Hangman game

General Rules of Hangman / Play Style:
    1.) First player will pick a secret word, and draws a line for each letter in it. An Underscore will represent each letter. 
    2.) Second player will then guess a letter, attempting to figure out the secret word.
    3.) If Second player correctly guesses a letter, Player one will then replace the corresponding underscores with the correctly guessed letter. Note, in this version if a letter appears multiple times it will have to be guessed again.
    4.) If Second player incorrectly guesses a letter, First player will draw a body part of a hanged stick figure
    5.) If Player two completes the word before the drawing of the hangman is complete, Player two wins. If the hangman is complete, Player one wins. 
"""
