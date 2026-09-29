# Verification and remaining review

Confirmed locally:
- Both HTML files parse and render in the browser; mint pause and companion word return links work.
- Both use the same epoch, pace and letter generation.
- Independently enumerated A–Z and every two-letter string match all 1,378 character positions.
- Designated-word calculations and first whole-millisecond timing checked for A, Z, AA, AB, ZZ, AAA, JOHANN and a 26-letter string.
- Calendar generation tested: Johann at 2027-05-12T10:03:41Z (rounded up), HTTPS return URL, five-minute alarm, CRLF and byte-folding. Test calendar was not imported.
- Actual PNG/SVG export functions executed for AB. PNG visually inspected; SVG character positions checked (29–30). Browser Save/Print actions were exercised during development.
- No external scripts, fonts or assets are required. Offline rendering does not imply a trusted device clock.

Documentation images:
- AB-a-limited-infinity.png and AB-print.svg: actual export outputs for a past word.
- preview-one-hour.png: a reconstructed promotional still at precisely one hour after the beginning, generated from the artwork renderer with a controlled test clock and a fixed portrait size. It is not a screenshot of the live moment or a platform-approved thumbnail. The visible letters follow the same rule; headers and timestamp are composed for documentation.

Unverified before mint:
- Current platform create flow and embedded artifact restrictions have not been inspected in this preparation.
- Static thumbnail acceptance and final immutable settings remain to be reviewed.
- No pinning, publishing, listing or mint transaction was performed.
- System font substitutions can affect appearance. No fonts are bundled.

## Long timeline navigation
Go to a date added to both HTML files; input is explicitly UTC and restricts visits to elapsed history. Browser date dialog and visit verified. Controlled-clock render checks passed at 20, 50, 100 and 1,000 calendar years after the study beginning. At 1,000 years the calculated history contains 1,136,048,716,800 letters; only viewport rows are drawn. Each synthetic render took about 3–4 ms in the local canvas test (not a cross-device benchmark). Future date visits were rejected in all four scenarios. This verifies arithmetic and rendering, not survival of infrastructure for a thousand years.

Launch date is pending user choice. Both files still use the original study timestamp; no launch reset has occurred.
