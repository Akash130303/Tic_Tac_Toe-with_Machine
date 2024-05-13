# Tic_Tac_Toe-with_Machine
 Tic-Tac-Toe game with machine using python and tkinter

The code implements a Tic-Tac-Toe game with an AI opponent using the Tkinter library in Python. Here's a brief description of its components:

Class Structure:
The code defines a class TIC_TAC_TOE_AI that encapsulates the game logic and GUI elements.
The constructor __init__ initializes the game window and various attributes required for the game.

GUI Setup:
The GUI setup involves creating buttons for the Tic-Tac-Toe grid, control buttons for choosing the game mode, and a reset button.
Buttons are arranged using the Tkinter Canvas widget.

Game Logic:
The game alternates between human and AI moves.
The AI employs a simple strategy based on predetermined moves and techniques to play optimally.
The __machine_play method handles the AI's moves, while the __human_play method handles human moves.
The game checks for win or draw conditions after each move and displays appropriate messages using messagebox.

Game Control:
Players can choose between playing against the AI as the first or second player.
A reset button allows players to restart the game.

End Game Handling:
Once the game is won or drawn, further moves are disabled, and the reset button is enabled to start a new game.
Overall, this code provides a functional implementation of a Tic-Tac-Toe game with a simple AI opponent that makes strategic moves to challenge the player.
