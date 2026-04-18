# SF Supervisor Lookup Widget

A tiny static Vercel app for looking up a San Francisco district supervisor by address.

## What changed in this version

- Simplified UI for embedding on a larger advocacy page
- Address-only lookup widget
- Gmail compose button as the primary action
- `mailto:` button kept as a fallback for users who prefer a local mail app
- Copy-email button for a third fallback

## Files

- `index.html` — the full widget in one file
- `vercel.json` — minimal Vercel config

## Deploy

1. Create a new GitHub repo.
2. Upload these files to the repo root.
3. Import the repo into Vercel.
4. Deploy as a static project.

## Embed in Notion

After deployment, copy the public Vercel URL and paste it into Notion using `/embed`.

## Update supervisor emails

The district-to-email mapping is hardcoded near the top of `index.html` in the `SUPERVISORS` object.

## Data source

The widget uses San Francisco's public address dataset for address search and district matching.
