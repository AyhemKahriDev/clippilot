# Proof — clippilot (web)

- **result:** `pass`
- **when:** 2026-11-19T18:07:00+01:00 → 2026-11-19T18:07:02+01:00
- **target:** `http://127.0.0.1:8801/`
- **runner:** `harness-proof.service` (pid 318770)
- **stop:** `/home/ayhem/harness/scripts/run.sh stop proof`

## Captures

- [`after.png`](after.png) — 1408×775, 107126 bytes, stdev 29.58, blank=False, sha256 `00f80393081912d6…`
- [`window.png`](window.png) — 1440×960, 134395 bytes, stdev 93.58, blank=False, sha256 `4706858b689bd37a…`

## Checks

- PASS `preflight` — display, lock, browser, bus
- PASS `url-reachable` — http://127.0.0.1:8801/ (HTTP 200)
- PASS `session-cdp` — proof :39971 pid 318770 (harness-proof.service)
- PASS `window-visible` — harness-proof window of session proof
- PASS `window-focused` — harness-proof raised before interaction
- PASS `after-non-blank` — after.png 1408x775 stdev=29.58
- PASS `window-non-blank` — window.png 1440x960 stdev=93.58
- PASS `cache-bypass` — HTTP cache disabled for the proof page
- PASS `page-url` — http://127.0.0.1:8801/
- PASS `window-url` — page=http://127.0.0.1:8801/ after-capture=http://127.0.0.1:8801/
