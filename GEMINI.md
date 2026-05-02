# Snake Game - Project Instructions

## Project Overview
This project is a classic Snake game implemented in Python using the `pygame` library. The game includes features such as:
- Real-time snake movement controlled by arrow keys.
- Randomized food spawning.
- Score tracking and display.
- Collision detection with boundaries and the snake's own body.
- A game-over screen with options to restart or quit.

### Tech Stack
- **Language**: Python 3.x
- **Library**: Pygame

---

## Building and Running

### Prerequisites
Ensure you have Python 3 installed on your system.

### Installation
Install the necessary dependencies using pip:
```bash
pip install -r requirements.txt
```
*Alternatively, you can install Pygame directly:*
```bash
pip install pygame
```

### Running the Game
Execute the main script to start the game:
```bash
python snake.py
```

---

## Development Conventions

### Project Structure
- `snake.py`: Contains the entire game logic, including initialization, game loop, and event handling.
- `requirements.txt`: Lists the external dependencies.
- `README.md`: Provides basic user documentation.

### Coding Style
- **Configuration**: Constants for colors, screen dimensions (`600x400`), and game parameters (`BLOCK_SIZE`, `SNAKE_SPEED`) are defined at the top of `snake.py`.
- **Logic**: The core logic is encapsulated within the `gameLoop()` function.
- **Rendering**: Uses standard Pygame surface operations (`fill`, `blit`, `draw.rect`).
- **Fonts**: Relies on system fonts (`bahnschrift` and `comicsansms`). If these are not available, Pygame will fallback to default fonts.

### Future Improvements (Todo)
- [ ] Add a high-score persistence feature (e.g., saving to a file).
- [ ] Implement sound effects for eating and game over.
- [ ] Create a main menu screen.
- [ ] Refactor logic into classes (e.g., `Snake`, `Food`, `Game`) for better maintainability.
