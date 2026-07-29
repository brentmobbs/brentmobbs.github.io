# brentmobbs.github.io

Brent D. Mobbs Website — a single static page (`index.html` + `styles.css`) with
anchor navigation between sections. No build step, no JavaScript, no Jekyll:
GitHub Pages serves the files as-is, and `.nojekyll` keeps it that way.

## Editing

- **Content and structure** — `index.html`
- **Design** — `styles.css`. Colours, spacing, and type are CSS custom properties
  in the `:root` block at the top of the file.
- **Fonts** — `assets/fonts/`, self-hosted so nothing is requested from a third
  party. Newsreader and Inter, both under the SIL Open Font License; the licences
  sit alongside the font files.

## Adding an article

1. Drop the file — PDF or anything else — into `articles/`.
2. Copy one of the `<li class="article">` blocks in the Articles section of
   `index.html` and edit it. The comment above that list explains each field.

An entry can link to the hosted file, out to wherever it was originally
published, or both.
