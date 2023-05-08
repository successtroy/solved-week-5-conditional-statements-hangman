Download Link: https://assignmentchef.com/product/solved-week-5-conditional-statements-hangman
<br>
<p class="ui header product-top-header" title="Week 5 – Conditional Statements Hangman Solution">Deliverables

Each increment of the program will adhere to the following standards:

1.       Each source file will have a header describing the program, programmers name, date, purpose of the program, and increment.

2.       Each source file will adhere to the coding standards provided in the lecture, or given by the Professor.

3.       Each program will have an introductory output message introducing the program to the user and providing directions.

4.       All program output will be well structured, easy to read, and appropriately formatted.

Test Plan

Your test plan should test for a variety of cases. In your test plan list the values you tested along with a screenshot for each. You should test both incorrect and correct inputs.

Problem Description

You will be creating a Hangman program. In this game, the computer will have a hard coded word and the user will enter one letter at a time until he or she has guesses the correct word. A score will be tallied that will be the number of incorrect guesses the user has. So a smaller score is better.

Initially the word will be displayed as a list of special characters such as ‘*’ or ‘-‘. The user will input one letter at a time and each input will be compared with the word. If the guess is correct the letter will be displayed rather than the special character. Each incorrect guess will increment the score. When the user guesses the correct word the game will be over.

Below is an example of the program running:

Week 4 – Sequential Processing

Design and code the program to display the input and output for the Hangman program. Use your last name as the word to guess. Each letter will be a char data type. Start by having the user enter 5 letters to guess.  See below:

Week 5 – Conditional Statements

Modify the design and program to test if each letter the user entered is one of the letters in the word. If the letter guessed is in the word, display a message to the user that they guessed correctly, if not display a message that the user guessed incorrectly. Add a score variable that will keep track of the number of incorrect guesses. If the user guesses incorrectly, increment the score variable. Display the score at the end of the program.

Week 6 – Iteration and Arrays

Modify the design and program to allow for iteration. Increase the number of guesses to 10 to solve the word. Display the word to the user with each letter as a special character such as ********. Create an array of correct letters guessed such as: char[] guessed = new char[26];

You will need counter also to keep track of how many letters are in the guessed array. You do not need to keep track of incorrectly guessed letters.

Week 7 – Arrays and Output

This is your final modification to the project. Modify the design and program of the program so that the word is stored as an array. You can use code such as the following: char[] word = “happy”.ToCharArray();

Where “happy” is replaced with your name. Add a for loop to display each letter in the word character array. If it has been guessed correctly, display the correct letter, if not display the special character.

Optional: Instead of a fixed number of guesses (10), stop the program once the user guesses the correct