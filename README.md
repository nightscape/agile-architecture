Agile Architecture
==================

An [impress.js](https://github.com/impress/impress.js) presentation on Agile Architecture.

Video
-----
<video src="https://user-images.githubusercontent.com/35170/236177370-87945c72-ba18-4e25-8f6f-e100abadc8c1.mp4"></video>

Slides
------
The whole presentation is a single self-contained file: [`index.html`](index.html).
Just open it in a modern browser — no build step, nothing to install.
`impress.js` and `marked` are loaded from a CDN, and the slide images live in `img/`.

It is deployed automatically to GitHub Pages on every push to `main`:
<https://nightscape.github.io/agile-architecture/>

### Editing

Slide content is authored as Markdown inside `.md` step elements; all styling lives
in the `<style>` block at the bottom of the file.

Positioning uses a small skeleton of absolute anchors (`#agile-core`, `#arch-def`,
`#agile-architecture`, and the centre title) with every other slide placed relative
to an anchor via `data-aim="<id>"` plus `data-offset-x` / `data-offset-y`. Move an
anchor and its whole cluster follows.

### Controls

`Space` / `→` next · `←` back · `Esc` overview
