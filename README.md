**Slot Machine Game** 

This Slot Machine Game is a simple command-line application written in JavaScript. Players can deposit money, place bets on up to three lines, spin the slot machine, and win based on the combination of symbols displayed. The game continues until the player runs out of money or chooses to stop playing.

**Basic Actions**

1. Deposit Money: The player is prompted to enter a deposit amount to start the game.
2. Bet on Lines: The player selects the number of lines (1 to 3) to bet on.
3. Place Bet: The player sets a bet amount for each line.
4. Spin the Slot Machine: The slot machine reels spin and display a combination of symbols.
5. Check Winnings: The game calculates the winnings based on the bet amount and the symbols displayed on the lines bet on.
6. Play Again: The player can choose to play again if they have a remaining balance or stop the game.


**Features**

Deposit: Input the amount of money to deposit into the game.
Betting Lines: Choose the number of lines to bet on (1 to 3).
Bet Amount: Set the bet amount for each line.
Spinning Reels: Simulate the spinning of slot machine reels and display the outcome.
Winnings Calculation: Automatically calculate and display the winnings based on the bet and the outcome of the spin.
Replay Option: Option to play again or quit the game after each round


**Running the Game**
1. git clone https://github.com/yourusername/slot-machine-game.git
cd slot-machine-game
2. npm install prompt-sync
3. node project.js

**Example Game Play**

1. Enter a deposit amount: 100
2. You have a balance of $100
3. Enter the number of lines to bet on (1-3): 2
4. Enter the bet per line: 10
A | B | C
D | A | D
C | C | B
6. You won, $0
7. You have a balance of $80
8 . Do you want to play again (y/n)? y

