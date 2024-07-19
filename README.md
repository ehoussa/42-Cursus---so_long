# Solong Project

The Solong project is a game development project at 42 Network that involves creating a simple 2D game using the `mlx` graphics library. The goal of the project is to build a game where the player navigates through a map, collects items, and reaches the exit while avoiding obstacles.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Gameplay](#gameplay)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The main goal of the project is to create a game called `solong` that includes the following features:

1. **Map Parsing**: Read and parse a map file that defines the game layout, including player position, collectible items, obstacles, and exit.
   
2. **Graphics and Controls**: Use the `mlx` graphics library to display the game window and handle user input for player movement.

3. **Game Logic**: Implement game logic to handle player movement, collision detection with obstacles, collecting items, and reaching the exit.

## Project Structure

The project consists of the following files:

1. **solong.c**: Contains the main logic for the `solong` game.
2. **map_parser.c**: Functions for parsing and validating the map file.
3. **render.c**: Functions for rendering the game graphics using `mlx`.
4. **player.c**: Functions for controlling player movement and interactions.
5. **map.txt**: Example map file defining the game layout.
6. **libft**: A library of utility functions (similar to the `libft` project) that may be used in `solong`.
7. **Makefile**: Defines compilation rules and dependencies for building the `solong` executable.

## Usage

To compile and run the `solong` game, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/ehoussa/42-Cursus---so_long/
    cd 42-Cursus---so_long
    ```

2. **Compile the program:**

    ```bash
    make
    ```

    This will compile the `solong` program and create an executable file called `solong`.

3. **Run the game:**

    ```bash
    ./solong map.txt
    ```

    Replace `map.txt` with your map file defining the game layout.

4. **Controls:**

    Use the arrow keys (up, down, left, right) to move the player character within the game window.

## Gameplay

The objective of the game is to navigate the player character through the map to collect all items (`C`) and reach the exit (`E`) while avoiding obstacles (`1`). The game ends when the player successfully reaches the exit.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
