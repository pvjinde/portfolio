# portfolio# Priyanka Jinde — QA Engineer Portfolio

A personal portfolio for a **Senior Software QA Engineer** in telecom (4G / CBRS / MOCN),
built as a single self-contained HTML file. The whole page is framed as a QA
validation run — sections are test cases with PASS / RUNNING / READY status, and
selected work is shown as test-case and bug artifacts.

**Live site:** _add your URL here_ — e.g. `https://pvjinde.github.io/portfolio/`

---

## Features

- **Single file, no build step** — everything (HTML, CSS, JavaScript) lives in `index.html`. Nothing to compile or install.
- **Light / dark theme toggle** — switches between a resume-matched purple light theme and a network-operations dark theme. The choice is remembered per visitor.
- **Fully responsive** — adapts from desktop down to mobile; the nav collapses and multi-column grids reflow.
- **Print-ready** — a dedicated print stylesheet renders a clean, ink-friendly version for saving as PDF.
- **Accessible motion** — respects the visitor's `prefers-reduced-motion` setting; animations pause and the page stays fully readable without JavaScript.
- **A crawling-bug easter egg** — a small ladybug that walks along the bottom of the page, with an on/off toggle. Fitting for a portfolio about finding bugs.

---

## Sections

- **Profile** — summary, quick facts, and a stat band (experience, sessions validated, cases authored, cases automated)
- **Environment & Tools** — skills grouped by testing, wireless/protocol, AI/LLM, backend/frontend, and infrastructure
- **Career History** — full work history, presented as a regression suite
- **Case Studies** — CBRS/MOCN interoperability, LTE core validation at scale, and a self-built AI test-plan pipeline
- **Recognition & Publications** — awards and IEEE/IOSR papers
- **Contact** — email and LinkedIn

---

## Tech

- Plain HTML, CSS (custom properties for theming), and vanilla JavaScript — no frameworks.
- Typography: [IBM Plex Sans & IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Sans) via Google Fonts.
- No dependencies, no package manager, no tracking.

---

## Run it locally

Just open the file in a browser:

```
open index.html      # macOS
start index.html     # Windows
xdg-open index.html  # Linux
```

An internet connection is only needed so the web fonts load; everything else is embedded.

---

## Deploy

**GitHub Pages**
1. Put `index.html` at the root of a public repository.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `root` → Save.
3. Your site goes live at `https://<username>.github.io/<repo>/` in about a minute.

**Netlify / Vercel / Cloudflare Pages**
Drag the file (or connect this repo) in the dashboard — it deploys as-is with no configuration.

---

## Customizing

- **Default theme** — change `data-theme="light"` to `data-theme="dark"` on the `<html>` tag near the top.
- **Contact links** — update the `mailto:` and LinkedIn `href` values (they appear in the hero and the contact section).
- **The bug** — toggle it off in the footer, or remove the `<div id="bug">` element and its `#bug` styles to drop it entirely.
- **Colors** — all theme colors are CSS custom properties in the two `html[data-theme="..."]` blocks in the `<style>` section.

---

## Author

**Priyanka V. Jinde** — Senior Software QA Engineer · Telecom · Pune, India
[LinkedIn](https://www.linkedin.com/in/priyanka-j-39b20466/) · priyankavjinde@gmail.com
