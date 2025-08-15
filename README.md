🎰 Python Slot Machine Game
A simple command-line slot machine game built in Python. Players can deposit money, choose the number of lines to bet on, set their bet amount, spin the reels, and win based on matching symbols.

📜 Features
* Deposit any positive starting balance.
* Choose 1 to 3 lines to bet on.
* Set bet amount within a min/max range.
* Randomized spins using Python’s random module.
* Calculates winnings based on symbol values.
* Displays winning lines and total winnings.
* Simple and easy-to-read code structure.

🖥️ How It Works
1. Deposit an amount to start playing.
2. Choose the number of lines you want to bet on.
3. Set your bet per line (within limits).
4. Spin the slot machine and see if you win!
5. Continue playing until you choose to quit or run out of money.

🔢 Symbol Information
Symbol	Count in Reels	Value (Multiplier)
A	2	5×
B	4	4×
C	6	3×
D	8	2×
📦 Requirements
* Python 3.x
* No external libraries needed (uses built-in random module)

🚀 How to Run
1. Clone this repository:    git clone https://github.com/yourusername/slotmachine.git
2.   
3. Navigate into the folder:    cd slotmachine
4.   
5. Run the program:    python slotmachine.py
6.   

📝 Example Gameplay

what would you like to deposit? 100
enter the number of lines to bet on (1-3)? 3
what would you like to bet? 5
You are betting $5 on 3. Total bet is equal to: $15
A | B | C
D | B | C
A | A | A
you won $25
you won on lines: 3

📌 Notes
* Minimum bet: $1
* Maximum bet: $100
* The game continues until you choose to quit (q) or run out of money.
* Winning lines are horizontal only.
