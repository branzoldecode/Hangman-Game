# Hangman-Game
A simple Hangman Game
### Hello Every one, Today I am going to show you how to make a simple hangman game with Python programming language.

## **The Plan**

## **Our hangman game has to do the following:**

Let the user guess characters for random words 

## Now you can start thinking about how this might work in code. The code will need to do the following:

1. Use the random library
2. make an input variable for the user name and say hi
3. make a list of words
4. create a variable that randomly choose words from out previous list
5. tell the user to guess the characters
6. create a guesses variable
7. create a turns variable and set it to any number
8. create a while loop for turns while greater than 0
9. create a variable in the while lopp and call ir failed and it equals to 0
10. create a for loop inside the while loop (for char in word)
11. create an if statemnt in the for loop (if char in guesses) then print it, else print "_" and encrease the failad variable by one
12. create an if statment inside the while loop for failed and set it to 0 and if its true print you winand print the word and break thw whilw loop.
13. create an input ion the guess var to guess the chracter
14. store every input charcter in the guesses variable
15. create an if statemnt if guesses not in word then reduce "turns "by one and print wrong and print the number of turns left for the user
16. if turns = 0 you lose
