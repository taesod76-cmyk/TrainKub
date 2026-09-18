# TRAINKRUB (เทรนครับ)

A single-page PWA for booking and managing personal trainers.

## Files

- `index.html` — the entire app (HTML/CSS/JS in one file)
- `manifest.webmanifest` — PWA manifest (name, icons, colors)
- `service-worker.js` — offline caching
- `icons/` — app icons in all standard sizes, plus `favicon.ico`

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `trainkrub`).
2. Upload all the files/folders in this ZIP to the root of that repository
   (keep the `icons/` folder as-is).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`, then **Save**.
5. Wait a minute, then open the URL GitHub gives you
   (usually `https://<your-username>.github.io/trainkrub/`).

That's it — no build step, no server required. On phones, visitors can use
"Add to Home Screen" to install it like an app.
