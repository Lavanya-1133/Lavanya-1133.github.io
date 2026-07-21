# lavanya-bhatnagar.github.io

Personal portfolio site, styled as a technical dossier (a blueprint cover
sheet followed by numbered specification sheets) to match a formal,
engineering register.

## Files

- `index.html` — all page content and structure
- `style.css` — all styling (colours, type, layout live in `:root` at the top)
- `script.js` — two small behaviours: nav border on scroll, fade-in on scroll
- `README.md` — this file

There is no build step. It's plain HTML/CSS/JS, so it can be opened directly
in a browser or hosted as-is on GitHub Pages.

## Things still marked for you to fill in

Search the files for `[Add dates]` and `[Add ...]` — these are placeholders,
styled in brass/amber so they're easy to spot on the live page too:

- **Experience → SURGE internship**: exact dates, and 1–2 lines on your
  specific contribution (estimation/control approach, sensors, validation).
- **Projects → IRoC-U**: exact dates, and any further detail on the VIO
  implementation you'd like to include (framework used, how it was
  validated, etc).

## Adding project media

Each project card has a dashed placeholder box:

```html
<div class="figure-slot"><span>Fig. 0X — Media Pending</span></div>
```

To swap in a real image, create an `assets/` folder next to `index.html`,
drop your file in (e.g. `assets/nidar-01.jpg`), and replace the div above
with:

```html
<img src="assets/nidar-01.jpg" alt="Describe what the image shows">
```

For a short video/GIF demo, an `<img>` tag works fine for a `.gif`; for
`.mp4` clips use a `<video>` tag with `controls`.

## Publishing

See the step-by-step guide in the chat where this was generated, or in
short: push these files to a repository named
`<your-github-username>.github.io`, and GitHub will serve them at
`https://<your-github-username>.github.io` within a minute or two of the
push landing on the default branch.
