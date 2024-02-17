# hangman

This script will open a GUI and run a simple game of [hangman](https://en.wikipedia.org/wiki/Hangman_(game)).

## Detailed Description:
This game uses a simple interface to play a game of hangman. The python modules [TURTLE](https://docs.python.org/3/library/turtle.html) and [TKINTER](https://docs.python.org/3/library/tkinter.html) are used for the graphics.

## Instructions for the Game:
1. You can guess either a letter or a word.
2. If you guess a letter and that letter is in the word, then the computer will reveal the places as to where it is in the word.
3. If you guess a letter and that letter is not in the word, then the computer will draw a man being hanged.
4. If you guess a word that is correct, you win!
5. If you guess a word that is not correct, the hangman gets hanged.
6. If you are able to reveal all the places of the word or guess it before the hangman is hanged, you win!

## Steps for Customizations:
1. For customizations regarding using a certain word, simply change the variable on line 5 (`TARGET_WORD`) to include the word you want to play with. Make sure this word is in the word list, or the code will not work.
2. For customizations regarding using a different word list, simply change the variable on line 7 (`WORD_FILE_NAME`) to contain the path of that word list. 

## Steps for Running the Game:
To run the program, Python 3 must be installed. Run [game-main.py](https://github.com/shuldrox/hangman/blob/main/game-main.py) to play!

## Acknowledgements:
The wordlist provided is from [dwyl/english-words/words_alpha.txt](https://github.com/dwyl/english-words/blob/master/words_alpha.txt).

## Notes:
Though the python module [RANDOM](https://docs.python.org/3/library/random.html) does not actually provide random numbers, it has been used since this is just for game purposes.