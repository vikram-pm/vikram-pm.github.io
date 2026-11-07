# Vikram Seenivasan — AI Product Manager portfolio

One-page portfolio with a live 3D sphere field, five project case studies, demo videos and an AI twin.

```
index.html                     the whole site (HTML, CSS, JS in one file)
assets/videos/                 project demo videos (p01–p05)
assets/Vikram-Seenivasan-Resume.pdf
ai-twin-worker/                Cloudflare Worker that powers the AI twin (optional)
.nojekyll                      tells GitHub Pages to serve files as-is
```

## Publish on GitHub Pages (10 minutes)
1. On GitHub (account `vikram-pm`), create a **public** repository named exactly **`vikram-pm.github.io`**.
   This makes the site live at `https://vikram-pm.github.io/`. Your existing project sites (for example `/idp-canada-ap-contracts`) keep working.
2. Upload everything in this folder: **Add file → Upload files**, drag in the folder contents (including `assets` and `ai-twin-worker`), then **Commit changes**.
   Or with git: `git init && git add . && git commit -m "Portfolio" && git branch -M main && git remote add origin https://github.com/vikram-pm/vikram-pm.github.io.git && git push -u origin main`
3. Go to **Settings → Pages**, set **Source: Deploy from a branch**, **Branch: main / (root)**, and save.
4. Wait 1–2 minutes, then open `https://vikram-pm.github.io/`.

## Before you share the link
- **Photo:** add `assets/vikram.jpg` (4:5) and follow the `PHOTO:` comments in `index.html` (hero card and AI twin avatar).
- **Contact details:** email and LinkedIn are filled in from your résumé. Search `index.html` for them to change.
- **Résumé:** `assets/Vikram-Seenivasan-Resume.pdf` includes your phone number. Replace the file if you’d rather not publish it.

## Turn on the live AI twin (optional, about 20 minutes)
Without this step the twin still works, answering from its built-in FAQ (status shows “Offline mode”).
Follow `ai-twin-worker/README.md`, then in `index.html` set:
```js
const TWIN_ENDPOINT = 'https://vikram-ai-twin.YOUR-SUBDOMAIN.workers.dev';
```
Commit the change. Never put your Anthropic API key in `index.html`; it lives only in the Worker as a secret.

## Updating content
- Projects and case studies: the `PROJECTS` and `SHIP` data in `index.html`.
- Career timeline: `JOURNEY`. Lifecycle tags: `LIFECYCLE`.
- What the AI twin knows: `TWIN_KNOWLEDGE` in `index.html` and `ai-twin-worker/knowledge.md` + `worker.js` (keep them the same).
