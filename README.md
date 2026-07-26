# Misbah's Birthday Site

## How to deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `misbah-birthday`).
2. Upload **both** `index.html` and the `images/` folder (with all the .jpg files inside it) to the repository, keeping the same folder structure.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Wait a minute or two, then GitHub will give you a live link like:
   `https://yourusername.github.io/misbah-birthday/`

That link is what you can send to Misbah.

## Notes
- Keep `index.html` and the `images` folder in the same place relative to each other — the page loads photos from `images/...`, so if that folder moves, the photos will break.
- No other setup needed — it's a static site, works instantly on GitHub Pages.
