# Hangman Game (Python)

This is a simple **Hangman game** implemented in Python as a beginner-level project.  
The game randomly selects a word, and the player must guess the letters before running out of lives.

This project helped me practice **loops, conditionals, strings, and basic game logic** in Python.

---

## 🧠 How the Game Works

- A word is randomly chosen from a predefined word list.
- The player guesses one letter at a time.
- If the guessed letter is incorrect, the player loses one life.
- ASCII art is displayed to show the hangman stages based on remaining lives.
- The game ends when:
  - All letters are guessed correctly → **You win**
  - Lives reach zero → **You lose**

---

## 🛠 Concepts Used

- `while` loop (game continues until win or lose)
- `for` loop (to build and update the word display)
- `if-elif-else` conditions
- Strings and string comparison
- Lists (used for hangman stages)
- `random.choice()` for word selection
- User input handling

---

## ▶️ How to Run the Program

1. Make sure Python is installed on your system.
2. Clone this repository or download the file.
3. Run the program using:

```bash
python hangman.py

