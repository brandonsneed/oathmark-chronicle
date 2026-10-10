# The Oathmark Chronicle

A record of an ongoing Oathmark campaign — the battles fought, the kingdoms involved, and the regions contested. Hosted via GitHub Pages as a plain static HTML/CSS site.

## Structure

- `index.html` — the timeline (chronicle home), battles grouped by Regnal Year and season
- `battles/` — one page per battle, in the fixed Narrative / Technical / Aftermath layout
- `kingdoms/` — one page per kingdom (stubs for now)
- `regions/` — region/map detail (stub for now)
- `css/style.css` — shared stylesheet
- `CONTENT_STYLE_GUIDE.md` — the writing rules for battle entries (voice, structure, naming conventions)

## Adding a new battle

1. Draft the battle with the author against `CONTENT_STYLE_GUIDE.md`.
2. Copy an existing file in `battles/` as a template (header, two-column `battle-body`, `aftermath` section).
3. Add an entry to the relevant Regnal Year block in `index.html` (create a new `year-block` if it's a new year).
4. Add a "Battles of Record" link on each involved kingdom's page in `kingdoms/`.
5. Update the `battle-nav` prev/next links on the new page and the one before it.

## Publishing

GitHub Pages: Settings → Pages → Deploy from branch `main`, root (`/`).
