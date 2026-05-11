# Tic-Tac-Toe, Human vs. AI

A simple **terminal/CLI Tic-Tac-Toe** game written in Python where you play against an AI with three difficulty levels:
**Easy**, **Medium**, and **Impossible**.

The game runs locally in your terminal and prompts you to:
- Choose a difficulty level
- Choose your mark (`x` or `o`)
- Enter moves as `row col` using 0–2 indices

## Prerequisites

- **Python 3.8+** (recommended: Python 3.10+)

No external dependencies are required.

## Setup

### 1) Clone this repo from GitHub

```bash
git clone <YOUR_GITHUB_REPO_URL>
cd <YOUR_REPO_FOLDER>
```

### 2) (Recommended) Create and activate a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
python --version
```

### 3) Run the project locally

```bash
python3 main.py
```

You’ll be asked to choose:
- Difficulty: `Easy`, `Medium`, or `Impossible`
- Mark: `x` or `o`

Then play by entering moves like:

```text
Enter your move (row and column from 0-2, e.g., '1 2'): 1 2
```

## Notes

- The board uses `-` for empty cells.
- Rows and columns are **0, 1, 2**.