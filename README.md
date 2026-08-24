# Kestrel Coffee — Demo Site

A three-page static website built as a test/template. Fictional business, placeholder content.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page — hero, services, review teaser, call-to-action |
| `about.html` | Description / about page — story, offerings, hours, FAQ |
| `reviews.html` | Reviews page — rating summary and review cards |
| `styles.css` | Shared stylesheet for all three pages |
| `script.js` | Mobile menu toggle + footer year |

No build step, no dependencies, no external requests. Every page is plain HTML/CSS/JS.

## Deploying to Vercel

1. Create a new repository on GitHub (leave it empty — no README).
2. On the empty repo page, click **uploading an existing file** and drag in
   the contents of this folder (all 5 files, not the folder itself).
3. Commit the changes.
4. In Vercel: **Add New… → Project**, pick the repo, click **Deploy**.
   No framework preset or build settings needed — Vercel serves it as-is.
5. To attach a custom domain: project **Settings → Domains → Add**,
   then update DNS at the domain's registrar. SSL provisions automatically.

## Re-skinning it for a client

Open `styles.css` and edit the variables at the top of the file (`:root`).
Changing `--accent`, `--ink`, and `--cream` alone will re-color the entire site.
Fonts are set with `--font-display` and `--font-body` in the same block.
