# 🎰 Slot Machine Game

A simple terminal-based slot machine game built with **Node.js**. Users can deposit money, place bets on multiple lines, and spin to try their luck!

## 💡 Features

- Deposit and bet system
- Supports betting on 1 to 3 lines
- Randomly generated symbols with values
- Winnings calculated based on symbol values
- Repeat gameplay until the balance runs out
- Built-in CLI input with `prompt-sync`

  1.## 🧠 How It Works

1. The user deposits money.
2. Chooses how many lines (1-3) to bet on.
3. Enters a bet amount per line.
4. Spins the slot machine.
5. Wins money if matching symbols appear on any line.
6. Can play again or quit.

## 🛠️ Tech Stack

- **Node.js**
- **prompt-sync** (for command-line input)

## 🧪 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Ramkrishnan007/slot-machine-game.git
cd slot-machine-game

2. Install dependencies
bash
Copy code
npm install

3. Start the game
bash
Copy code
npm start

📦 Project Structure
bash
Copy code
slot-machine-game/
├── slot-machine.js     # Main game logic
├── package.json        # Project metadata and dependencies
├── .gitignore          # Ignoring node_modules
└── README.md           # Project information

📸 Demo
mathematical
Copy code
Enter a deposit amount: 100
Enter the number of lines to bet on (1-3): 3
Enter the bet per line: 5
A | A | A
D | B | C
C | D | B
You won, $75
Do you want to play again (y/n)? n

📄 License
This project is open-source and free to use for educational purposes.
```
