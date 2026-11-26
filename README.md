# Anmol Koli — Portfolio

Single-page portfolio for **Anmol Koli** — Marathi rapper and YouTuber.

- **Main channel:** [@Anmolkoli1](https://www.youtube.com/@Anmolkoli1) · 160K+ subscribers
- **Music channel:** [@realanmol1](https://www.youtube.com/@realanmol1)
- **Music:** [Spotify](https://open.spotify.com/artist/2Vff2PC0pAu5av5lUEaZr7) · [Apple Music](https://music.apple.com/us/artist/anmol-koli/1625908557) · [JioSaavn](https://www.jiosaavn.com/artist/anmol-koli-songs/yaMbGOdtFsY_)

## About the site

One self-contained `index.html` — no build step, no dependencies beyond Google Fonts. All images (portrait + video thumbnails) are embedded as base64 data URIs, so the file works offline and can be dropped on any static host as-is.

Stats, track list, view counts and contact emails were pulled from his public channels (Nov 2026).

## Run locally

Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

Push to GitHub and enable **Settings → Pages → Deploy from branch → main / root**. The site goes live at `https://<user>.github.io/AnmolKoli-Portfolio/`.
