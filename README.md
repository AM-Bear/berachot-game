# Berachot Game

A board game about berachot (blessings), written in Python with Pygame for a school project.

## How it plays

- 56 tiles on a snaking board, 2 to 4 players
- Question tiles in three categories: Daily (D), Food (F) and Special (S), about 60 questions in all
- Star tiles give a bonus move for a correct answer
- Prayer tiles let you pick the question category
- Wrong answer: move back 1 to 3 spaces
- Black hole: fall back to the previous black hole
- First to the END tile wins

## Run it

```sh
pip install pygame
python blessing_journey.py
```

Press F for fullscreen and Esc to quit. Sound files in `sounds/` are optional; the game runs without them.
