# gauravbuilds.online

Personal portfolio — Big Data & GenAI Engineer. Static single-page site, no build step.

## Files
- `index.html` — the whole site (HTML + CSS + JS inline). Edit content here.
- `netlify.toml` — Netlify config (publishes the repo root).
- `resume.pdf` — **add your own** (the Résumé buttons link to `/resume.pdf`). Drop your PDF in the repo root with this exact name.

## Deploy to Netlify (2 minutes)
1. Push this folder to a GitHub repo.
2. In Netlify → **Add new site → Import an existing project** → pick the repo.
3. Build command: **(leave empty)**. Publish directory: **`.`** (root). Deploy.
4. Point your domain: Netlify → **Domain settings → Add custom domain** → `gauravbuilds.online`, then update your DNS as Netlify instructs.

Drag-and-drop also works: zip the folder and drop it on the Netlify dashboard.

## Editing
- **Text/projects/experience**: search for the section comments (`<!-- WORK -->`, `<!-- EXPERIENCE -->`, etc.) in `index.html`.
- **Colors**: the `:root` block at the top — the palette is built from the Bronze/Silver/Gold medallion theme (`--gold` is the primary accent).
- **Stats numbers**: the `<!-- STATS -->` section.

## Notes
- Fully responsive, keyboard-accessible focus states, and respects `prefers-reduced-motion`.
- No dependencies except Google Fonts (loaded from CDN). Works offline-ish; fonts need network.
