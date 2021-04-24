# Mastermind

<h2>What is Mastermind?</h2>
Mastermind is a board game where the computer randomly places four colored pegs in a row and the player has six guesses to guess which color and which order each peg is in. To help the player guess the correct colored sequence, after the player makes a guess, the computer shows the player a number of black pegs that represents the number of pegs in the correct color and position and a number of white pegs that represents the number of pegs in the correct color but not the correct position.


<h2>How was it Implemented?</h2>
The game is coded in python and is playable on the command line. The player can either choose to play the game or watch the computer play the game. Every time the player starts a new game, four pegs are randomly colored red, blue, yellow, green, purple, or orange. The computer checks the player's answer after each guess. When the computer plays the game, the pegs are given random colors just like when the player plays. The computer's algorithm when playing is based on Donald Knuth's algorithm. You can read more about his algorithm on Wikipedia. https://en.wikipedia.org/wiki/Mastermind_(board_game) .

<h2>What are Future Steps for this Project?</h2>
Currently, the game is playable on the command line. The player can choose to play the game or watch the computer play against itself. In the future, I would like make it playable on a GUI. Donald Knuth's algorithm should find the solution within 5 turns. Instead, this implementation takes, on average, 11 turns to find the solution. In the future, I would like to fix this.
