# Jonathan Ran — Personal Site

Source for **[jonathanran.com](https://jran21.github.io/Website/)** *(or wherever GitHub Pages serves this)* — the personal portfolio of **Jonathan Ran**, Business Intelligence Analyst at Principal Financial Group and COO / Co-Founder of [Neobotics Foundation Inc.](https://neobotics.org)

Single-page editorial-style site covering bio, work, education, and contact.

---

## Stack

- **Single-file HTML** — everything (markup, CSS, JS) lives in `index.html`
- **No build step**, no framework, no dependencies
- **Vanilla JS** for scroll effects, cursor, reveal animations, and clipboard copy
- **Google Fonts**: Fraunces (serif), Instrument Sans (sans), JetBrains Mono (mono)
- **Mobile-first** — breakpoints at 1024 / 768 / 480px

## Deployment

Pushes to `main` auto-deploy via **GitHub Pages**. No CI, no build — the HTML is served as-is.

## Running Locally

Open `index.html` directly in a browser, or serve it:

```bash
# Python
python -m http.server 8000

# Node (if installed)
npx serve .
```

Then visit `http://localhost:8000`.

## Structure

```
.
├── index.html      ← entire site (HTML + CSS + JS inline)
├── headshot.jpg    ← hero portrait
├── bu-logo.webp    ← Boston University logo (Education section)
└── README.md
```

## Editing Notes

- All style and behavior changes go in `index.html` — there are no separate `.css` / `.js` files by design.
- Anchor sections: `#about`, `#experience`, `#education`, `#contact`.
- Keep edits **mobile-first** — test narrow viewports before committing.

## Contact

- **Email**: jmr@neobotics.org
- **Phone**: (610) 606-1536

---

© Jonathan Ran · Built with intention.
