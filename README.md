
---

# 2048 — Vanilla JavaScript Game

A fully functional implementation of the classic 2048 puzzle game.
The project focuses on clean architecture, modularity, grid-based logic, animations, and responsive UI — all written in pure JavaScript without frameworks.

---

## Live Preview

- [DEMO LINK](https://alex-redman.github.io/js_2048_game/)

---

## Design Reference

[Original game for comparison:](https://play2048.co/)

---

## Technologies Used

* JavaScript (ES6+)
* HTML5
* SCSS
* Module-based architecture
* CSS Grid for layout
* Basic animations & transitions

---

## Project Structure

```
src/
│   index.html
│
├───images
│       .gitkeep
│       reference.png
│
├───modules
│       Game.class.js
│
├───scripts
│       main.js
│
└───styles
        main.scss
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Install dependencies

```bash
npm install
```

### Run the project locally

If you have a dev server configured:

```bash
npm start
```

If not — simply open `index.html` in your browser.

---

## Features

* Fully working 2048 mechanics:
  * movement in 4 directions
  * merging logic
  * new tile spawning
  * game-over detection
* Adaptive UI
* Keyboard controls
* Smooth tile animations
* Clean and readable code structure
* Separate game logic class (Game.class.js)

---

## Notes About the Code

* The core game logic is fully isolated inside the Game.class.js module — this makes the project easy to extend or refactor.
* main.js handles initialization, event listeners, and communication between the UI and the game engine.
* main.scss contains all styles and can be easily scaled as you add new features.
* Image assets are stored inside the /images folder.

---

## Deployment Tips

* GitHub Pages works perfectly with this project — just ensure the index.html file is in the deployment root.
* Make sure:
  * all asset paths are relative (no leading /)
  * compiled CSS is included if you are using Sass
  * you deploy the final src structure properly

---

## README Checklist

* [x] Correct project title
* [x] Clear description
* [x] Working live demo
* [x] Tech stack
* [x] Setup instructions
* [x] Clean folder structure
* [x] No unnecessary files

---

