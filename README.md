# Tic-Tac-Toe AI Game

## Overview

This project implements a Tic-Tac-Toe game where a human player competes against an AI. The AI's decisions are guided by Q-tables, allowing it to learn and improve its gameplay over time. The game is implemented in Python and uses various libraries for displaying and analyzing the game state.

## Features

- **Game Board Display**: The game board is displayed in a human-readable format with 'X' and 'O' representing the moves of the AI and human players, respectively.
- **AI Integration**: The AI uses Q-tables to make decisions and improve its strategy. The Q-tables are loaded from a JSON file.
- **Interactive Gameplay**: Players can choose their moves and see the game progress with real-time updates.
- **Visualization**: The expected reward for each move is visualized using a heatmap.

## Files

- `Tic-Tac-Toe.py`: Contains all the code for the game. This includes the game logic, AI integration, and human interaction.

## Requirements

- Python 3.x
- `numpy`
- `matplotlib`
- `seaborn`
- `IPython`

You can install the necessary Python packages using pip:

```bash
pip install numpy matplotlib seaborn ipython

```

## Usage

1. **Prepare Q-Tables**: Ensure you have a JSON file with Q-tables for the AI. This file should be named `randomfirst.json` or modify the code to use a different file name.

2. **Run the Game**: Execute the Python script to start the game. The AI will make moves based on the Q-tables, and the human player will be prompted to make a move.

    ```bash
    python Tic-Tac-Toe.py
    ```

3. **Game Interaction**: The game will prompt the human player to choose a move (0-8). The AI will then make its move, and the game will display the updated board and the result.

## Gameplay

* The AI and human players take turns to make a move.
* The game continues until a win condition is met or all cells are filled (resulting in a tie).
* The AI's performance can be improved by updating the Q-tables with new data.

## Example

Here's a brief overview of the game interaction:

```plaintext
Where would you like to play (0-8): 4
```
The game board will be displayed, and the AI will make its move. The result of the game will be shown at the end.

## Contributing
  
Feel free to contribute to this project by improving the AI's performance, adding new features, or fixing any issues. Fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
