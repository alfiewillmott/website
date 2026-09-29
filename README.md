# Sparq website

Static site — no build step.

- `/` → landing page (`index.html`)
- `/offer` → £499 funnel page (unlisted, noindex)
- All images are inlined in the pages; `support.js` and `image-slot.js` are the only runtime assets.

Deploy: connect this repo in Netlify with publish directory `.` (set in `netlify.toml`), or drag the folder onto app.netlify.com/drop.
