# WISE: Project Website

Website for WISE (WISE Is Semantic-aware E-Graphs): making e-graphs more aware of
semantics and providing optimizations that leverage that additional information.

Hosted on GitHub Pages at <https://prg-grp.github.io/egraphs-extensions-website/>.

## Structure

- `index.html` — the main page
- `background.html` — longer background on e-graphs and the challenges WISE addresses
- `style.css` — all styling, including light/dark themes (brand colors live in the
  `:root` variables at the top)
- `assets/` — logos and images:
  - `logo-base.svg` — the owl mark, used as the favicon (light/dark aware)
  - `logo-wise.svg` / `logo-wise-dark.svg` — the "WISE" wordmark for light and dark mode
  - `logo-hero.svg` — the animated wordmark injected into the hero (owl blink / leaf /
    tail / ear animations live in its internal `<style>` block)
- `publications/` — PDFs linked from the publications section
- `.nojekyll` — tells GitHub Pages to serve the files as-is, without a Jekyll build

## Updating

Edit `index.html` directly and push to `main`. To add a publication, drop the PDF in
`publications/` and copy one of the `<article class="publication">` blocks in `index.html`.

To publish for the first time, enable Pages in the repository settings:
Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
