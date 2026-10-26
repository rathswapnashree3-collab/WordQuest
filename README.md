# WordQuest

WordQuest is a cozy word search game made with HTML, CSS, and plain JavaScript. It runs in your browser and saves player progress on your device.

## Run the game

1. Keep `index.html`, `style.css`, `script.js`, and `word-meanings.js` together in the same folder.
2. Open `index.html` in a web browser.
3. Choose **Play a game** or **Daily game** on the Home screen.

No install or server is required. An internet connection lets the game load its optional Google Fonts; system fonts are used if they are unavailable.

## Files

- `index.html` contains the page structure and game interface, and loads the game scripts in order.
- `style.css` contains the cozy colors, playful fonts, layout, and light/dark themes.
- `script.js` handles gameplay, scores, hints, coins, achievements, and saved progress. `word-meanings.js` contains definitions for the expanded word banks and must stay beside the other game files.
- `assets/wordquest-hero.png` is the softly faded artwork used in the home screen banner.

## Game features

- Five themes with large word banks (about 100–200 words each); regular games rotate through unused words before repeating, with Easy, Medium, and Hard levels.
- Words hidden horizontally, vertically, diagonally, forwards, and backwards.
- Mouse and touch selection, two hints, word meanings after each find (tap a found word to see its meaning again), a timer, and pause, restart, and quit controls.
- Daily games, local scores, achievements, coins, and cosmetic shop items.
- Save multiple unfinished puzzles and resume or delete them later.
- Light and dark themes.

Use **Leaderboard → Scores** to see saved scores and **Leaderboard → My progress** to see your stats and achievements. Every word in the playable word banks has a word-specific meaning, shown when it is found.

## Saved progress

The game uses browser `localStorage` to save your player profile, coins, settings, achievements, purchases, completed games, and unfinished puzzles. This information stays in the current browser on the current device. Scores are not global or verified. Clearing browser data may erase your progress.

## Publish with GitHub Pages

You can upload these files to a GitHub repository, then enable GitHub Pages in the repository settings to share the game as a website. Each visitor’s progress will still be saved only in their own browser.

