# Pong Arcade

A browser-based classic ping pong game. Single HTML file, zero dependencies.

## What we're building

- 800x500 canvas
- Player paddle (left side, keyboard controlled: W/S or Arrow Up/Down)
- AI paddle (right side, follows ball with slight delay for beatable difficulty)
- Ball with velocity, angle changes on paddle hit
- Score display (first to 7 wins)
- Start screen, playing state, game over screen with "Play Again"
- Retro aesthetic: black background, white paddles and ball, dotted center line
- No external libraries. No build tools. One index.html file.

## Tech

- Vanilla JavaScript
- HTML5 Canvas API
- requestAnimationFrame game loop
- All code in a single index.html file

## Constraints

- No em dashes in comments or text
- Keep code clean and well-commented
- Game must be playable on desktop browsers (Chrome, Firefox, Safari)
- Canvas must be centered on the page with a dark background behind it