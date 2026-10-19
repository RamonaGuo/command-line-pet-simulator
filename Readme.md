# Command Line Pet Simulator

A Python command-line pet game with cats, dogs, and JSON save files.

## Requirements

Python 3.10 or later. No third-party packages required.

## Start a new game

```bash
python pet.py --mode new --type cat --name ***
```

## Resume a saved game

```bash
python pet.py --mode load
```

Create a pet and quit with `q` before loading a saved game.

## Commands

- `p`: Play
- `f`: Feed
- `s`: Show status
- `v`: Hear your pet's voice
- `q`: Save and quit

The save file is stored beside `pet.py`.
Only one save slot is available; saving overwrites the previous save.