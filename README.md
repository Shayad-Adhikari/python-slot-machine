# Python Slot Machine Game

A simple command-line **slot machine game** built with Python.  
Players deposit money, choose how many lines to bet on, place bets, and spin the slot machine to try their luck!

---

## Features

- 3×3 slot machine grid  
- Multiple betting lines (up to 3)  
- Configurable bet limits  
- Randomized symbol generation  
- Different symbols with different payout values  
- Balance tracking  
- Win/loss feedback after every spin  

---

## How the Game Works

1. The player deposits money.
2. The player selects:
   - Number of lines to bet on (1–3)
   - Bet amount per line
3. The slot machine spins randomly.
4. If all symbols in a selected line match:
   - The player wins based on the symbol’s value.
5. The game continues until:
   - The player quits, or
   - The balance reaches $0.

---

## Symbols & Payouts

| Symbol | Frequency | Value Multiplier |
|------|----------|------------------|
| @    | 2        | 5×               |
| #    | 4        | 4×               |
| &    | 6        | 3×               |
| ¥    | 8        | 2×               |

- Rarer symbols pay more.
- More common symbols pay less.

---

## Requirements

- Python 3.x  
- No external libraries required  

---

## How to Run

1. Clone or download the repository
2. Navigate to the project directory
3. Run the script:

```bash
python main.py
