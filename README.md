# erenciracioglu-dotcom.github.io

Index page for my browser projects: **https://erenciracioglu-dotcom.github.io/**

English by default, Turkish with the flag at the top. Each card has a screenshot, a short description (EN / TR), a link to the live page and a link to the source.

## Adding a project

1. Add an entry to `projects.json` (`repo`, `title`, `tags`, `tr`, `en`).
2. Put a 16:10 screenshot at `thumbs/<repo in lower case>.webp` (960×600 works well).

## Adding a music video

Add `{ "id": "<YouTube video id>" }` to `videos.json`. The thumbnail and title come from YouTube; add a `"title"` to override the title.

## Tags

Project tags: `game`, `music`, `sim`, `art`, `4d`, `map`, `other`.

If a repo gets GitHub Pages but has no entry yet, the page lists it anyway, marked "New", with its GitHub description and its `screenshot.png`. Adding it to `projects.json` gives it a proper description and thumbnail.
