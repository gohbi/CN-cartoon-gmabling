# CN Cartoon Games 🎮

A web-based games site featuring cartoon-themed games built with HTML5 Canvas and modern web technologies. This is a learning project to explore 2D and 3D animated game development for the web.

## Features

- **Responsive Design**: Works on desktop and mobile devices
- **Multiple Games**: Three fully playable games with animations
- **HTML5 Canvas**: All games use 2D canvas rendering for smooth animations
- **Modern UI**: Clean, colorful interface with gradient backgrounds

## Available Games

### 🎰 Cartoon Slots
A classic slot machine game with animated reels. Match 3 symbols to win!
- Each spin costs 10 credits
- Match 3 symbols to win 50 credits
- Features smooth reel animations

### 🎲 Dice Roll
Roll two dice and bet on the outcome!
- Bet on Even/Odd or High/Low
- Animated dice with rotation effects
- Win 30 credits on successful bets

### 🎯 Spinner Game
Spin a colorful wheel to win prizes!
- Prize values range from 0 to 100 credits
- Smooth spinning animation with deceleration
- Visual pointer shows your prize

## How to Run

1. Clone the repository
2. Open `index.html` in a web browser, or
3. Run a local server:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Project Structure

```
.
├── index.html          # Main landing page with game list
├── styles.css          # Global styles for the site
└── games/
    ├── slots.html      # Slot machine game
    ├── dice.html       # Dice rolling game
    └── spinner.html    # Wheel spinner game
```

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Gradients, Animations)
- JavaScript (Canvas API, RequestAnimationFrame)
- No external dependencies or frameworks

## Learning Goals

This project demonstrates:
- 2D graphics rendering with HTML5 Canvas
- Animation techniques using requestAnimationFrame
- Game state management
- Responsive web design
- Interactive UI components

## Future Enhancements

- Memory Match game (Coming Soon)
- Sound effects and music
- High score persistence with LocalStorage
- More game varieties
- 3D game implementations using WebGL

## License

See LICENSE file for details.
