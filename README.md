# casino-game
This project is a simple text-based Slot Machine Casino Game built in Python. It simulates a slot machine where a player can deposit money, place bets on one or more lines, spin the slot machine, and potentially win money based on matching symbols. 



Deposit Money:
The player starts by depositing any amount of money.

Betting:
The player selects how many lines to bet on (1 to 3 lines).Then, the player places a bet amount for each line.

The total bet is calculated as:
total_bet = number_of_lines × bet_per_line

Spinning the Slot Machine:
The slot machine consists of a 3x3 grid (3 rows, 3 columns).
Each slot displays a symbol (A, B, C, or D) randomly chosen with weighted probability based on predefined symbol counts.

Winning Logic:
The game checks if all symbols in a line (horizontal row) match across all columns.
If matched, the player wins based on the symbol's value.

Winnings are calculated as:
winnings = symbol_value × bet_amount

Repeat or Quit:
The player can continue playing or quit at any time.
The final balance is displayed upon exiting.
