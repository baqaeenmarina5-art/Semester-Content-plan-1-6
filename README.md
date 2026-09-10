# Curriculum Planning Toolkit — Grades 1–6

A single-page, offline-first web tool for English-language curriculum planning in Jordan's "Team Together" first-semester materials.

## What it does

Two linked modules, switchable from tabs at the top:

- **Content Analysis** — per-grade, per-unit breakdown of Pronunciation, Attitudes & Values, Functions, Structures, Vocabulary/Terms, and Topics & Themes.
- **Term Plan** — per-grade, per-unit semester plan: duration, pages (SB/AB), number of classes, outcomes, lesson numbers, plus a shared Reflection / Activities / Assessment / Instructional Strategies / Resources template per grade.

All fields are editable directly in the browser. Every grade (and the full 1–6 set) can be downloaded as a fully editable Word (`.doc`) file — table formatting included — generated entirely client-side, no server or external service involved.

## Running it

Just open `index.html` in any browser — no build step, no dependencies, works offline.

### Hosting on GitHub Pages

1. Push this repo to GitHub (see commands below).
2. In the repo settings, go to **Settings → Pages**, set the source to the `main` branch, root folder.
3. Your tool will be live at `https://<your-username>.github.io/<repo-name>/`.

## Editing the built-in data

The starting content for every grade lives in two JavaScript arrays near the top of `index.html`'s `<script>` block:

- `ORIGINAL_DATA_CA` — Content Analysis source data.
- `ORIGINAL_DATA_TP` — Term Plan source data.

Edit these directly to correct or extend the built-in dataset (e.g. add a second-semester block); anything a teacher edits in the browser only, without touching this file, is *not* saved between sessions — download the Word file to keep it.

## License

Internal teaching-team resource — adapt freely for classroom/school use.
