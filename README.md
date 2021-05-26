TIC-TAC-TOE GAME

In this Project i have create an offline 2 player Tic Tac Toe game. We will code the whole game logic, count player points, add a reset functionality and handle orientation changes, so we don’t lose our game state when we rotate the device.

We will create the layout by creating 9 buttons within nested LinearLayouts and we will even them out over the screen by adding the layout_weight attribute. Our player points and reset button will be in a RelativeLayout and we will create a 2 dimensional array of buttons, we will dynamically assign them with findViewById and set OnClickListeners on them by using a nested for-loop.We will handle the clicks on our playing field, switch between players and implement a method that checks for a winner at the end of each turn, by going through all rows, columns and diagonals of our playing field and checking if one of them has 3 matching fields. An integer variable will count each round, so we know, that if we don’t have a winner after 9 rounds, we have a draw.

Next we will finish the winning logic by updating the player points and resetting the board and variables and we will also take care of draw situations.we will also take care of configuration changes (like an orientation change), by giving our TextViews and Buttons the “freezesText” attribute and saving our member variables in onSaveInstanceState. 

We will restore these values in onRestoreInstanceState so we don’t lose our game progress.
Also we will implement a restart functionality, which resets our board, points and round count.

GAME LAYOUT SCREENSHOT

![image](https://user-images.githubusercontent.com/59703066/119693025-86f55280-be69-11eb-8657-61bc17b120aa.png).

![image](https://user-images.githubusercontent.com/59703066/119693177-abe9c580-be69-11eb-9184-65b7b3a4d9b8.png)

After RESET:-

![image](https://user-images.githubusercontent.com/59703066/119693274-befc9580-be69-11eb-94c3-d584f3459cce.png)




