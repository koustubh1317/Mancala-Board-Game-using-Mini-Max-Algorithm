# Project : Mancala-Board-Game-using-Mini-Max-Algorithm
# Made By - Koustubh sinha

* The mancala game consists of two-player,which is a turn-based strategy board games played
with small stones, beans, or seeds and rows of holes or pits in the earth, a board or other
playing surface. The objective is usually to capture all or some set of the opponent's
pieces.

![image](https://user-images.githubusercontent.com/54525819/203593100-58a4b95f-e999-4b92-9c61-43109c5a76cc.png)

* I tried to implement ***Mancala game*** using ***Mini-Max Algorithm and Alpha-Beta pruning*** .

![image](https://user-images.githubusercontent.com/54525819/203593286-cce4f432-3b83-4f5f-98de-fb4fab74eb0e.png)

# Mini-Max Algorithm (Alpha Beta Pruning)

* ***Alpha Beta pruning*** is an optimization technique for min-max algorithms that would
reduce the number of branch / node extensions to get better and faster results. In this
project we are implementing the famous African board game “Mancala” using the
min-max algorithm (Alpha Beta Pruning).

* ***Minimax is a kind of backtracking algorithm*** that is used in decision making and game
theory to find the optimal move for a player, assuming that your opponent also plays
optimally. It is widely used in two player turn-based games such as Tic-Tac-Toe,
Backgammon, Mancala, Chess, etc.

* ***In Minimax the two players are called maximizer and minimizer. The maximizer tries to
get the highest score possible while the minimizer tries to do the opposite and get the
lowest score possible.***

* Every board state has a value associated with it. In a given state if the maximizer has the
upper hand then, the score of the board will tend to be some positive value. If the
minimizer has the upper hand in that board state then it will tend to be some negative
value. The values of the board are calculated by some heuristics which are unique for
every type of game.

# Mancala Board game Representation 

![image](https://user-images.githubusercontent.com/54525819/203593437-f820b97a-e019-49d0-b7af-1f84dceab3bd.png)

* Both the player will have 6 cups each containing 4 stones each . ***For Player 1 it will be from index 1 to 6 and for Player 2 it will be from index 8 to 13 .***

* ***The Mancala box for Player 1 will be at Index 7 and for player 2 will be at Index 0 .***

* We tried to make 2 type of gameplay (i) Player Vs Player  (ii) Player Vs AI(Bot) .

* ***The final result of game will be calculated on the basis of which player have a sum total of stones in their mancala box more compared to other .***

