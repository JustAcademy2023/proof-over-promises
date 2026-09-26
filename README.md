# proof-over-promises

**A single page landing site for "How Real Projects Help Freshers Get IT Jobs"** — built for JustAcademy Pune to point freshers toward live, mentor led bootcamps and courses instead of another passive video queue.

![status](https://img.shields.io/badge/status-live-C89B3C) ![type](https://img.shields.io/badge/type-landing--page-14213D) ![responsive](https://img.shields.io/badge/responsive-yes-2F6F62)

## What this is

A self contained, single file HTML landing page designed around one idea: freshers don't get hired because of certificates, they get hired because of proof. The page walks a visitor from the problem (why applications go silent), into the five live programs on offer, into a short reading room of supporting blog posts, and out to a clear call to action.

No build step, no dependencies, no framework. Open `index.html` in a browser and it works.

## Design concept

The visual language borrows from an engineer's field notebook and blueprint paper rather than a typical SaaS template. Highlights:

- **Palette** — deep ink navy, warm parchment, muted gold, and a quiet teal accent. No cream and terracotta combo, no neon on black.
- **Type** — Fraunces (serif, display) paired with IBM Plex Mono (labels, body, navigation) for a technical, handwritten log feel.
- **Layout** — a blueprint grid hero with corner registration marks, a "build log" list of programs instead of shadowed cards, and a two column "reading room" on a dark plate.
- **Motion** — kept minimal and purposeful: hover states only, `prefers-reduced-motion` respected.

## Structure

```
.
├── index.html      # entire site: markup, styles, and the small JS menu toggle
└── README.md        # this file
```

## Sections

| Section | Purpose |
|---|---|
| Hero | The core argument, stated in one line, with a route into programs or the JustAcademy homepage |
| The Problem | Why identical resumes get filtered out before a human ever reads them |
| The Build Log | All five live, mentor led programs, each linking straight to its course page |
| Reading Room | Four supporting blog posts for freshers still deciding on a direction |
| CTA Band | A single, low pressure invitation to the JustAcademy homepage |
| Footer | Full sitemap of every program and blog link, repeated for accessibility and SEO |

## Links wired into the page

**Programs**
- Full Stack Java Developer Bootcamp (Pune)
- Full Stack Python Developer Bootcamp (Pune)
- Selenium Training (Pune)
- Python Training (Pune)
- Data Analytics Course (Pune)

**Reading room**
- Top IT skills to learn in 2026 for high paying jobs
- How to become a data analyst in 2026 without a technical background
- Selenium automation testing framework, complete beginner guide
- How real projects help freshers get IT jobs

**Homepage** — linked from the nav, hero, and CTA band.

## Running locally

No installation needed.

```bash
git clone https://github.com/your-username/proof-over-promises.git
cd proof-over-promises
open index.html      # macOS
# or just double click the file, or serve it:
python3 -m http.server 8000
```

## Deploying

This is a static file, so it works as is on GitHub Pages, Netlify, Vercel, or any static host.

For GitHub Pages: push to a repo, enable Pages in Settings, point it at the root of `main`, and the site is live at `https://your-username.github.io/proof-over-promises/`.

## Customising

All design tokens live at the top of the `<style>` block in `index.html` under `:root`, so colors, spacing, and the max content width can be changed in one place without hunting through the file.

## License

Free to reuse and adapt for JustAcademy's own marketing and training pages.
