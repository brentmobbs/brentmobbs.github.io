# brentmobbs.github.io

Brent D. Mobbs Website — a single static page (`index.html` + `styles.css`) with
anchor navigation between sections. No build step, no Jekyll, and no JavaScript
beyond a one-line copyright-year updater. Deployed by GitHub Actions
(`.github/workflows/deploy-pages.yml`) on every push to `master`.

## Editing

- **Content and structure** — `index.html`
- **Design** — `styles.css`. Colours, spacing, and type are CSS custom properties
  in the `:root` block at the top of the file.
- **Fonts** — `assets/fonts/`, self-hosted so nothing is requested from a third
  party. Newsreader and Inter, both under the SIL Open Font License; the licences
  sit alongside the font files.

## Adding an article or project

1. Drop the file — PDF or anything else — into `articles/` (optional).
2. Copy one of the `<li class="article">` blocks in the Articles or Projects
   section of `index.html` and edit it. The comment above the Articles list
   explains each field.

Entry titles link to copies hosted on this site — HTML pages or PDFs under
`articles/` — while each "Read at ..." link points to the original publication.
The article pages reuse `/styles.css` (the `.article-head` and `.prose` styles),
so a new one is easiest to start by copying an existing page in `articles/`.
