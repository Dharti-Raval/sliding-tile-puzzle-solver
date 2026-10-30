# Slide — N-Puzzle Solver

An interactive N-Puzzle game and optimal solver built using **HTML, CSS, and JavaScript**. Play the classic sliding-tile puzzle manually or solve it automatically using AI search algorithms.

Explore how **A\*** and **IDA\*** work, compare their performance, and visualize optimal solutions step by step.

## Features

- **Two Puzzle Sizes:** 3×3 (8-puzzle) and 4×4 (15-puzzle).
- **Manual Gameplay:** Move tiles using mouse clicks or keyboard controls.
- **Automatic Solver:** Solve puzzles using A* and IDA* algorithms.
- **Heuristic Functions:** Manhattan Distance and Linear Conflict.
- **Solution Playback:** Play, pause, reset, and navigate through solutions.
- **Algorithm Comparison:** Compare solution length, execution time, and search statistics.
- **Custom Puzzles:** Create and solve your own configurations.
- **Puzzle Validation:** Detect unsolvable configurations.
- **Additional Features:** Dark/light themes, puzzle history, adjustable difficulty, and built-in self-tests.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling and responsive design |
| JavaScript | Application logic |
| A* and IDA* | Search algorithms |
| Binary Min-Heap | Priority queue |
| Web Workers | Background computation |

## Getting Started

No installation or external dependencies required.

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

2. Open the project folder.
3. Run `index.html` in your browser.
4. Start solving puzzles!

## Algorithm Overview

- **A* Search:** Uses `f(n) = g(n) + h(n)` to find an optimal solution.
- **IDA* Search:** Uses iterative deepening with heuristic cost thresholds to reduce memory consumption.
- **Manhattan Distance:** Estimates the distance of tiles from their goal positions.
- **Linear Conflict:** Improves heuristic estimation by identifying conflicting tiles.

## Testing

The application includes built-in self-tests covering:
- Puzzle solvability.
- Heuristic calculations.
- Optimal solution verification.
- A* and IDA* performance and solution agreement.

Use the **Run Self-Tests** button in the application.

## Project Structure

```text
Slide-N-Puzzle-Solver/
├── index.html
└── README.md
```

The entire application is currently contained in a single HTML file, including its CSS and JavaScript.

## Future Improvements

- Additional search algorithms and heuristics.
- Advanced performance visualizations.
- Persistent puzzle history.
- Support for larger puzzle sizes.



