# Project 2 : The Hangman Game

## Introduction
The purpose of my project is to implement a simple hangman game, with only 10 guesses, and a decryption mechanism. My hangman game will randomly select one word from the list of words provided (“WHDSPQZ”, “XHO”, “TTDBFRT”, “QQJYF”, “ENQD”, “DNPK”, “CNTR”, “EHWHOD”, “TSVMOHOF”, “XNOCFQGTM”) and the user must guess the word. Firstly, the hangman game function will conveniently show dashes wherever the letters are not guessed, the number of remaining incorrect guesses, letters that were guessed correctly, and letters that had already been guessed. If the number of guesses reaches zero before the user guesses the correct word, a statement will show up on the screen reciting: "You lose. the secret word is ________." However, if the user decodes the correct word before the number of guesses are up, the following statement will show up on the screen: "Congratulations! You guessed the correct word!" Next, the second part of my program, which is the decryption mechanism, is meant to decode the secert message when the user guesses the word correctly.

## How My Hangman Function Works:
