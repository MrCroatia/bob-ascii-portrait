# Bob — A face made of light

A visual-only character study: an original fictional portrait rendered as dense white characters on pure black. The page is a single self-contained HTML file with the portrait embedded; no app framework, server code, analytics, or image API is required.

## Run

Open `index.html` in a modern browser. The page draws the embedded portrait into a sampled canvas, maps luminance to a variable-density character ramp, and paints the glyphs directly to a second canvas. The small controls tune glyph density and idle motion. A restrained sway and occasional eye-line blink add life. Reduced-motion preferences disable movement.

The density labels are a visual-only control. Mood, chat, and expression response are intentionally out of scope for this appearance study.

## Research notes

- [Capri Desktop](https://github.com/lachydotmcg/capri-desktop) informed the character-first presentation and quiet companion framing. This prototype does not use Capri code or assets.
- [iart-ai/web-animation-skills — ASCII Animation](https://github.com/iart-ai/web-animation-skills/tree/main/skills/ascii-animation) is the best-fitting reusable agent skill: it covers generative ASCII fields and converting images, video, and 3D scenes to ASCII for canvas and Three.js.
- [collidingScopes/ASCII](https://github.com/collidingScopes/ASCII) is a practical JavaScript + HTML Canvas reference for sampling source imagery and painting character cells. Its MIT license is listed in its repository.
- [ayangabryl/asciify-engine](https://github.com/ayangabryl/asciify-engine) is the strongest reusable engine/skill option for future expansion: it includes photo-aware ASCII rendering, GPU/WebGL2, media input, and an agent skill; it is MIT licensed.
- [Google's Gemini image-generation guide](https://ai.google.dev/gemini-api/docs/image-generation) was reviewed for portrait prompt and iteration guidance. No Google API or external runtime service is used by the demo.

## Deployment

This repository deploys its root as a static GitHub Pages site through `.github/workflows/pages.yml`.

