=====================================
=                                   =
=                                   =
=             Go Engine             =
=                                   =
=                                   =
=====================================

- Built for a Go AI competition
- Written in Golang
- Engine will first update AI then wait for a response

Build 0.0.1
Coded by Kai Ergin

Rules and Info:
AI has 60 seconds to make a move. If no move is made, AI automatically loses.
If an illegal move is made, engine will ask AI again for a correct move.
If 3 illegal moves are returned, AI automatically loses.

Note: Suicide IS recognized as a legal move.

Go AI MUST be written in Go.
For building the AI, moves can be typed out against your AI if debug = True.
When debug is on, board will be printed after each move.
To make a move, wait for input and type cordinates of move separated by a space.
To turn time off make time = False.
AI func to return a move should be called "returnMove". This will be the function the engine calls.
This function will receive one argument, [][]int, the board.
This function should return []int containing the coordinates of the move made.
To pass, the AI should return []int{-1,-1}.

Go rules can be found here:
http://www.britgo.org/intro/intro2.html
In end game, dead/hopeless strings WILL cause territory to become neutral.
- This will hopefully be changed/fixed in a later build.
Game will be played on a 19x19 board.

To run engine with your AI, type "go run engine.go <NAME OF AI>.go" .
Your AI should NOT have a main function. Only a returnMove function.
You can change the engine if you would like but only your AI will be submitted.
A slightly different engine will be used for the competition that can run two AIs.

Good luck!
