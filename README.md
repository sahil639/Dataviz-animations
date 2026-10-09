# Dataviz Animations

Static HTML animation prototypes. Every page is self-contained (fonts, images and data are inlined), so the repo deploys to Vercel as a plain static site with no build step.

| Path | What it is |
| --- | --- |
| `/groww-recap-seq1/` | Groww monthly recap, Sequence 1: 11 dial-style story cards. Each card runs 10s (3s entrance, 5s hold, 2s transition). Autoplay by default; tapping, swiping or the arrow keys switch to manual control. Hold or press Space to pause. |
| `/september-recap-v2/` | September Recap v2: 11 screens with a new motion design for each, using the same 10s timing, autoplay and manual control. |

## Deploy

Import the repo in Vercel with the **Other** framework preset, leave the build command empty, and use the repo root as the output directory.
