# Gamer Bingo

Gamer Bingo is a fun, interactive bingo game designed for gamers. This project was created by [islandjon](https://github.com/islandjon).

Repository: [https://github.com/islandjon/gamer-bingo](https://github.com/islandjon/gamer-bingo)

## Features

- **Randomized Board:** Each new game shuffles phrases and places a "FREE" cell in the center.
- **Interactive Cells:** Click on any cell to mark it. The FREE cell is pre-marked.
- **Bingo Detection:** Automatically detects complete rows, columns, or diagonals.
- **Confetti Celebration:** Uses the [canvas-confetti](https://www.npmjs.com/package/canvas-confetti) library to display a confetti animation upon achieving Bingo.
- **URL Sharing:** The board state is encoded in the URL so you can share a specific bingo card.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## How to Use

1. **Open the Game:**
   - Simply open the HTML file (`index.html`) in your browser.

2. **Play the Game:**
   - Click on the cells to mark them.
   - When you complete a row, column, or diagonal, the game will display a "BINGO!" overlay with confetti.

3. **New Card and Printing:**
   - Click the **"New Card"** button to generate a new randomized board.
   - Use the **"Print"** button if you wish to print your bingo card.

4. **Sharing the Board:**
   - Click the **"Copy ID"** button to copy the current page URL (which includes the board state) to share with friends.

## Customization

- **Phrases:**
  - Modify the `phrases` array in the `<script>` section to change or add new phrases.
- **Styling:**
  - Adjust the CSS styles in the `<style>` section to change the appearance of the board, buttons, and messages.
- **Confetti Effect:**
  - The confetti settings (e.g., particle count, velocity) can be adjusted in the `showBingo()` function within the JavaScript code.

## Dependencies

- [canvas-confetti](https://www.npmjs.com/package/canvas-confetti) – Included via CDN.

## License

This project is open-source. Feel free to modify and distribute it as needed.
