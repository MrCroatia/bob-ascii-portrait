# Bob — A presence in the room

A visual-only study for Bob: an ambiguous human-like presence formed directly from white ASCII characters on pure black. No portrait, photo, image asset, app framework, server code, analytics, or external runtime service is used.

## Run

Open `index.html` in a modern browser. A procedural face-and-shoulders field is shaded with luminance and texture, then mapped to a character ramp and painted on Canvas. Idle motion and blinking are subtle. Keyboard and pointer activity inside the page trigger short responses; the buttons let you preview typing, clicking, and thinking. Character density is adjustable, and reduced-motion settings are respected.

This demo does not watch activity outside its browser tab. Mood, chat, and real desktop integration remain future work.

The separate `bob-floating.html` study keeps the original `index.html` untouched and adds a full floating figure, tiny animated T-rex arms, drag movement, and randomized click reactions.

## Research notes

- [Capri Desktop](https://github.com/lachydotmcg/capri-desktop) informed the quiet, character-first companion framing. No Capri code or assets are used.
- [iart-ai/web-animation-skills — ASCII Animation](https://github.com/iart-ai/web-animation-skills/tree/main/skills/ascii-animation) covers generative ASCII fields and converting images, video, and 3D scenes to ASCII for canvas and Three.js.
- [collidingScopes/ASCII](https://github.com/collidingScopes/ASCII) is a JavaScript + HTML Canvas reference for image sampling and glyph rendering; its repository lists an MIT license.
- [ayangabryl/asciify-engine](https://github.com/ayangabryl/asciify-engine) offers a more advanced photo-aware GPU/WebGL2 engine and reusable agent skill under MIT.
- [Google's Gemini image-generation guide](https://ai.google.dev/gemini-api/docs/image-generation) was reviewed in the initial research. This revision uses no generated portrait or Google API.

## Deployment

This repository is prepared for static GitHub Pages deployment through `.github/workflows/pages.yml`. Enable **Settings → Pages → Source → GitHub Actions** once to allow the workflow to publish.

