# Double Feature

A PIN-locked movie, show, and event log for two. Built as a single `index.html` — deploy straight to GitHub Pages.

## Features

- **PIN lock** — each person gets their own PIN and welcome screen
- **TMDB integration** — search any film or show, poster + director + cast + genres autofill
- **Events** — add plays, concerts, etc. with manual details and image
- **Dual ratings** — separate star ratings and notes for each person
- **⚡ Disagreement badge** — appears when ratings differ by 2+ stars
- **Edit later** — each person can add/update their own rating anytime
- **Sort & filter** — by top rated, most recent, or genre
- **Polaroid corkboard** — push pins, film grain, CRT scanlines, the works

## Setup

1. Clone this repo
2. Get a free [TMDB API key](https://www.themoviedb.org/settings/api)
3. Open `index.html` and replace the `TMDB_KEY` value at the top of the `<script>` block with your key
4. Push to GitHub Pages — done

## PINs

Set your PINs by editing the `PINS` object in the script:

```js
const PINS = { '0511': 'Adya', '1206': 'Vishak' };
```

## Stack

Vanilla HTML/CSS/JS. No frameworks, no build tools, no dependencies. Data is stored in `localStorage`.

## Credits

Poster data from [TMDB](https://www.themoviedb.org/). This product uses the TMDB API but is not endorsed or certified by TMDB.
