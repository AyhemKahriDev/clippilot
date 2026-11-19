# Proof — clippilot

The landing surface is three static pages; the proof is the real page in a real browser.

```bash
python3 -m http.server 8801 --directory ~/harness/projects/clippilot   # terminal 1
harness proof web http://127.0.0.1:8801/ --project clippilot
```

Expected: `PROOF PASS`, page + window captures non-blank, 10 checks.

Last proved: 2026-11-19 (`artifacts/20261119-135520`).
