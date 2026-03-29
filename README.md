Overview:
This assignment contains the implementation of an UNO game played between 3 players using two AI strategies such as minimax (Defensive) + expectimax(offensive) and a third player has an option to play manually as well.

Goal: 
Simulate the algorithms and their decisions.

Features:
UNO game rules are implemented.
Depth limited minimax search using evaluation function.
Depth limited expectimax search using evaluation function.
Evaluation Function: Score = 50 - 5*(Cards in hand) + 2*(Average opponent cards) + 3*(Number of Skip cards)
Interactive user play against AIs.
Game Tree Simulation

How to Run:
Open the .ipynb file named "i242510_AbdullahWaheed_A#2"
Run All The Cells 
In playgame(mode = "manual"), Select "ai" if you want to be a viewer or "manual| if you want to play yourself
Use (0,1,2,3,4) as inputs for selectiong the cards if you play as user

