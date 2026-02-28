# NBA Height × Weight Heatmap · 1947–2026

An interactive animated heatmap visualizing the height and weight distribution of every NBA player across 80 seasons.

## Features

- **Animated playback** through every NBA season from 1947 to 2026 with smooth interpolated transitions
- **Normalized heatmap** — each season's grid is scaled to its own peak density, making sparse early seasons and dense modern ones visually comparable
- **Hover tooltips** listing every player in a given height/weight cell for the current season
- **Live stats** — active player count, average height, average weight, and era name update each season
- **Keyboard controls** — Space to play/pause, arrow keys to step through seasons
- **Speed controls** — 1×, 2×, 4×, 16× playback
- Self-contained single HTML file, no dependencies, no build step

## Data

Player data sourced from [Basketball-Reference.com](https://www.basketball-reference.com/). Each player's career is expanded year-by-year (a player active 1990–2005 contributes one entry per season). Height bins are 1 inch, weight bins are 5 lbs.

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch**, select `main` / `root`
4. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Local

Just open `index.html` in a browser. That's it.

## License

Data from Basketball-Reference.com. Visualization code is MIT.
