# Life Alignment Questionnaire

A single-file, static HTML questionnaire for couples (or individuals) to work
through life-alignment questions together — partner A / partner B columns,
per-question rating and notes, English/Greek i18n toggle, light/dark theme
toggle, and a results export modal (copy/download summary).

Everything (markup, CSS, and JS) lives in `index.html`. There is no build
step and no external dependencies.

## Running it

Just open `index.html` directly in a browser, or serve the folder with any
static file host, e.g.:

```
npx serve .
```

or

```
python3 -m http.server
```

Netlify/deployment is handled separately by Ninos — this folder only needs a
static host pointed at `index.html`.
