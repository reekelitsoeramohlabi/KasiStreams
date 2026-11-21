# KasiStream Web Streaming Platform

## Folder Structure
- `index.html`: Home / Discover page, Hero Banner, Featured Rows, Demo Sign-In Modal, and Fetch API / JSON updates.
- `movies.html`: Full 12-title Catalogue with real-time search and Genre/Type filters.
- `watchlist.html`: Persistent "My List" powered by `localStorage`.
- `about.html`: Project overview, FAQ accordion, and validated Support/Contact form.
- `css/style.css`: Custom dark/amber theme, CSS Grid/Flexbox cards, hover animations, and responsive media queries.
- `js/app.js`: Dynamic rendering engine, `localStorage` persistence, search/filtering, modal video player, and form validation.
- `data/featured-news.json`: Local JSON feed loaded asynchronously via `fetch()`.
- `assets/posters/`: Place `poster1.jpg` through `poster12.jpg` here (auto-generates SVG fallback posters if missing).
- `assets/movies/`: Place `sample-trailer.mp4` here (auto-falls back to open sample MP4 streams if missing).

## How to Run in Visual Studio Code
1. Extract this ZIP archive and open the `KasiStream` folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and click **Open with Live Server**.
