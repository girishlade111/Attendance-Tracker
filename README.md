# Attendance Tracker

A lightweight, client-side web app for recording and managing daily attendance. Built with plain HTML, Tailwind CSS (CDN), and vanilla JavaScript — no build step, no backend, and everything runs locally in the browser.

## Features

- Mark daily attendance (present / absent / leave) per student or employee
- Switch between dashboard, entry, and history views in a tabbed interface
- Attendance records persist in the browser via `localStorage` — works offline after first load
- Responsive, modern UI built with Tailwind CSS and Font Awesome icons
- Zero dependencies to install — open `index.html` and it works

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript (`localStorage` for persistence)
- Font Awesome icons

## Quick Start

### Run locally

```bash
# clone and open
git clone https://github.com/girishlade111/Attendance-Tracker.git
cd Attendance-Tracker
open index.html   # or double-click in your file manager
```

Or serve it with any static server:

```bash
npx serve .
# then open http://localhost:3000
```

### Use the hosted version

Open the live site linked on this repo's GitHub page.

## Project Structure

```
Attendance-Tracker/
├── index.html   # Entire app: views, styles, and JS in one file
└── README.md
```

## Notes

- Data is stored only in the browser's `localStorage`; clearing site data resets attendance records.
- Since it's 100% static, it deploys cleanly to GitHub Pages, Netlify, Cloudflare Pages, or any static host.

## Deploy

```bash
# GitHub Pages
# Settings → Pages → Deploy from branch → main → / (root)
```

## License

MIT — free to use and modify.

---

Built by Girish Lade — [ladestack.in](https://ladestack.in)
