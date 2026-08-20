# Portfolio site — deploy instructions

No build tools, no npm, no Jekyll config — just these files, hosted as-is.

## Fastest path: GitHub Pages (free)

1. On github.com, click **New repository**. Name it either:
   - `YOUR-USERNAME.github.io` → site goes live at `https://YOUR-USERNAME.github.io/` (this becomes your main site/front door), or
   - anything else, e.g. `portfolio` → site goes live at `https://YOUR-USERNAME.github.io/portfolio/`
2. On the new repo's page, click **Add file → Upload files**, then drag in every file from this folder
   (`index.html`, `style.css`, `vex-robotics.html`, `bionic-hand.html`, `research.html`, `oceansafe.html`,
   plus an `assets/` folder once you add real images). Commit.
3. Go to **Settings → Pages**, set Source to the `main` branch, root folder, save.
4. Give it a minute — your site is live at the URL from step 1.

No git, no terminal, no command line needed for any of this — it's all drag-and-drop in the browser.

## Before it's ready to send to recruiters

- [ ] Replace every `[ ... ]` thumbnail and `.media-placeholder` block with a real `<img>` or video embed
      (each placeholder tells you the exact filename it expects, e.g. `assets/vex/chassis-cad.jpg`)
- [ ] Fill in the bio paragraph in `index.html`
- [ ] Replace `you@example.com`, `YOUR-USERNAME`, `YOUR-PROFILE` in every footer/nav
- [ ] Add a real `resume.pdf` into this folder (the nav already links to it)
- [ ] Expand the placeholder copy in `bionic-hand.html` and `research.html` — those are stubs with a few
      real facts, not finished write-ups like the VEX page
- [ ] Swap the `.media-placeholder` autonomous-run / demo-video blocks for real YouTube embeds once clips are uploaded

## Adding a new project later

Duplicate `bionic-hand.html`, rename it, update the nav links in **every** page (including `index.html`'s
project grid), and write the content following the section structure already used on the VEX page
(Overview → technical case study → results/media).
