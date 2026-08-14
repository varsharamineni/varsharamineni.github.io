# BiasTrace — Project Page

A single-file GitHub Pages site for the BiasTrace paper.

## Deploy in 3 steps

1. Create a new repo (e.g. `biastrace-page`) or use an existing one — for a **project page** the URL will be `https://<username>.github.io/<repo>/`. For your **user page**, name the repo `<username>.github.io` and the URL is `https://<username>.github.io/`.
2. Drop `index.html` in the repo root and push.
3. In the repo's **Settings → Pages**, set the source to `main` (root). It'll be live in a minute or two.

## Before you publish

- Replace `href="#"` on the "Read the paper" and top-strip "Paper" links with your arXiv or preprint URL (there's a `TODO` comment in the file).
- The GitHub link, author list, affiliations, and contact are pulled from the paper — double-check they're right.
- Fonts are loaded from Google Fonts (Fraunces, Source Serif 4, JetBrains Mono). No build step needed.

## Editing

Everything is one file — HTML, CSS, and content. The colour tokens live in `:root` at the top of the `<style>` block, so palette changes are a one-liner. The six annotation wash colours map to the BiasTrace behaviours and are reused in the legend, trace, and callout — change one, and it updates everywhere.

## What's on the page

- Header with title, authors, affiliations, and links
- Six-part narrative walkthrough: the gap → scheme → annotated trace → key finding → applications → takeaway
- One signature element: a real reasoning trace from Figure 1 of the paper, annotated inline with the BiasTrace scheme
- Minimal footer

Designed to fit within \~6–8 screens of scroll on desktop.
