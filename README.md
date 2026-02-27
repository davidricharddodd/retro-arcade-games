# 🕹️ Retro Arcade Games Collection

A collection of classic arcade games built with vanilla JavaScript, HTML5 Canvas, and CSS3. Play your favorite retro games right in your browser!

![Retro Arcade](https://img.shields.io/badge/Games-3-brightgreen)
![Browser](https://img.shields.io/badge/Platform-Browser-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🎮 Games Included

### 🔴🟡 Connect 4
Classic strategy game where you connect four pieces in a row to win!

**Features:**
- 👥 Player vs Player mode
- 🤖 Player vs AI mode with 3 difficulty levels
  - Easy: Random moves
  - Medium: Strategic positioning
  - Hard: Advanced threat evaluation
- 🔊 Sound effects (drop, win, error)
- ✨ Smooth drop animations
- 📱 Mobile responsive

### 🚀👾 Space Invaders
Defend Earth from waves of alien invaders!

**Features:**
- 👾 Classic alien formations
- 🎯 Player shooting mechanics
- 💥 Aliens shoot back!
- 📈 Progressive difficulty levels
- ❤️ Lives system
- 🏆 High score persistence (localStorage)
- 🔊 Retro sound effects
- ⏸️ Pause functionality

### 🟡👻 Pac-Man
Navigate the maze, eat dots, and avoid the ghosts!

**Features:**
- 🗺️ Classic maze layout
- 👻 4 unique ghosts (Blinky, Pinky, Inky, Clyde)
- ⚡ Power pellets to turn the tables
- 🎚️ Progressive levels
- ❤️ Lives system
- 📊 Score tracking
- 🔊 Sound effects (wakka, power-up, death)
- ⌨️ Smooth keyboard controls

## 🚀 Play Now

**[👉 Play Online Here!](https://davidricharddodd.github.io/retro-arcade-games/)**

## 💻 Local Setup

No build process needed! Just clone and play:

```bash
# Clone the repository
git clone https://github.com/davidricharddodd/retro-arcade-games.git

# Navigate to the directory
cd retro-arcade-games

# Open in your browser
open index.html
# or simply double-click index.html
```

## 🎯 Controls

### Connect 4
- **Mouse Click**: Drop piece in column

### Space Invaders
- **← →**: Move ship left/right
- **SPACE**: Shoot
- **P**: Pause

### Pac-Man
- **↑ ↓ ← →**: Move Pac-Man
- **P**: Pause

## 🛠️ Technical Stack

- **HTML5 Canvas**: For game rendering
- **Vanilla JavaScript**: Game logic (no frameworks!)
- **CSS3**: Styling and animations
- **Web Audio API**: Sound effects

## 🎨 Features

- ✅ 100% browser-based - no downloads required
- ✅ Retro pixel-perfect graphics
- ✅ Classic sound effects
- ✅ Keyboard controls
- ✅ Responsive design
- ✅ High score tracking
- ✅ Pause/resume functionality
- ✅ No external dependencies

## 🧠 AI Implementation

The Connect 4 AI uses a **rule-based decision tree** algorithm:

1. **Offensive**: Check for immediate winning moves
2. **Defensive**: Block opponent's winning moves
3. **Strategic**: 
   - Easy: Random valid moves
   - Medium: Center column preference
   - Hard: Position evaluation with threat counting

This is a traditional game-playing algorithm, not machine learning - ensuring instant response times and deterministic behavior.

## 📁 Project Structure

```
retro-arcade-games/
├── index.html              # Main menu/launcher
├── connect4.html           # Connect 4 game
├── space-invaders.html     # Space Invaders game
├── pacman.html            # Pac-Man game
└── README.md              # This file
```

## 🎯 Scoring

### Connect 4
- Win the game!

### Space Invaders
- Top row aliens: 30 points
- Middle row aliens: 20 points  
- Bottom row aliens: 10 points

### Pac-Man
- Small dots: 10 points
- Power pellets: 50 points
- Eating ghosts: 200 points each

## 🚧 Future Enhancements

- [ ] Add more classic games (Tetris, Snake, Breakout)
- [ ] Global leaderboard system
- [ ] Achievements/badges
- [ ] Mobile touch controls
- [ ] CRT screen effect toggle
- [ ] Game tutorials
- [ ] Two-player online mode

## 🤝 Contributing

Feel free to fork this project and add your own retro games! Pull requests are welcome.

## 📄 License

MIT License - feel free to use this code for learning or your own projects!

## 👨‍💻 Author

**David Dodd**
- GitHub: [@davidricharddodd](https://github.com/davidricharddodd)

## 🙏 Acknowledgments

Inspired by the golden age of arcade gaming! These implementations pay homage to the original classics while adding modern web features.

---

**Made with ❤️ and nostalgia**

🎮 Happy Gaming! 🎮
