# iniyarajan.dev

Personal portfolio site for **Iniyarajan** — senior iOS & mobile engineer.

Live at **[iniyarajan.dev](https://iniyarajan.dev)**.

## About

Single-file static site (`index.html`) — hand-coded HTML, CSS and a touch of JS,
no framework and no build step. Dark-first design, Space Grotesk + Inter +
JetBrains Mono, with a progressive-enhancement scroll reveal (the page renders
fully without JavaScript).

## Deploy

Self-hosted behind nginx + Cloudflare, with a **GitHub Actions push-to-deploy**
pipeline ([`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)) —
push to `main` and it ships automatically. Host and credentials live in
repository/CI secrets, never in the source.

## Local preview

Open `index.html` in any browser.
