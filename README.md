> [!NOTE]
> I don't know what I want this to be, I built it and now want a place for it to sit publicly :/

# hacker-news-frontend

A lightweight, single-file Hacker News client built with vanilla JS and Tailwind CSS.

## Features

- Browse Top, New, Show, and Ask stories
- Search stories by title or author
- Paginate with the More button
- Refresh the current feed without losing your scroll position

## Live Demo

[View on GitHub Pages](https://4uffin.github.io/hacker-news-frontend)

## Usage

The app must be served over HTTP — opening the file directly in a browser will result in CORS errors from the HN API.

```
# Python
python -m http.server 8000

# Node
npx serve .
```

Then open `http://localhost:8000` in your browser.

## Data

All data is fetched live from the [Hacker News Firebase API](https://github.com/HackerNews/API). No backend, no dependencies, no build step.

## License

This project is under the [MIT License](LICENSE.txt).
