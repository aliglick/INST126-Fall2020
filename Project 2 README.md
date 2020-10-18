# Project 2 : The Hangman Game

## Introduction
The purpose of my project is to implement a simple hangman game, with only 10 guesses, and a decryption mechanism. My hangman game will randomly select one word from the list of words provided (“WHDSPQZ”, “XHO”, “TTDBFRT”, “QQJYF”, “ENQD”, “DNPK”, “CNTR”, “EHWHOD”, “TSVMOHOF”, “XNOCFQGTM”) and the user must guess the word. Firstly, the hangman game function will conveniently show dashes wherever the letters are not guessed, the number of remaining incorrect guesses, letters that were guessed correctly, and letters that had already been guessed. If the number of guesses reaches zero before the user guesses the correct word, a statement will show up on the screen reciting: "You lose. the secret word is ________ ." However, if the user decodes the correct word before the number of guesses are up, the following statement will show up on the screen: "Congratulations! You guessed the correct word!" Next, the second part of my program, which is the decryption mechanism, is meant to decode the secert message when the user guesses the word correctly.

## How My Hangman Function Works:

1. Firstly, my function  randomly selects a word from this list: words = ['WHDSPQZ', 'XHO', 'TTDBFRT', 'QQJYF', 'ENQD', 'DNPK', 'CNTR', 'EHWHOD', 'TSVMOHOF', 'XNOCFQGTM']

2. Secondly, my program prints the following statements:

    a. "Welcome to the Hangman Game!"
    
    b. "The secret word is - - - -" <-- the dashes will vary depending on how long the secret word is
    
    c. "Number of guesses remaining : 10"
    
3. Thirdly, the user will be asked to please enter a letter

    a. If the letter is not in the secret word, then letter will be added to the lettersGuessed list, the number of guesses will go down by one, and the user will be asked to guess another letter.
    
    b. If the letter is in the secret word, then the letter will replace the dashed line in the correct position, the number of guesses will go down by one, and the user will still be asked to guess another letter!
    
4. If the user guesses the secret word before he/she has used up his/her 10 tries, then the following will be recited on the screen: "Congratulations! You guessed the correct word!"

5. If the user does not guess the word and his/her 10 tries are up, then the following statement will be recited on the screen: "You lose. The secret word is ______ ."

## How My Hangman Decryption Works:

1. 
