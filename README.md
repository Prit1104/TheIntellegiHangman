# TheIntellegiHangman
An intellegent playgame of hangman that learns the difficulties of a word, from human based training.

Start with trial1.py file to get start with the game.
trial1.py file takes input from word1.txt file and chooses random word to be guessed and starts hungman.py file.

hungman.py file has all the game essentials and all the vowels are only displayed and other letters are to be guessed in 10 max trials.
If there is a hit of any letter than there will be increment on the correct tries.

If letter miss is there than guesses left will reduce.

If you guess the correct word than the difficulty level will be displayed in the range of 0 to 1. It states that how easy the word was to guess.
The greater difficulty value the easier the word is to guess.
