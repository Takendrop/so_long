# so_long

**so_long** is a 2D game developed in C using the MiniLibX library. The goal is to navigate a character through a map, collect items, and reach the exit.

## Features

- **Player Movement**: Use `W`, `A`, `S`, `D` to move the player. The player cannot move through walls.
- **Collectibles**: Collect all items (`C`) before reaching the exit (`E`).
- **Map Format**: The map is defined in a `.ber` file and includes:
  - `1`: Wall
  - `0`: Empty space
  - `C`: Collectible
  - `P`: Player start position
  - `E`: Exit
- **Collision Detection**: Prevents movement through walls and checks interactions with collectibles and the exit.
- **Movement Counter**: Displays the number of moves in the shell (or on-screen as a bonus).
- **Window Management**: Smooth window handling. `ESC` or close button exits the game.
- 
## How to Run

1. Compile the program:
    ```sh
    make
    ```
2. Run the game with a map file:
    ```sh
    ./so_long ./maps/map2.ber
    ```
