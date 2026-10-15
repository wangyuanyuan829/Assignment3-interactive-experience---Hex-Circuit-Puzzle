# Hex Circuit Puzzle
Assignment 3: An interactive experience

## Project Introduction
This is a simple web-based hexagonal circuit puzzle.
Target users: casual puzzle players who enjoy rotation and path-building games.
Core interaction: Click hexagonal pipe tiles to rotate pipe segments, connecting the power source to all three light bulbs.
Each click immediately updates the pipe graphics. When the full circuit is connected, all bulbs light up with success feedback, forming a complete input-response-feedback loop.

## How to Run
1. Clone or download this repository to your local machine.
2. Open `index.html` in Chrome or Edge browser.
3. Click hexagonal pipe tiles to rotate pipelines and connect power to bulbs.
4. Click the Reset Puzzle button to restart the puzzle.

## Game Instructions
- ✅ Click hexagonal tiles with pipes to rotate the circuit path
- 🔒 Bulb and power source tiles are fixed and cannot be rotated
- 🎯 Goal: Connect the power source to all three bulbs to win

## Screenshot
![Game screenshot](screenshot.png)

## Known Limitations
1. Browser audio autoplay restriction: audio will only trigger after the first mouse click.
2. This puzzle uses a small fixed grid. Larger hex grids will increase computational cost for connectivity detection.
3. Optimised mainly for desktop mouse interaction.

## Credits
Built with vanilla HTML, CSS and JavaScript.
Based on web examples from course materials. Extended with hex tile rotation, click feedback and win condition detection.
Assets are created for educational assignment use only.
