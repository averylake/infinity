# A Limited Infinity

Avery Lake, 2026. Self-contained, time-based HTML artwork. Silent. Continuous.

Live: https://infinity.averylake.art (Cloudflare Pages project `infinity-avery-lake`)

## Site
- `index.html`: the public companion. Same sequence and beginning as the artwork, plus word search, time records, calendar reminders and PNG/SVG excerpts. No external scripts, fonts, analytics or network requests.
- `social.png`: share image (1200 x 630), rendered from the artwork's own code.

## Frozen parameters (do not change)
- Beginning: 2026-09-15T20:40:46.490Z (epoch ms 1789504846490)
- Pace: 36 characters per second
- Alphabet: A to Z; sequence by increasing length, lexicographic within each length, no spaces
- The clock reconstructs the present from elapsed time, so re-deploying the same bytes restores the work exactly, including any downtime.

## release/
- `a-limited-infinity.html`: the artwork file prepared for minting (timeline, pause, history; no search). Not minted as of this commit.
- `ARTWORK-TEXT.md`, `artwork-metadata.json`, `VERIFICATION.md`, `PREPARATION-NOTES.md`, `AB-print.svg`: statement, frozen configuration, verification record and an example export.

## Restore
Upload `index.html` and `social.png` to any static host (Cloudflare Pages direct upload or Git deploy with no build command and the repository root as output). Check `SHA256SUMS`.
