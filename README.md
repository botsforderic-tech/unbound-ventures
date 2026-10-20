# Unbound Ventures website

Static site hosted on Cloudflare Pages. Every push to `main` publishes automatically.

## Adding trip photos
Drop a landscape photo named `cover.jpg` into the matching folder and push. The trip poster picks it up automatically, no code changes needed.

- `assets/mount-temple/cover.jpg`
- `assets/roatan/cover.jpg`
- `assets/sedona/cover.jpg`
- `assets/grand-canyon/cover.jpg`

Aim for 2400px wide, under 600 KB.

## Cloudflare Pages settings
- Framework preset: None
- Build command: (leave empty)
- Build output directory: `/`
