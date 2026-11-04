# ankitgupta.me

Ankit Gupta's personal site: essays, interests and a press kit.

It's one static page (`index.html`) with no build step. Pages switch by the `#` part of the URL (`#essays`, `#about`, ...).

## Adding an essay

1. In `index.html`, add an entry to the `ESSAYS` list near the bottom (newest first): `slug`, `title`, `section` (`general`, `books` or `food`), `minutes`, `summary`.
2. Copy the `<section class="view" data-view="problem-solving">` block, change `data-view` to the new slug, and paste in the essay text.

## Hosting

Served by GitHub Pages from the `main` branch. The `CNAME` file sets the custom domain to ankitgupta.me. DNS: four A records on the root domain (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a CNAME record for `www` pointing to `gankit.github.io`.
