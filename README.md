# Ghita's 40th — Castle Shortlist

A single-page dashboard comparing UK castle venues for a 40th-birthday dinner
(40 guests, any week in October). Filterable by venue type and country
(England/Scotland), sortable by price per head or distance from London.

## Files

- `index.html` — the whole dashboard. Self-contained (styles and script
  inline), so it needs no build step.

## Publishing with GitHub Pages

1. Push this repo's `main` branch with `index.html` at the root.
2. In the repo on GitHub: **Settings → Pages → Build and deployment → Source:
   Deploy from a branch → Branch: `main`, folder `/ (root)` → Save**.
3. GitHub publishes it at `https://kapetanios55.github.io/GhitasBirthday/`
   within a minute or two of the push. Every future push to `main` republishes
   automatically — no extra step needed.

## Updating the dashboard

Edit `index.html` directly (venue data lives in the `venues` array near the
bottom of the file, in a `<script>` tag) and push again.
