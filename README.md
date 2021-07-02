# hangman_game

- good use of a loop to search multiple iteration of the same character at line 59 :

while index < length:
            index = word.find(guess, index)

- interesting use of positioning characters in a string example line 63 :

word = word[:index] + "_" + word[index + 1:]