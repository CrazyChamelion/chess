# chess
chess in python

## Current State
- Takes turns
- Select a piece of correct color to see possible moves
- Escape to select another piece
- Pick one of the possible moves to move
- Detects check and draws the square under the king in orange
- Detects check mate and draws the square under the king in blue

## Known Bugs
- Allows castle through check or out of check
- Does not handle en passant

## use

```bash
python chess.py
```

### venv

create the venv
```bash
python -m venv venv
```

activate the venv windows
```bash
.\venv\Scripts\activate.bat
```
activate the env linux
```bash
source venv/bin/activate
```

### requirements
```bash
pip install -r requirements.txt
```
