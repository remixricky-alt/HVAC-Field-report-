# HVAC Field Report Builder — GitHub Pages Package

This package is ready for GitHub Pages as a static site.

## What to upload
Upload **all files in this folder** to the root of a GitHub repository.

Files included:
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `netlify.toml` (safe to leave there; GitHub Pages ignores it)

## Fastest GitHub Pages setup
1. Create a new repository on GitHub.
2. Name it something like `hvac-field-report`.
3. Upload all files from this folder to the repository root.
4. In GitHub, go to **Settings** → **Pages**.
5. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
6. Click **Save**.
7. Wait a minute or two for GitHub Pages to publish.
8. Open the site URL GitHub shows you.

## iPhone install
Open the live site in Safari, then:
**Share → Add to Home Screen**

## Notes
- Data saves on each device using local storage.
- PDF export should be tested on the live GitHub Pages site, not inside a preview panel.


This updated package includes a typing-focus fix: text fields save when you leave the field instead of rerendering on every keystroke.
