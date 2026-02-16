<div align="center">

# Paw Catch

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Canvas API](https://img.shields.io/badge/Canvas_API-FF6B6B?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://alfredang.github.io/paw-game/)

**A fun reflex-testing game where you catch a bouncing paw before it escapes!**

[Play Now](https://alfredang.github.io/paw-game/) · [Report Bug](https://github.com/alfredang/paw-game/issues) · [Request Feature](https://github.com/alfredang/paw-game/issues)

</div>

## Screenshot

![Screenshot](screenshot.png)

## About

Paw Catch is an engaging browser-based clicking game where players test their reflexes by catching a bouncing paw on a starry night canvas. Each successful catch earns points and increases the paw's speed, creating an increasingly challenging experience. No dependencies, no build step — just pure HTML, CSS, and JavaScript.

### Features

- Click-to-catch gameplay with real-time score tracking
- Progressive difficulty — paw speeds up with every catch
- Hand-drawn paw rendered with the Canvas API
- Starry night background with a glowing canvas aesthetic
- Fully responsive and works in any modern browser

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Structure** | HTML5 |
| **Styling** | CSS3 (Flexbox, Gradients, Box Shadow) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Rendering** | Canvas API (`requestAnimationFrame`) |
| **Hosting** | GitHub Pages |

## Architecture

```
┌─────────────────────────────────┐
│           Browser               │
│  ┌───────────────────────────┐  │
│  │      index.html           │  │
│  │  ┌─────────┐ ┌─────────┐ │  │
│  │  │style.css│ │ game.js │ │  │
│  │  └─────────┘ └────┬────┘ │  │
│  │                    │      │  │
│  │         ┌──────────▼───┐  │  │
│  │         │  Canvas API  │  │  │
│  │         │  - Draw paw  │  │  │
│  │         │  - Stars BG  │  │  │
│  │         │  - Collision │  │  │
│  │         │  - Animation │  │  │
│  │         └──────────────┘  │  │
│  └───────────────────────────┘  │
└─────────────────────────────────┘
```

## Project Structure

```
paw-game/
├── index.html       # Game page and canvas element
├── style.css        # Dark theme styling and layout
├── game.js          # Game loop, rendering, and input handling
├── screenshot.png   # App screenshot
└── README.md        # Project documentation
```

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)

### Run Locally

```bash
# Clone the repository
git clone https://github.com/alfredang/paw-game.git

# Open in browser
open paw-game/index.html
```

No build tools or dependencies required.

### How to Play

1. Open the game in your browser
2. Click anywhere on the canvas to start
3. Click the bouncing paw to score points
4. The paw speeds up with each catch — how high can you score?

## Deployment

The game is deployed on **GitHub Pages** and available at:

**https://alfredang.github.io/paw-game/**

To deploy your own fork:
1. Fork this repository
2. Go to **Settings** > **Pages**
3. Set source to **Deploy from a branch** > `main` > `/ (root)`
4. Your site will be live at `https://<your-username>.github.io/paw-game/`

## Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/awesome-feature`)
3. Commit your changes (`git commit -m 'Add awesome feature'`)
4. Push to the branch (`git push origin feature/awesome-feature`)
5. Open a Pull Request

## License

Distributed under the MIT License.

## Collaborator

- [Openclaw](https://github.com/openclaw)

## Acknowledgements

- Built with the [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- Hosted on [GitHub Pages](https://pages.github.com/)

---

<div align="center">

If you enjoyed this game, give it a star!

</div>
