# Lab04-Tic-Tac-Toe
Tic Tac Toe game made through C#

### To play, just download and hit start.
First, it will ask for a name for player 1. Then a name for player 2. Once both names are entered, the games begin.  
  
The numbers 1-9 will display in a tic-tac-toe pattern. 1-3 make the first row, 4-6 the second row, and 7-9 the third row.  
Player one types a number 1-9 and hits enter to choose a spot on the game. Then to player 2, then back, then forth, etc.  
When a winner is decided, the program will tell you who has won, and the game will end.  
Try it out!  
  
### Classes
Game class -> declares how the game is played, checks for winners, etc.  
Board class -> declares and returns the new board  
Player class -> creates different players and has methods to change their turns  
Position class -> behind the scenes work to decide which position the numbers 1-9 relate to  
  
These classes are all put together in the program and they run the game by checking for winners, starting the next turn, displaying the board, all in the console.  
