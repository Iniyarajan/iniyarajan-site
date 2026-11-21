# iniyarajan.dev

Personal portfolio site for Iniyarajan — full-stack & AI engineer.

Single-file static site (`index.html`), no build step. Hand-coded HTML/CSS/JS.

## Hosting

Served by nginx on the VPS (`porter-vps`, `148.251.229.73`) from
`/www/wwwroot/iniyarajan.dev`, behind Cloudflare DNS (grey/DNS-only) with a
Let's Encrypt cert.

## Deploy

The docroot on the box is a clone of this repo. Ship changes with:

```sh
git push                 # push to main
ssh porter-vps '/root/vps-deploy/vps-deploy.sh update iniyarajan.dev'
```

`update` for a `static` site = `git pull` in the docroot (atomic, no build).

## Local preview

Open `index.html` in a browser, or render a screenshot with headless Chrome.
