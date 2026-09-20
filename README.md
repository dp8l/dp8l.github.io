# Devansh Patel

Personal site, served by GitHub Pages at https://dp8l.github.io/.

Structural engineer and PhD student at Arizona State University. Concrete composites, inverse analysis, and the HRC Designer software (https://www.hrcdesigner.com).

## Layout

- `index.html`, the whole site. Plain HTML, one stylesheet, a few lines of script for the theme toggle and the publication filter.
- `styles.css`, the stylesheet. Light and dark themes through CSS variables.
- `assets/`, the optimized images the site uses.
- `shared/`, older uploads kept for reference. The site does not use them.
- `.nojekyll`, tells GitHub Pages to serve the files as they are.

## Updating

- New paper. Copy one `<li class="pub">` block in `index.html`, set `data-type` to `journal` or `conference`, and update the three counts in the filter buttons.
- New release. Change the version and date in the Software section and in the Latest strip near the top.
- Bump the `Rev` date in the footer title block when you publish.
