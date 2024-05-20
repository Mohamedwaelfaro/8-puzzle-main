# 8-Puzzle Solver

This project implements an 8-puzzle solver using the Greedy Best-First Search and A* (A-star) algorithms. The 8-puzzle, also known as the sliding puzzle, consists of a 3x3 grid with numbered tiles from 1 to 8 and one empty space. The goal is to rearrange the tiles to match a target configuration by sliding the tiles into the empty space.

## Features

- **Greedy Best-First Search**: Uses a heuristic to prioritize the tiles closest to the target configuration.
- **A* Search Algorithm**: Combines the heuristic of Greedy Best-First Search with the cost to reach the current state for optimal pathfinding.
- **Customizable Initial and Goal States**: Allows users to define their own starting and goal configurations.

## Technologies Used

- Python
- Heuristic functions for efficient searching

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/8-puzzle-main.git
    ```
2. Navigate to the project directory:
    ```sh
    cd 8-puzzle-main
    ```
3. (Optional) Create and activate a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Define the initial and goal states in the `solver.py` script.
2. Run the solver:
    ```sh
    python solver.py
    ```
3. The solution path and steps will be displayed in the console.

## Contributing

Contributions are welcome! Please open an issue to discuss your ideas or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
