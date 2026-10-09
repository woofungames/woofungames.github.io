# Oceanyan Limited — GitHub Pages website

## Deploy (no command line needed)

1. Create a **public** GitHub repository named `<your-username>.github.io` (replace with your actual username).
2. Open the repository, choose **Add file → Upload files**, and upload **the contents of this folder**, not the ZIP itself or the outer folder. Make sure `index.html` is at the repository root. Commit the files.
3. Go to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, `main`, `/(root)`, then **Save**.
4. Wait for publishing, then visit `https://<your-username>.github.io/`.

## Before publishing as an official company site

- Replace the placeholder contact details with a verified business email.
- Confirm the legal company name, game ownership and relationship to Woofun Games.
- Add real game artwork and a verified RuStore listing URL.
- **Review and complete `privacy.html` and `terms.html`**. They contain explicitly marked drafts, not final legal policies.
- Populate `app-ads.txt` only with the exact lines provided by VK or other authorized ad partners. It is intentionally blank; do not invent publisher IDs.
- Check how RuStore exposes the developer website and how VK discovers `app-ads.txt`. GitHub Pages and a Finance 'Site' URL do not guarantee ad authorization approval.

## File structure

- `index.html`: home page
- `privacy.html`: privacy draft
- `terms.html`: terms draft
- `assets/style.css`: responsive styling
- `app-ads.txt`: intentionally empty ad authorization file
- `.nojekyll`: static hosting compatibility

## Local preview

Open `index.html` in a browser. No build tools or dependencies are needed (Google Fonts is optional and loaded from a CDN).
