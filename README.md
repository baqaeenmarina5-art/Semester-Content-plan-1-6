# English Language Curriculum Toolkit — Hmood Primary Mixed School

Prepared by **Teacher Marina Al-Baqaeen** · Grades 1–6 · First Semester

A two-page, offline-first web tool:

- **`index.html`** — the cover / home page: school name, teacher credit, and
  quick links into either module, per grade.
- **`toolkit.html`** — the working tool itself, with two switchable modules:
  - **Content Analysis** — Pronunciation, Attitudes & Values, Functions,
    Structures, Vocabulary/Terms, Topics & Themes, per unit.
  - **Term Plan** — duration, pages (SB/AB), number of classes, outcomes,
    lesson numbers, and the shared Reflection/Activities/Assessment/
    Instructional Strategies/Resources block per grade — laid out as the
    same table structure as the original semester-plan documents.

Every field is editable in the browser, and any grade (or all six at once)
can be downloaded as a fully editable Word (`.doc`) file — table formatting
included — generated entirely client-side. No server, no external service,
no dependencies.

## Running it

Open `index.html` in any browser. No build step, no install, works offline.

## Hosting on GitHub Pages

1. Push this repo to GitHub (see commands below).
2. In the repo, go to **Settings → Pages**, set the source to the `main`
   branch, root folder.
3. The site goes live at `https://<your-username>.github.io/<repo-name>/`.

```bash
git init
git add index.html toolkit.html README.md
git commit -m "Add curriculum planning toolkit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO-NAME.git
git push -u origin main
```

## Editing the built-in data

The starting content for every grade lives in two JavaScript arrays near
the top of `toolkit.html`'s `<script>` block:

- `ORIGINAL_DATA_CA` — Content Analysis source data.
- `ORIGINAL_DATA_TP` — Term Plan source data.

Edit these directly to correct or extend the dataset (e.g. add a
second-semester block). Anything a teacher edits only in the browser is
*not* saved between sessions — download the Word file to keep it.

## License

Internal teaching-team resource — adapt freely for classroom/school use.
