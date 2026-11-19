# ClipPilot

ClipPilot turns the best moments of livestreams into vertical short videos and posts them to
YouTube Shorts, Instagram Reels and TikTok. This repo is the **public landing surface** for the
app: a static marketing site (home, privacy, terms) with its icon.

- `index.html` — the landing page
- `privacy.html` / `terms.html` — the store-policy pages
- `icon.png` — app icon

Static, no build step. Preview it locally:

```bash
cd ~/harness/projects/clippilot
python3 -m http.server 8080     # then open http://localhost:8080
```

**Brand lane:** ClipPilot holds the **Good Wave Media** YouTube authorization
([[goodwavemedia]]); the grant itself lives in the app's data directory and is never copied into
a repo or the vault. Related: [[litmuswell]], [[reelworks]].
