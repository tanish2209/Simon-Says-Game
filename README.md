# 🎮 Simon Says Game

A browser-based implementation of the classic **Simon Says** memory game, built with vanilla HTML, CSS, and JavaScript.

## 📖 About

Simon Says is a memory skill game where the player must repeat a randomly generated sequence of colored button flashes. With each level, the sequence grows longer — how far can you go?

## 🚀 How to Play

1. Open `simon.html` in any modern web browser.
2. **Press any key** to start the game.
3. Watch the sequence of button flashes carefully.
4. Click the buttons in the **same order** as the flashed sequence.
5. Each correct round adds one more step to the sequence.
6. One wrong press and it's **Game Over** — your score is displayed and you can press any key to restart.

## 🗂️ Project Structure

```
├── simon.html   # Game layout and structure
├── simon.css    # Styling for buttons, layout, and flash animation
└── simon.js     # Game logic: sequence generation, input handling, scoring
```

## ⚙️ Features

- Randomly generated color sequences that grow with each level
- Visual flash feedback for both game and player button presses
- High score tracking within the session
- Game Over screen with red flash effect and final score display
- Instant restart on any keypress

## 🛠️ Built With

- **HTML5** — Page structure
- **CSS3** — Styling and flash animations
- **Vanilla JavaScript** — Game logic, DOM manipulation, event handling

## 🖥️ Running Locally

No installation or build step needed. Just clone or download the repo and open the HTML file:

```bash
git clone https://github.com/your-username/simon-says.git
cd simon-says
open simon.html   # or double-click the file in your file explorer
```

## 🔮 Possible Improvements

- Add sound effects for each button color
- Persist high score using `localStorage`
- Add difficulty levels (faster flash speed)
- Mobile touch support improvements
- Animated intro screen

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
