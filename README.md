# Brandon Nguyen — Portfolio

Static site for GitHub Pages. No build step.

- `index.html` — the whole site. Project text, captions and image lists live in the `PROJECTS` and `OTHER` arrays near the top of the `<script>`.
- `img/` — each image comes in two sizes: `name.jpg` (1800px) and `name-sm.jpg` (900px). Add both when you add an image.

To publish: put these files in a repository named `<username>.github.io`, then in Settings → Pages choose "Deploy from a branch", branch `main`, folder `/ (root)`.
