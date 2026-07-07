# ChefMaison AEO / GEO Experiment Dashboard

A single-page, self-contained dashboard that tells the story of ChefMaison's Answer Engine Optimisation (AEO/GEO) experiment: the research, the baseline proof that AI assistants don't yet suggest a private chef at the awareness stage, why the birthday-in-Amsterdam topic was chosen, and the expected outcomes.

## Files

- `index.html` — the dashboard (open in any browser).
- `.gitignore`

## View locally

Open `index.html` in a browser. That's it, no build step, no dependencies.

## Push to GitHub

From this folder:

```bash
git init
git add -A
git commit -m "ChefMaison AEO/GEO experiment dashboard"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Create the empty repo on GitHub first (no README, so nothing conflicts).

## Publish free with GitHub Pages

1. In the repo on GitHub: **Settings → Pages**.
2. **Build and deployment → Source:** Deploy from a branch.
3. Branch **main**, folder **/ (root)**, then **Save**.
4. After a minute it's live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- Fully self-contained: the ChefMaison logo and favicon are embedded as base64, so no image files are needed.
- Fonts (Inter) load from Google Fonts via CDN, so the first load looks best online and falls back to system fonts offline.
- All figures reflect the 26 June 2026 baseline and are meant to be re-measured after the blog is published.
