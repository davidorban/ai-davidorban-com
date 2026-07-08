# ai.davidorban.com

A single-page site about how David Orban works with AI — his approach ("humans and
AIs, side by side"), the working toolkit, and a direct line to **Dex**, his AI
assistant, at `dex@ai.davidorban.com`.

## Hosting
- **GitHub Pages** (this repo, `main` branch, root).
- Custom domain: `ai.davidorban.com` (see `CNAME`).
- DNS: **DNS-only A/AAAA records** to GitHub Pages on the Cloudflare zone
  `davidorban.com`. A-records (not a CNAME) because `ai.davidorban.com` already
  carries an `MX` record for AgentMail email — a CNAME can't coexist with an MX.
- HTTPS: issued by GitHub Pages (Let's Encrypt).

## Edit
Everything is in `index.html` (self-contained, inline CSS/JS). Push to `main` to deploy.
