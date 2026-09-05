# ÆTHER — particle field

Single-file WebGL site. 120,000-point GPU particle field that morphs between
five geometries. three.js + custom GLSL, no build step, no dependencies to install.

## Deploy (Cloudflare Pages, ~2 min)
1. dash.cloudflare.com → Workers & Pages → Create → Pages → "Upload assets"
2. Drag this ENTIRE `dist` folder in
3. Name the project (e.g. `aether`) → Deploy
Result: https://<project>.pages.dev — permanent, free, global CDN.

## Files
- index.html   — the whole site (markup, CSS, shaders, logic)
- favicon.svg  — tab icon
- preview.jpg  — link preview card (Discord/iMessage/Twitter)

## Controls
Click shape buttons to morph · click-drag to orbit (release to throw)
· move mouse to push particles · scroll to read
