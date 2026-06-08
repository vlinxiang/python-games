# 🐍 Python Projects for Beginners

A collection of 16 beginner-friendly Python projects covering games, utilities, and tools — all built with core Python concepts and a handful of lightweight libraries.

---

## 📁 Projects

### 🎮 Games

| Project | Description |
|---|---|
| `number_guessing_game.py` | Guess a random number between 1–100 with high/low hints |
| `rock_paper_scissor.py` | Classic Rock, Paper, Scissors against the computer with emoji display |
| `dice_rolling_game.py` | Roll two dice as many times as you want |
| `cows_and_bulls_game.py` | Guess a secret 4-digit number — bulls are exact matches, cows are right digit wrong position |
| `word_guessing_game.py` | Guess a hidden word letter by letter (reads from `words.txt`) |
| `pig_dice_game.py` | Two-player dice game — roll and bank points, but rolling a 1 loses your turn |
| `slot_machine.py` | Bet and spin a slot machine with a starting balance |
| `tic_tac_toe.py` | Two-player Tic Tac Toe with colored terminal output |
| `quiz_game.py` | Multiple choice trivia quiz with randomized questions and scoring |

### 🛠️ Utilities & Tools

| Project | Description |
|---|---|
| `atm.py` | ATM simulator — deposit, withdraw, and check balance with input validation |
| `todo_list.py` | Terminal-based to-do list — add, view, and remove tasks |
| `simple_text_editor.py` | Read and write text files from the terminal |
| `currency_converter.py` | Convert amounts between USD, EUR, and CAD |
| `password_generator.py` | Generate secure passwords with customizable length, uppercase, numbers, and special characters |
| `password_strength_checker.py` | Score a password's strength based on length, case, digits, and special characters |
| `qr_code_generator.py` | Generate a QR code image from any text or URL |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x

### Install dependencies
Most projects use only the Python standard library. A few require external packages:

```bash
pip install termcolor qrcode[pil]
```

- `termcolor` — used by `tic_tac_toe.py` and `quiz_game.py` for colored terminal output
- `qrcode` — used by `qr_code_generator.py`

### Run a project
```bash
python number_guessing_game.py
python rock_paper_scissor.py
python tic_tac_toe.py
# etc.
```

---

## 📚 Concepts Covered

- Functions and classes
- Loops and conditionals
- Input validation and error handling
- File I/O
- Random number generation
- String manipulation
- Object-oriented programming (ATM)
- Regular expressions (password checker)
- External libraries (qrcode, termcolor)

---

## 📝 Notes

- `word_guessing_game.py` requires `words.txt` to be in the same directory
- `currency_converter.py` uses hardcoded exchange rates — not live data
- All games are terminal-based with no GUI
