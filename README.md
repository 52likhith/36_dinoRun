# Dino Run Repair Lab

A side-scrolling endless-runner game built with Python and Pygame. This project was completed for VibeCoding Lab 4, Problem #36.

## Features

- Fixed the high-score comparison so a new best score is saved to `dino_highscore.txt`.
- Changed the dino's color while it is airborne.
- Added a popup when the dino successfully passes an obstacle.
- Implemented double jump.
- Kept obstacle spawning, increasing game speed, collision detection, game-over, and restart behavior.

## Requirements

- Python 3.10 or later
- Pygame

## Run the Game

Install Pygame:

```bash
pip install pygame
```

Start the game:

```bash
python game.py
```

**Controls:** Press Space, Up Arrow, or W to start and jump. Use the same keys to restart after Game Over.

## Project Structure

```text
36_dinoRun/
├── game.py
├── README.md
├── .gitignore
├── dino_highscore.txt
└── chat_history/
    ├── DinoRun_Copilot_Chat_History.pdf
    └── chat.json
```

- `game.py`: Main game implementation.
- `README.md`: Project overview and instructions.
- `.gitignore`: Files excluded from Git.
- `dino_highscore.txt`: Local high-score save file, if tracked or present.
- `chat_history/`: Copilot chat export and readable transcript for lab evidence.

## Lab Evidence

The `chat_history/` folder contains the original JSON export and a readable PDF transcript of the Copilot conversation. Keep the before- and after-changes gameplay recordings with your lab submission, in the location required by your instructor.

