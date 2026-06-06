# Portfolio Website

This repository contains the static files for my personal portfolio and media archive.

Live site: https://shaemonet87.github.io/portfolio/

## What’s in this repo
- `index.html` — homepage
- `archive.html` — audio & video archives
- `styles.css` (or `style.css`) — styling
- `README.md` — this file

## Local development
To preview locally, open the files in your browser or use a simple HTTP server. For example:

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Updating the archive
- Audio embeds use Mixcloud iframe widgets — update the `feed` parameter in `archive.html` to point to a different Mixcloud upload.
- Video embeds use YouTube iframe IDs. Some videos may be taken down by YouTube; `archive.html` now includes direct links under each embed so you can open the video page if the embed fails.

## Deployment
This site is published to GitHub Pages from the `main` branch. To publish changes:

```bash
git add .
git commit -m "Describe changes"
git push origin main
```

## Troubleshooting
- If an embed doesn't display, try a hard refresh (Cmd+Shift+R) or open the direct YouTube/Mixcloud link included below the embed.
- If you want broken YouTube videos removed or replaced, tell me which ones and provide replacement URLs.

## Contact
You can include links to your social profiles or contact info here.

---
Small note: `archive.html` was updated to add fallback links for YouTube embeds — see the `video-archive` section.


