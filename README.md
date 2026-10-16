# Color Clash: Quick Card Battle

A colorful, browser-based card game where you compete against a computer opponent. Match cards by color or value, use special cards strategically, and try to empty your hand before the opponent does.

> **Project status:** Prototype. Test the game in your target browsers and review platform requirements before publishing it as a public release.

## Features

- **Single-player gameplay** against a computer-controlled opponent.
- **Color and value matching** with special action cards.
- **Wild cards** that let a player choose the next color.
- **Score tracking**, wins and losses, and win streaks.
- **Sound effects** and game feedback.
- **Interactive tutorial and rules panel** to help new players learn.
- **Responsive layout** designed for desktop and mobile screens.
- **Standalone HTML implementation** with CSS and JavaScript in one file.

## Play the Game

**Live demo:** Add your public game URL here after you deploy it.

For example, if you publish this repository with GitHub Pages, your link will usually look like:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Start a round and follow the on-screen instructions.

No build step or package installation is required for the standalone HTML version.

## How to Play

1. Play a card that matches the current card's color or value, when a valid move is available.
2. Use special cards strategically to affect the round.
3. Draw a card when you cannot make a valid play.
4. When you have one card left, use the in-game call button as instructed.
5. Empty your hand before the computer opponent to win the round.

The game includes an in-game tutorial and rules panel. Refer to those for the exact behavior of special cards and penalties.

## Technology

- HTML
- CSS
- JavaScript
- YouTube Playables SDK script integration (included in the current prototype; platform integration has not been certified)

## Project Structure

```text
.
├── index.html
└── README.md
```

## Publishing with GitHub Pages

1. Create a new public repository on GitHub.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under the build and deployment section, choose the branch containing your files and the root folder.
5. Save the settings and wait for GitHub Pages to publish the site.
6. Open the public URL and test the game on desktop and mobile.

GitHub Pages is useful for sharing a browser-playable demo. Hosting it there does **not** mean the game has been approved for YouTube Playables.

## YouTube Playables Readiness

The current HTML includes a YouTube Playables SDK script reference. This alone does not confirm that the game meets all Playables requirements. Before submitting, test the game in the official environment and verify the current SDK, lifecycle, save/load, audio, scoring, performance, and certification requirements.

## Intellectual Property

Before public release, review the game's title, rules presentation, visual design, card artwork, sounds, and all terminology for originality and rights clearance. The current prototype includes the term **“UNO”** in its interface/tutorial; replace it with original terminology and review the game's overall presentation before publishing. Do not use third-party trademarks, assets, music, or other protected material unless you have the necessary permission or licence.

## Contributions and Feedback

Suggestions, bug reports, and improvements are welcome. Please describe the issue clearly and include the browser/device where it occurred.

## License

No open-source license has been selected for this project yet. Unless a license is added, do not assume that others have permission to reuse, modify, or redistribute the code or assets.
