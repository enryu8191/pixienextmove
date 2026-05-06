# PixieNextMove Bot

A standalone Python bot for finding the best next move in **Pixie Chess**.

## Features
- Full chess rules using `python-chess`
- Minimax AI with alpha-beta pruning
- Extensible system for Pixie Chess magical abilities
- Interactive CLI interface

## Installation
```bash
git clone https://github.com/enryu8191/pixienextmove.git
cd pixienextmove
pip install chess
```

## Usage
```bash
python pixie_next_move_bot.py
```

Paste FEN positions from pixiechess.xyz to get expert move recommendations.

## Adding New Pixie Pieces
Edit the `PIXIE_OVERRIDES` dictionary and `apply_pixie_overrides()` function in `pixie_next_move_bot.py` to support new magical abilities.