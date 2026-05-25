# Dance Combat Lab — iPhone Version

Web-based side-scrolling beat combat game, optimized for **iPhone 12 and earlier** (375–390px screens).

## Play

Open `index.html` in a browser, or deploy to any static host (GitHub Pages, Netlify, Vercel).

**iOS tip:** Add to Home Screen → tap icon → plays full-screen with no browser chrome.

## Controls

| Button | Action |
|--------|--------|
| PARRY  | Tap before enemy flashes to counter |
| BLOCK  | Hold to absorb + stagger enemy (costs 3 HP) |
| LIGHT  | Fast combo hit (Z) |
| HEAVY  | Slow hard hit (X) |
| FIN    | Finisher — ends combo for big damage (F) |

## Levels & BPM Ramp

| Level | BPM | Mechanic |
|-------|-----|----------|
| 1 – Pulse   | 36 | Wide parry window, learn the feel |
| 2 – On-Beat | 45 | Parry on-beat = 1.5× damage |
| 3 – Rhythm  | 54 | Half-beat attacks |
| 4 – Phrase  | 63 | 4-beat bar reading |
| 5 – Flow    | 72 | Dense. Trust the groove. |

## Relationship to Python Version

- **iPhone version** = this repo (web, touch controls, Canvas 2D)
- **Python version** = [dance-combat-lab](https://github.com/michaelnocito/dance-combat-lab) (pygame desktop)

Both share the same BPM ramp, level structure, color palette, and game mechanics. Changes to one should be mirrored in the other.

## Deploy to GitHub Pages

1. Go to repo **Settings → Pages**
2. Source: `main` branch, `/ (root)`
3. Your game is live at `https://michaelnocito.github.io/dance-combat-iphone/`
