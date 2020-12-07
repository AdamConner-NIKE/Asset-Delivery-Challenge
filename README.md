# Asset Delivery Code Challenge

Welcome to the Asset Delivery Code Challenge. This is a series of questions that we would like you to prepare answers for in order to demonstrate your technical skills and abilities. Before we get started, here are some rules and guidelines.

## Rules

1. Create a new private repo and put your answers in your own repo. We'll ask you to share the link to your repo during the interview.
2. We expect this should take between 1 and 2 hours to complete. If you're not finished after 2 hours, that is ok and you don't need to continue. We will simply review what you have finished in that time. There are no penalties for extra time, but we won't be adding "bonus points" because you did a bunch of extra work.
3. Choose between Java or TypeScript for your code. We are in the middle of migrating from Java to TS and want you to write in whatever you are most comfortable with.
4. Use online resources and feel free use them as a starting point. Your ability to describe what and why is very important. We will be comparing your answers to online source and also will ask you to make some in person changes so we are sure you actually know what you are talking about.
5. Use your favorite code editor, use separate files and show off your skills for us. How would you organize the repo? How would you test your code? etc.
6. Commit often and early so we can see timestamps and progression. It will help us understand and step through code after your interview is complete if we need to compare things.
7. Make sure to keep your answers separated from one another somehow. If question 2 builds on question one, make sure you can show both answers independently.
8. Good luck, and have fun!

## Tic - Tac - Toe

All of the remaining questions will be related to the game tic tac toe.

Here are the rules of Tic-Tac-Toe:

* Players take turns placing characters into empty squares (" ").
* The first player A always places "X" characters, while the second player B always places "O" characters.
* "X" and "O" characters are always placed into empty squares, never on filled ones.
* The game ends when there are 3 of the same (non-empty) character filling any row, column, or diagonal.
* The game also ends if all squares are non-empty.
* No more moves can be played if the game is over.

You can get creative with how you display the board, but a simple way is just use * as empty spaces.
An empty board would look like:  
    * * *  
    * * *  
    * * *  
In the following grid, 7 turns were taken ending with a win by player 1 (X)  
    X X X  
    O O X  
    * * O  
In the following grid, no move were left so it was a draw  
    X X O  
    O O X  
    X O X  
      
Ok, let's get started on the questions.

## Question 1
Provide 2 examples of possible data structures to describe the game board. Think about an empty board, partially completed, and fully completed.

## Question 2
Using your favorite model from Question 1, Write a method that takes a game board as input and returns which player has won.

## Question 3
Write a method that takes a game board as input and returns a boolean of whether the game is complete or not.

## Question 4
Write unit tests and sample cases for Questions 2 and 3
