# PR235 — Explicit `isHeading` field (revision)

Review-only screenshots for BibleGo PR #235's revised design: mid-verse NASB
section headings rendered via an explicit `isHeading: true` data field (no
heuristic parser).

- `pr235-explicit/*.png` — raw local web screenshots (desktop + mobile) of the
  explicit-field build (`npm run start`), representative + adversarial cases.
- `pr235-explicit/composites/*.png` — labeled BEFORE (origin/main plain-text
  rendering) vs AFTER (explicit `isHeading` rendering) side-by-side composites.

`*_UNCHANGED.png` composites are regression proofs: the BEFORE and AFTER panels
are pixel-identical (verified via image diff) for ordinary prose, verse-start
subtitles, poetry stanzas, near-miss cases, and Strong's — only the four heading
verses change.

Not committed to the BibleGo repo. Hosted here and embedded via
raw.githubusercontent.com.
