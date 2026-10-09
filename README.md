# Nirav Shah · Portfolio dashboard

A single-page, dashboard-style portfolio for recruiters and hiring managers. Plain HTML/CSS/JS, no build step.

## Files

- `index.html` – the whole site
- `resume.pdf` – **add this yourself** (the "Resume" button links to it)
- `.nojekyll` – tells GitHub Pages to serve files as-is

## Deploy to GitHub Pages (personal account)

1. Sign in to your **personal** GitHub account and create a new **public** repo named `<your-username>.github.io`.
2. Upload `index.html`, `.nojekyll` and `resume.pdf` (Add file → Upload files → Commit).
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. In a minute or two the site is live at `https://<your-username>.github.io`.

Or from a terminal:

```bash
git init && git add . && git commit -m "Portfolio dashboard"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

## Editing

- Headline numbers: the `.kpis` section in `index.html`.
- Charts and "Selected work" cards: the `BA`, `SK`, `TL` and `CASES` arrays in the `<script>` block.
- Update the footer's "last updated" date when you change things.

After it's live, add the URL to your LinkedIn and to the "Portfolio / Website" field on applications.
