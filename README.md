# Vikram's AI twin — deploy guide

The portfolio page already has the chat panel. It picks its "brain" in this order:
1. **Your Worker** (this folder) — set `TWIN_ENDPOINT` in the page. Use this for the public site.
2. **Claude inside claude.ai** — works automatically for signed-in viewers who allow it.
3. **Offline FAQ** — built-in answers, so the twin never breaks.

## Steps (about 20 minutes)
1. **Get an API key** at console.anthropic.com → API Keys. In Billing, set a monthly spend limit.
2. **Install Wrangler**: `npm install -g wrangler`, then `wrangler login` (free Cloudflare account).
3. **Edit `worker.js`**: put your site address in `ALLOWED_ORIGINS` (for example `https://vikram-pm.github.io`).
4. **Add the key as a secret**: `wrangler secret put ANTHROPIC_API_KEY` and paste the key. Never put it in the page.
5. **Deploy**: run `wrangler deploy` in this folder. Copy the URL it prints (…workers.dev).
6. **Connect the page**: in the portfolio HTML, set `const TWIN_ENDPOINT = 'https://vikram-ai-twin.<you>.workers.dev';` and publish the site to GitHub Pages.
7. **Test** with `twin-tests.md` before sharing the link.

## Updating what the twin knows
Edit `knowledge.md`, paste the same text into `TWIN_KNOWLEDGE` in the page and into `worker.js`, then run `wrangler deploy` again.
