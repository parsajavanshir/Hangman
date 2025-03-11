# Hangman Game 🎯

A simple command-line Hangman game built with Python. The game selects a random word, and the player must guess the letters before they run out of lives.

## Features ✨
- Random word selection from a predefined word list.
- Keeps track of guessed letters and prevents duplicate guesses.
- Visual representation of remaining lives using ASCII art.
- Win or lose conditions are displayed appropriately.

## How to Play 🎮
1. Run the script.
2. Guess a letter by typing it and pressing Enter.
3. If the letter is in the word, it will be revealed in its correct position.
4. If the letter is incorrect, you lose a life.
5. The game continues until:
   - You guess the complete word (You win 🎉)
   - You run out of lives (Game over 😢)

## Installation & Setup ⚙️
### Prerequisites
- Python 3.x installed on your system.

### Clone the Repository
```sh
git clone https://github.com/parsajavanshir/hangman.git
cd hangman
```

### Run the Game
```sh
python main.py
```

## Project Structure 📁
```
📂 hangman
├── main.py             # Main game script
├── hangman_words.py    # List of words used in the game
├── hangman_art.py      # ASCII art for hangman stages & logo
└── README.md           # Project documentation
```

## Example Gameplay 📜
```
****************************<6/6 LIVES LEFT****************************
Word to guess: _ _ _ _ _ _
Guess a letter: a
Good job!
Word to guess: _ a _ _ _ a _
```

## Contribution 🤝
Feel free to fork this project and submit pull requests if you want to improve the game!

## License 📝
This project is open-source and available under the MIT License.

