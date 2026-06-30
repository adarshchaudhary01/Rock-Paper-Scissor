# Rock Paper Scissors

A simple browser-based Rock Paper Scissors game. Click an icon to play a round against the computer — scores update automatically and keep counting until you refresh the page.

## How to Play

1. Open `rock.html` in your browser.
2. Click on Rock, Paper, or Scissors.
3. The computer makes its choice and the result is calculated instantly.
4. Scores update on the scoreboard — keep clicking to keep playing.

## Project Structure

```
RockPaperScissor/
├── rock.html        # Main HTML file / game structure
├── paper.css         # Styling
├── scissor.js        # Game logic
└── Images/
    ├── rock.png
    ├── paper.png
    └── scissors.png
```

## Features

- Click-to-play interface — no typing required
- Live scoreboard tracking "You" vs "Comp"
- Score persists across rounds until the page is refreshed

## Built With

- HTML
- CSS
- JavaScript

## Getting Started

No build steps or dependencies needed. Just clone or download the project and open `rock.html` in any modern browser.

```bash
git clone <your-repo-url>
cd RockPaperScissor
open rock.html
```

## Future Improvements

Some ideas to extend the game:
- Add keyboard support for selecting a choice
- Add a "best of N" mode instead of indefinite scoring
- Add a reset button to clear scores without refreshing
- Add sound effects or win/lose animations

## License

This project is open source and available for personal or educational use.
