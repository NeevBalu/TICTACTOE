# TICTACTOE
creating a two player mobile game with an algorithm that can play against you. Players will be able to choose their own shapes and can keep score of wins. 

Rules for Tic Tac Toe Classic Edition:
- classic tic tac toe game but with the ability to choose yoour shapes. Not only limited to X or O 
- Defalt will be X and O if the user diesn't change them
- three by three board with 9 total spaces for the shapes to go in
- each player will go one at a time, player 1 will state then player 2 will have a chance to go
- to win, a player must get three in a row, vertically, horizontally, or diagonally
- will keep tally of who won in each game to designate the next game starting player
- a tie will be called if none of the players get three in a row
- if game ends in toe, a randomizer is used to choose the first player
- all rules will be in a tab called Game Rules in the navigation bar
  
Home Screen:
- score board will be on the top of the screen, score increases when a player wins and will be added to the winners score
- No logging in, when opening the app, we ask for the players names which is used to change the scores of the players, if not, we will create a new row with a new score
- when opening the app, the logo will be animated and then a large Start Game button will pop up, when clicked, a new game will start

Game Screen:
- ask user to input names
- user will use their keyboard to customize their designated symboles that will reset when a new game is started
- there will be a default button where the names will be defaulted to "Player 1" and "Player 2" and the shapes will be "X" and "O"
- user clicks on start and the screan will present a three by three board. above the board, a test will be shown saying which players turn it currently is. when a user taps the screen at any of the empty boxes, the player's shape will be added
- Note: you cannot tap on a occupied box, player must choose an empty box for their move to end
- the game screen applies all the logic given in the Rules written above
- when the user clicks "Finish Game" a pop up screen will show saying "Congratualtions ____ (default or user specified name) in winning" if game ends in a tie, it will show "Tie game"
- below the statement, a "Home Screen" button will be present to go back to the home screen, where the score board is updated

Timeline:
P0: develop the game screen and impliment the rules
P1: develop the home screen and the backend Firebase system to store scores
P2: implementations of future editions 
P3: use a computer algorithm to replace a player if there is only one user playing


Future editions:
- speed edition with a short time and each interval of time that has passed, the winner will get less points in their win, i.e. 1:00 time but every 15 seconds that pass, the points go from 4 to 3 to 2 to 1
- 3 symboles edition where the players will only have 3 of their chossen shapes, and after placing all three on the board, the 4th play will move the first play's positions to the new position
