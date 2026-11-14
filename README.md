# Christmas Star Run · Забіг Звіздарів — landing page

Static site, no build step. Open `index.html` (or use VS Code "Live Server") to preview.

## Deploy to Vercel
```bash
npm i -g vercel        # once
vercel                 # first deploy; project name: winnipeg-star-run
vercel --prod          # publish to https://winnipeg-star-run.vercel.app
```
If the name `winnipeg-star-run` is taken, pick another and update:
- the URL in `index.html` (og:url, og:image) and `star-run.ics`
- regenerate the QR code (files in `qr/`)

## Files
- `index.html` — the whole page (EN/УКР toggle; `?lang=uk` opens Ukrainian)
- `img/`, `media/` — optimized photos and hero video
- `og-image.jpg` — social preview image (shown when the link is shared)
- `star-run.ics` — "Add to calendar"
- `qr/` — QR code for print (SVG/PDF) and Instagram (PNG); not deployed
