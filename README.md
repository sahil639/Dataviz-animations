# Dataviz Animations

Static HTML animation prototypes. Every page is self-contained (fonts, images and data are inlined), so the repo deploys to Vercel as a plain static site with no build step.

| Path | What it is |
| --- | --- |
| `/data-recap-sequence-3/` | Data Recap Sequence 3: a 10-card September recap set in Söhne. Each card runs 10s (3s entrance, 5s hold, 2s transition) with autoplay; tapping or the arrow keys switch to manual control. Card 06 has a 0–100% control (left of the phone) that drives the holdings-growth graph. |

## Archive

`archive/` holds earlier sequences. It is listed in `.vercelignore`, so it is kept in the repo but not deployed:

- `archive/data-recap-sequence-1/` — Data Recap Sequence 1 (11 dial-style cards)
- `archive/data-recap-sequence-2/` — Data Recap Sequence 2 (11-screen motion redesign)

To bring one back, move its folder out of `archive/` to the repo root (or delete the `archive/` line from `.vercelignore`) and add a link to it in `index.html`.

## Deploy

Import the repo in Vercel with the **Other** framework preset, leave the build command empty, and use the repo root as the output directory.
