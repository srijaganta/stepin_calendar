# stepin_tic-tac-toe
GAME DESCRIPTION


Tic-tac-toe is a two player game (one of them being your computer program). The two players take turns putting marks on a 3x3 board. The player who first gets 3 of his/her marks in a row (vertically, horizontally, or diagonally) wins the game, and the other loses the game.


Game Rules


A game will consist of a sequence of the following actions:
Initially, your program should ask the user which marks the user prefers ("X" or "O"). The player that gets to play with the "X" marks will play first (we call him/her player 1) and the player that gets to play with the "O" marks will play second (we call him/her player 2).


Player 1 and 2 take turns making moves. A move (mark row column) should satisfy the following constraints:


Time Limit There is a 1 minute time limit for a player to make his/her move. (1 min. user time, not CPU time.)


Move preconditions

mark is "X" if it is player 1's turn and "O" if it is player 2's turn.

The position (row, column) on the board is empty.


Move postconditions

After the move, the position (row, column) on the board will be occupied by a mark .

It will be the other player's turn.

The game ends when either:

one of the players wins the game, i.e. this player gets three of his/her marks in a row (vertically, horizontally, or diagonally).

all the positions on the board are occupied. In this case, the game ends in a draw.

![code inspector](https://www.code-inspector.com/project/28225/score/svg)
![code inspector](https://www.code-inspector.com/project/28225/status/svg)

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/32a0ddd9e5d64e5fb951b90d5fb794a3)](https://www.codacy.com/gh/srijaganta/stepin_tic-tac-toe/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=srijaganta/stepin_tic-tac-toe&amp;utm_campaign=Badge_Grade)


[![Git Inspector](https://github.com/srijaganta/stepin_tic-tac-toe/actions/workflows/Git%20Inspector.yml/badge.svg)](https://github.com/srijaganta/stepin_tic-tac-toe/actions/workflows/Git%20Inspector.yml)


[![Cpp check](https://github.com/srijaganta/stepin_tic-tac-toe/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/srijaganta/stepin_tic-tac-toe/actions/workflows/cppcheck.yml)


[![Static Code Analysis](https://github.com/srijaganta/stepin_tic-tac-toe/actions/workflows/static.yml/badge.svg)](https://github.com/srijaganta/stepin_tic-tac-toe/actions/workflows/static.yml)
