# Name

React Tic-Tac-Toe

# Description

This is a React project to play a game of tic-tac-toe.
From the original code, I updated the square colors so that X is always a blue background with white letters,
and O is always a red background with black letters.
Also updated players from 0 and 1 to 1 and 2 to solve a bug where the winner could not be determined if the winner was player 0.

# Installation

Requires the index.html file, tictactoe.js, and winner.js files to be in the same directory.

# Usage

Load the HTML file in a browser to see the program.

# Support

No support is provided for this application.  Use at your own discretion.

# Roadmap

1. Will eventually add a button to reset the game, rather than requiring a reload of the browser.
 	* This should be able to be accomplished by unmounting the game-board and then re-rendering it.
2. Will also fix the following known bugs:
	* Player can change a square that has already been played.
		* This should be able to be accomplished by testing if value for the square's id in the state array is not null, and not calling renderSquare while it is.
	* Game does not end after a winner is declared or all squares are filled.
		* This should be able to be done by seeing if winner is defined, and if so, not calling renderSquare.
	* Game does not end after all squares are filled.
		* This bug should go away when the bugs listed above have been resolved.

# License information

MIT License in the LICENSE file in this directory.
