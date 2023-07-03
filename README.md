# Minesweeper

Minesweeper is a classic puzzle game where players strategically uncover cells on a grid, avoiding hidden mines, using clues provided by adjacent numbers.

## Rules

1. The game is played on a grid of cells, where each cell can either be empty or contain a mine.
2. The objective of the game is to uncover all the cells that do not contain mines.
3. At the beginning of the game, the player is presented with a grid of covered cells.
4. The player can choose any cell to uncover.
5. If the chosen cell contains a mine, the game is over, and the player loses.
6. If the chosen cell does not contain a mine, it will reveal a number indicating the number of neighboring cells that contain mines.
7. Using the numbers as clues, the player must strategically uncover cells to avoid mines and uncover all safe cells.
8. If a cell with no neighboring mines is uncovered, all neighboring cells will automatically be uncovered recursively.
9. The game is won when all non-mine cells are uncovered.
10. The player can mark cells they suspect contain mines with a flag or question mark to help with their strategy.
11. The number of mines and the size of the grid can be adjusted to increase or decrease the difficulty of the game.

## Features

- Dynamic grid size: Choose from different difficulty levels: beginner, intermediate, and advanced.
- Random mine placement: Mines are distributed randomly on the grid for a unique gameplay experience.
- Strategic gameplay: Utilize the provided clues to deduce the locations of mines and safely uncover the remaining cells.
- Game over scenarios: Be cautious of mine detonations and the strategic reveal of safe cells.
- User-friendly interface: Enjoy a graphical user interface with a flagging system and a timer feature for competitive gameplay.

## Installation

1. Clone the repository: `git clone https://github.com/ghostrider1943/MineSweeper.git`
2. Compile the code using a C++ compiler.
3. Run the executable file.

## Usage

1. Choose the desired difficulty level.
2. Use the command line or graphical interface to select cells and make moves.
3. Avoid mines and strategically reveal safe cells.
4. Try to uncover all safe cells to win the game.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


