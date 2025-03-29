# Sudoku Generator with PyGame

This project is a simple Sudoku generator built using Python and the PyGame library.

## Features
- Generates random Sudoku puzzles
- Allows user interaction to input numbers
- Provides a graphical interface using PyGame

## Setup Instructions

### 1. Create a Virtual Environment
It is recommended to use a virtual environment to manage dependencies.

```sh
python -m venv venv
```

### 2. Activate the Virtual Environment
- **Windows:**
  ```sh
  venv\Scripts\activate
  ```

### 3. Install Dependencies
Ensure you have `pip` installed and up to date, then install the required packages from `requirements.txt`.

```sh
pip install -r requirements.txt
```

If `requirements.txt` is missing, manually install `pygame`:

```sh
pip install pygame
```

### 4. Run the Sudoku Generator
To start the application, run:

```sh
python Sudoku_GUI.py
```

## File Structure
```
.
├── Sudoku.py         # Sudoku logic implementation
├── Sudoku_GUI.py     # GUI implementation with PyGame
├── requirements.txt  # List of dependencies
├── README.md         # Project documentation
└── __pycache__/      # Cached Python files (auto-generated)
```

## License
This project is based on open-source resources.

