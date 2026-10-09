# Square Game

A simple interactive browser-based game built using HTML, CSS, and JavaScript. It contains four numbered boxes that respond to mouse hover and click events with random colors, changing numbers, and visual effects.

## Features

- Four interactive square boxes.
- Box 1 changes its background color on hover.
- Box 2 displays a random number and changes its background color on hover.
- Box 3 triggers changes in other boxes and applies a scaling effect.
- Box 4 triggers a multi-box interaction when clicked.
- Random RGB color generation.
- Random number generation.
- Automatic reset of the box content and colors after a short delay.
- CSS hover effects, transitions, and shadows.

## Technologies Used

- **HTML5** — Structure of the game.
- **CSS3** — Grid layout, styling, transitions, and hover effects.
- **JavaScript** — Event handling, random values, and dynamic DOM manipulation.

## How It Works

1. Hover over **Box 1** to change its background color.
2. Hover over **Box 2** to display a random number and change its color.
3. Hover over **Box 3** to change the content and colors of other boxes and apply a scaling effect.
4. Click **Box 4** to change the content and colors of all four boxes.
5. After 1.5 seconds, the boxes reset to their original numbers and white backgrounds.

## Project Structure

```text
square-game/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run Locally

1. Download or clone the repository.
2. Keep `index.html`, `style.css`, and `script.js` in the same folder.
3. Open `index.html` in your browser.
4. Interact with the boxes using your mouse.

No additional installation or build tools are required.

## Current Limitations

- The project is an interactive experiment rather than a complete game with scoring or levels.
- The random rotation function is defined, but its usage is currently commented out.
- Interactions are primarily designed for mouse events.

## Future Improvements

- Add a scoring system.
- Introduce multiple levels and challenges.
- Add sound effects and animations.
- Improve responsiveness for mobile screens.
- Add keyboard interaction and accessibility support.

## License

This project is created for learning and practice purposes. Add a formal license if you plan to distribute it publicly.