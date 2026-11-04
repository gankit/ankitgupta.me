# ankitgupta.me

Ankit Gupta's personal site: essays, interests and a press kit.

It's one static page (`index.html`) with no build step. Pages switch by the `#` part of the URL (`#essays`, `#about`, ...).

## Adding an essay

1. In `index.html`, add an entry to the `ESSAYS` list near the bottom (newest first): `slug`, `title`, `section` (`general`, `books` or `food`), `minutes`, `summary`.
2. Copy the `<section class="view" data-view="problem-solving">` block, change `data-view` to the new slug, and paste in the essay text.

## Hosting

Served by GitHub Pages from the `main` branch. When the domain is bought, add a `CNAME` file containing `ankitgupta.me` and point the domain's DNS at GitHub Pages.
