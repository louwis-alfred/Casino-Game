# Simple Casino Game 

Welcome to the **Simple Casino Game**! This is a Python-based slot machine simulator where you can deposit money, place bets, and spin the reels to try your luck. The game is designed to be simple, fun, and easy to understand.
Special thanks to Tim for the clear and educational guide!

---

## Features 
- **Deposit System**: Start by depositing money into your account.
- **Customizable Bets**: Choose how much to bet on each line.
- **Multiple Lines**: Bet on up to 3 lines for more chances to win.
- **Slot Machine Simulation**: Spin the reels and see if you win!
- **Winning Logic**: Check for matching symbols across the lines to calculate winnings.
- **Balance Tracking**: Keep track of your balance as you play.

---

## How to Play 
1. **Deposit Money**: Start by depositing an amount of your choice.
2. **Choose Lines**: Select how many lines you want to bet on (1-3).
3. **Place Your Bet**: Enter the amount you want to bet on each line.
4. **Spin the Reels**: The slot machine will spin, and the results will be displayed.
5. **Check Winnings**: If you match symbols across a line, you win! Your winnings will be added to your balance.
6. **Play Again or Quit**: Continue playing or quit the game and cash out your balance.

---

## Code Structure 
The game is built using Python and consists of the following key functions:

### 1. **Deposit**
- Prompts the user to deposit an initial amount of money.
- Ensures the input is valid and greater than 0.

### 2. **Get Number of Lines**
- Allows the user to choose how many lines to bet on (1-3).
- Validates the input to ensure it's within the allowed range.

### 3. **Get Bet**
- Prompts the user to enter the bet amount for each line.
- Ensures the bet is within the minimum and maximum limits.

### 4. **Spin the Reels**
- Simulates a slot machine spin by randomly selecting symbols for each column.
- Displays the results in a grid format.

### 5. **Check Winnings**
- Checks for matching symbols across the selected lines.
- Calculates the winnings based on the symbol values and bet amount.

### 6. **Main Game Loop**
- Keeps the game running until the user decides to quit.
- Updates the balance after each spin.

---
