
# Sudoku Game

A **Python-based Sudoku game** built with **Pygame**, featuring interactive gameplay and a built-in solver.

## 🎮 Features

- Interactive grid with highlighted selection  
- Manual number input with conflict checking  
- Temporary "sketch" numbers for in-progress moves  
- Confirm entries with **Enter**, clear with **Delete**  
- Auto-solve feature via **spacebar**, visualizing backtracking  
- Clean UI with real-time validation of entries

## 🧩 Requirements

- Python 3.x  
- Pygame library (`pip install pygame`)

## 🚀 Installation

1. Clone or download this repository:  
   ```bash
   git clone https://github.com/VineethaPadma/Sudokugame.git
   cd Sudokugame
   ```
2. Install dependencies:  
   ```bash
   pip install pygame
   ```

## ▶️ Usage

Run the game script:
```bash
python sudoku.py
```
(or whichever Python file contains the main loop.)

## 🕹️ Controls

- **Mouse Click**: Select a cell  
- **Number Keys (1–9)**: Input (sketch) a number  
- **Enter**: Lock in the number  
- **Delete**: Clear the cell  
- **Spacebar**: Trigger solver animation  
- **Window Close**: Exit game

## 🧠 How It Works

- Uses a classic **backtracking algorithm** to solve puzzles  
- GUI driven by Pygame — real-time rendering and event handling  
- Board logic and solving routines encapsulated in modular classes

## 📈 Future Improvements

- Multiple difficulty levels (easy/medium/hard)  
- Hint system to suggest the next move  
- Save/load game states  
- Timer and score tracking  
- Enhanced graphics and animations

## 📝 Contributing

Contributions are welcome! If interested:
- Open an issue to discuss your idea  
- Submit a pull request with your changes

## 📄 License

This project is (specify license, e.g., MIT).
