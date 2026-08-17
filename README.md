# Ô Ăn Quan

A lightweight browser version of **Ô Ăn Quan (Mandarin Square Capturing)**, a traditional Vietnamese board game.

Built specifically to work well on **Kindle Paperwhite 10th Gen** and other simple E-Ink browsers.

## Repository

https://github.com/tuongphantrue/oanquan

## Play

https://tuongphantrue.github.io/oanquan/

## Features

- Play vs Computer
- 2-player mode
- Easy / Normal / Hard AI
- Undo
- Clockwise and counter-clockwise moves
- Pebbles are shown visually instead of as numbers
- Moving hand animation that travels pit to pit
- The hand picks up stones and drops them one by one
- 2 seconds for each dropped pebble
- Black-and-white / grayscale interface
- Large touch targets for Kindle
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
3. The hand picks up the pebbles from that pit.
4. The hand moves around the board and drops one pebble into each pit.
5. Each dropped pebble is shown for 2 seconds so the move is easy to follow.
6. If the next small pit contains pebbles, those pebbles are picked up and sowing continues.
7. If sowing stops before an empty pit, you may capture the stones in the following pit.
8. A **Quan** piece is worth 10 points.
9. The game ends after both Quan pieces have been captured.
10. The player with the highest score wins.

> Ô Ăn Quan has several regional and household rule variations.  
> This project uses a simple common-rule variant designed for easy browser play.

## GitHub Pages

This repository is intended to be published with GitHub Pages.

Go to:

**Settings → Pages → Deploy from a branch**

Choose:

```text
Branch: main
Folder: / (root)
