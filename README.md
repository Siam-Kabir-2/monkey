# $SMOS website

Local static brand and community website for $SMOS. The deployable site lives
inside `dist/` and has no runtime dependencies.

## Local preview

```powershell
python -m http.server 4173 --directory dist
```

Open `http://localhost:4173` in your browser.

## Deploy on Vercel

Import this repository into Vercel with these settings:

- Framework Preset: `Other`
- Build Command: leave blank
- Output Directory: `dist`

The included `vercel.json` already sets the output directory, clean URLs, and
trailing-slash behavior.
