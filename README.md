# monoaster.github.io

The home page for mono-aster's open-source projects: [monoaster.github.io](https://monoaster.github.io).

One static `index.html`, no build step. The page is a road at night; scrolling drives the car past each project.

## Adding a project

In `index.html`, copy one `<li>` inside `<ol class="stops">` to the top of the list and move the `New` tag to it. Newest first. The road, the distance board, the river and the metro line lay themselves out again.

- `class="sign"` is a green road sign.
- `class="billboard"` takes an `<img>` on top. Add `drivein` and cars park under it. `data-reel="a.webp|b.webp"` shows more pictures in turn.
- A `.vms` board is optional: lines are split by `|`, pages by `;;`.

Pictures go in `assets/`. Fonts are in `assets/fonts/` (Big Shoulders Display, Overpass, Overpass Mono, Doto; all SIL Open Font License).

MIT licensed.
