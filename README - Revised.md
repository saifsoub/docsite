# docsite (Seif's fork) — plain-language README

## What this is
This is Seif's copy (a "fork") of **genkit-ai/docsite**, the documentation website for Genkit (Google's toolkit for building AI features into apps). The site is built with Astro and Starlight, tools that turn text pages into a docs website.

## Who it's for
Anyone who wants to read or host the Genkit docs, or change them.

## What it does today
- It builds the Genkit documentation website.
- **Seif's changes vs upstream:** on 14 March 2026 Seif merged PR #1 (branch `copilot/optimize-free-hosting-deployment`). It:
  - added `.github/workflows/deploy.yml`, which automatically publishes the site to GitHub Pages (GitHub's free hosting) using GitHub Actions;
  - changed `astro.config.mjs` and `pnpm-workspace.yaml` to fit that hosting.
- Whether the GitHub Pages site is live: not yet confirmed.

## How to run it
You need Node.js and pnpm.
```
pnpm install
pnpm dev       # preview at http://localhost:4321
pnpm build     # build the final site
pnpm preview   # look at the built site
```

## Current status and known gaps
- There is 1 open issue on this fork.
- Live site address: not yet confirmed.

## Where things live
| Folder / file | What's in it |
|---|---|
| `src/` | The site and its pages |
| `astro.config.mjs` | Site settings (edited by Seif) |
| `.github/workflows/deploy.yml` | Seif's auto-publish to GitHub Pages |
| `README.md` | The upstream readme |
