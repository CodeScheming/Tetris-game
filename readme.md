# Pygame Tetris

A classic implementation of the beloved puzzle game Tetris, built from the ground up using Python and the Pygame library. This project provides a fully playable Tetris game with core features like tetromino movement, rotation, line clearing, scoring, and a "next piece" preview.

## 🕹️ Features

- **Classic Tetris Gameplay**: Experience the timeless gameplay of arranging falling tetrominoes to create and clear horizontal lines.
- **All Seven Tetrominoes**: All the iconic "I", "O", "T", "S", "Z", "J", and "L" blocks are included.
- **Scoring System**: Your score increases for every line you clear.
- **"Next Piece" Preview**: See which tetromino is coming next to plan your moves strategically.
- **Responsive Controls**: Smooth and intuitive controls for moving and rotating the pieces.
- **Simple & Clean UI**: A minimalist interface that keeps the focus on the gameplay.

## 🔧 Requirements

To run this game, you'll need to have Python and the Pygame library installed on your system.

- **Python 3.x**
- **Pygame**: A cross-platform set of Python modules designed for writing video games.

## 📦 Installation

1. **Clone the repository** (or download the code):

```bash
git clone https://github.com/CodeScheming/Tetris-game.git
cd Tetris game
```

Alternatively, you can just save the Python code into a file named `tetris.py`.

2. **Install Pygame**:

If you don't have Pygame installed, you can install it using pip:

```bash
pip install pygame
```

## 🎮 How to Play

1. **Run the game**:

Execute the Python script from your terminal:

```bash
python tetris.py
```

2. **Game Controls**:

- **Left Arrow Key**: Move the falling tetromino to the left.
- **Right Arrow Key**: Move the falling tetromino to the right.
- **Down Arrow Key**: Speed up the descent of the tetromino.
- **Up Arrow Key**: Rotate the tetromino clockwise.

The game ends when the blocks stack up to the top of the playing field. The objective is to score as many points as possible by clearing lines.

## 📂 Project Structure

```
pygame-tetris/
└── tetris.py    # The main and only Python script containing all the game logic, rendering, and asset definitions
```

## 🎯 Game Rules

- Tetrominoes fall from the top of the playing field
- Use arrow keys to move and rotate pieces
- Complete horizontal lines to clear them and score points
- Game ends when pieces reach the top of the field
- Aim for the highest score possible!

## 🚀 Future Enhancements

- [ ] Level progression with increasing speed
- [ ] High score persistence
- [ ] Sound effects and background music
- [ ] Ghost piece preview
- [ ] Hold piece functionality
- [ ] Particle effects for line clears

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/pygame-tetris/issues).

---

**Enjoy playing Tetris!** 🎮
