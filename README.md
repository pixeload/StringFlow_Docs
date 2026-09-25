# StringFlow Documentation

Official documentation site for **StringFlow** — a Unity Editor toolkit of three tools
(StringFlow Tables, StringFlow Translate, StringFlow Environment Setup) for finding, auditing,
and machine-translating localized strings entirely on your own machine, with no cloud account
or per-word billing.

**Live site:** [REPLACE ME — your GitHub Pages URL, e.g. https://\<your-username\>.github.io/stringflow-docs/]

This repository contains **only the documentation website** — static HTML/CSS, no build step,
no dependencies. It is not the Unity asset itself; StringFlow is distributed separately via the
Unity Asset Store.

## What's here

| Page | Covers |
| --- | --- |
| `index.html` | Homepage |
| `introduction.html` | What StringFlow is and how its three tools fit together |
| `getting-started.html` | Installing StringFlow and translating your first table |
| `stringflow-tables.html` | Finding, auditing, and cleaning up localized strings |
| `stringflow-translate.html` | Machine-translating a String Table Collection |
| `environment-setup.html` | Installing and managing the local translation server(s) |
| `manual-setup.html` | Doing everything the setup wizard automates, by hand |
| `connecting-backends.html` | The REST contract for wiring up a custom translation backend |
| `licensing.html` | Third-party licences for everything StringFlow drives (LibreTranslate, NLLB, etc.) |
| `troubleshooting.html` | Fixes organized by what you're actually seeing |

Shared chrome (sidebar nav, fonts, styling) lives in `assets/style.css`; the logo is
`assets/logo.png`.

## Running it locally

No build step — open `index.html` directly in a browser, or serve the folder with anything
static:

```bash
python -m http.server 8080
# then visit http://localhost:8080
```

## Deploying

This site is a plain static folder, so any static host works (GitHub Pages, Netlify, Vercel,
Cloudflare Pages). For GitHub Pages: **Settings → Pages → Source: Deploy from a branch →
Branch: `main`, folder: `/ (root)`**.

## License

[REPLACE ME — e.g. "© 2026 \<your studio/publisher name\>. All rights reserved." if this is
proprietary documentation for a commercial asset, or an actual OSS license if you want the docs
themselves to be reusable.]
