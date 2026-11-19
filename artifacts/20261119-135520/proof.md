# Proof — clippilot (web)

- **result:** `pass`
- **when:** 2026-11-19T13:55:20+01:00 → 2026-11-19T13:55:21+01:00
- **target:** `http://127.0.0.1:8801/`
- **runner:** `harness-proof.service` (pid 78583)
- **stop:** `/home/ayhem/harness/scripts/run.sh stop proof`

## Captures

- [`after.png`](after.png) — 1408×775, 107126 bytes, stdev 29.58, blank=False, sha256 `00f80393081912d6…`
- [`window.png`](window.png) — 1440×960, 137190 bytes, stdev 92.84, blank=False, sha256 `a31d7e6bbf17b77b…`

## Checks

- PASS `preflight` — display, lock, browser, bus
- PASS `url-reachable` — http://127.0.0.1:8801/ (HTTP 200)
- PASS `session-cdp` — proof :45727 pid 78583 (harness-proof.service)
- PASS `window-visible` — harness-proof window of session proof
- PASS `window-focused` — harness-proof raised before interaction
- PASS `after-non-blank` — after.png 1408x775 stdev=29.58
- PASS `window-non-blank` — window.png 1440x960 stdev=92.84
- PASS `cache-bypass` — HTTP cache disabled for the proof page
- PASS `page-url` — http://127.0.0.1:8801/
- PASS `window-url` — page=http://127.0.0.1:8801/ after-capture=http://127.0.0.1:8801/
