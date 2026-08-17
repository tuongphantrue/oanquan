# Ô Ăn Quan

A lightweight browser version of **Ô Ăn Quan (Mandarin Square Capturing)**, a traditional Vietnamese board game.

Built specifically to work well on **Kindle Paperwhite 10th Gen** and other simple E-Ink browsers.

## Play

https://tuongphantrue.github.io/o-an-quan/

## Features

- Play vs Computer
- 2-player mode
- Easy / Normal / Hard AI
- Undo
- Clockwise and counter-clockwise moves
- Pebbles are shown visually instead of as numbers
- Large Mandarin stones
- Black-and-white / grayscale interface
- Large touch targets for Kindle
- No animations
- No external libraries
- No server or API required
- Works entirely in the browser

## Kindle Friendly

The game uses only:

- HTML
- CSS
- old-style JavaScript

It does **not** require React, WebAssembly, Canvas, Node.js, or a backend.

This makes it suitable for the older browser on a Kindle Paperwhite.

## How to Play

You control the five pits on the **bottom** side of the board.

1. Tap one of your non-empty pits.
2. Choose **CLOCKWISE** or **COUNTER-CLOCKWISE**.
3. The pebbles are distributed one by one around the board.
4. If the next small pit contains pebbles, those pebbles are picked up and sowing continues.
5. If sowing stops before an empty pit, you may capture the stones in the following pit.
6. A **Quan** piece is worth 10 points.
7. The game ends after both Quan pieces have been captured.
8. The player with the highest score wins.

> Ô Ăn Quan has several regional and household rule variations.  
> This project uses a simple common-rule variant designed for easy browser play.

## GitHub Pages

To host your own copy:

1. Upload the project files to a public GitHub repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose your default branch (`main` or `master`).
5. Choose **/(root)**.
6. Save.

Your game will then be available at:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## Project Files

```text
o-an-quan/
├── index.html
├── README.md
├── LICENSE
└── .nojekyll
```

## License

MIT License.

This implementation was created as a lightweight web version of the traditional Vietnamese game **Ô Ăn Quan**.
