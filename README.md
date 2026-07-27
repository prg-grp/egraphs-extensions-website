# Smart E-Graphs: Project Website

Website for the smart e-graphs project: making e-graphs more aware of semantics
and providing optimizations that leverage that additional information.

Hosted on GitHub Pages at <https://prg-grp.github.io/egraphs-extensions-website/>.

## Structure

- `index.html` — the whole site (single page, no build step)
- `assets/style.css` — all styling, including light/dark themes
- `assets/logo.svg` — the logo, used by both the header and the favicon; edit this one
  file to change the logo everywhere (colors live in its internal `<style>` block, with
  a dark-mode override)
- `publications/` — PDFs linked from the publications section
- `.nojekyll` — tells GitHub Pages to serve the files as-is, without a Jekyll build

## Updating

Edit `index.html` directly and push to `main`. To add a publication, drop the PDF in
`publications/` and copy one of the `<article class="pub">` blocks in `index.html`.

To publish for the first time, enable Pages in the repository settings:
Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
