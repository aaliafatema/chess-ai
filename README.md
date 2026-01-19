# chess-ai

A playable chess game with a built-in AI opponent and local graphical interface.  
The project uses Python and Pygame to render the board, handle user input, and run the game loop.  
The AI uses heuristic evaluation to choose moves and react to the player's actions.

---

## Features

- Full chess game rules (moves, captures, check, checkmate)
- AI opponent with move scoring
- Local player vs AI gameplay
- GUI rendered using Pygame
- Sound and piece asset packs included
- Runs locally with no internet required

---

## How to Run

### **1. Install dependencies**

```bash
pip install -r requirements.txt
````

### **2. Start the game**

```bash
python src/main.py
```

> Make sure assets remain in the `assets/` directory relative to `src/` as provided.

---

## Requirements

* Python 3.8+
* Pygame

Install via:

```bash
pip install pygame
```

---

## Folder Structure

```
chess-ai/
 ├── src/
 │   ├── main.py          # Game loop + UI
 │   ├── engine.py        # Board + move generation logic
 │   ├── chess_ai.py      # AI logic + evaluation
 │   └── __init__.py
 ├── assets/
 │   ├── images/          # Piece set #1
 │   ├── images_alt/      # Piece set #2
 │   └── sounds/          # SFX for moves and captures
 └── README.md
```

---

## Gameplay

* Click to select a piece
* Click on a valid move to execute
* AI makes a move after player turn
* Supports normal capture and basic rules
* Includes sound feedback

---

## Future Improvements (Optional Ideas)

* Minimax or Alpha-Beta search
* Multiple AI difficulty levels
* Checkmate/Draw detection improvements
* Highlight valid moves
* Undo moves
* Network multiplayer
* Piece skins selector
* Opening book for stronger play

---

## Assets

Assets used for pieces and sounds are included in the repository for local use.

---

## License

This project is provided for learning and experimentation.
You may modify or build upon it for personal use.

```
