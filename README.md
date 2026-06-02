# Vedran Balagović — Portfolio / CV

A clean, mobile-responsive one-page portfolio. Plain HTML + CSS, no build step.

**Live:** https://vbalagovic.github.io/

## Files
- `index.html` — the site
- `style.css` — styles
- `profile.jpg` — profile photo (swap this file to change the photo)
- `cv-print.html` — printable CV (open in a browser → ⌘P → Save as PDF)
- `CV.md` — CV source in Markdown
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Edit
Just edit `index.html` / `style.css` and refresh the browser. To preview locally:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy (GitHub Pages, free)
Already configured to publish from the `main` branch root. After pushing:

```bash
git add -A && git commit -m "Update portfolio" && git push
```

GitHub Pages rebuilds automatically. Manage it at **Settings → Pages**.

---
Contact: vedran@knittedlogic.com
