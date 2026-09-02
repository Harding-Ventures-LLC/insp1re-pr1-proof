Friends graph UI hosted proofs for 2026-09-02 (PR https://github.com/Harding-Ventures-LLC/insp1re/pull/6).

Reused existing project users: `today.proof` (Joe, zero friends), `journey.proof` (`jordan`), `nutrition.proof` (`nia`). No new Auth signups and no confirmation emails.

Shots are Flutter web release at 390pt × 852pt (2x) against hosted `qcpdfggdzanuglcswltv`. Not committed in the app repo.

Captured files (real PNGs, 780×1704):

- `friends-today-zero-dark.png` / `friends-today-zero-light.png` — Joe, no Friends row
- `friends-empty-dark.png` — account-sheet Friends, empty copy only
- `friends-request-dark.png` — Nia asked Jordan (`Asked.`)
- `friends-incoming-dark.png` — Jordan sees Accept / Ignore
- `friends-accepted-dark.png` / `friends-accepted-nia-dark.png` — accepted list both ways
- `friends-today-with-friend-dark.png` — Nia Today, Friends row present
- `friends-completions-dark.png` — Jordan detail, completions only
- `friends-unfriend-dark.png` / `friends-block-dark.png` — fresh loads after hosted RPCs returned ok

Binary git push to this repo is denied to the cloud agent (`cursor[bot]`). The PNGs are attached on PR #6 from this run rather than uploaded here as text (MCP file write would store ASCII, not a PNG).
