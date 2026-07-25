# Family Reunion 2028 — Destination Vote

A six-destination comparison deck for a 20-person, three-generation family reunion (late June/July 2028), with researched pitches for Greece, an Alaska cruise, Slovenia, Hawaii, the Norwegian fjords, and Portugal (Azores + Algarve) — plus a neutral verdict tab, synthesized theme music, and ranked-choice (instant-runoff) voting for the 11 adult voters.

**Live site:** deployed via GitLab Pages from `family-reunion-2028.html` (see `.gitlab-ci.yml`).

## How to vote
Open the site, go to the **🗳️ Vote** tab, drag the destinations into your order of preference, then either add your ballot on a shared device or hit **Copy ballot code** and text the code to the organizer, who imports all ballots and runs the count.

Note: ballots are stored in each visitor's own browser — the site has no server, so votes do not sync between devices. The ballot-code workflow is how votes reach the organizer.

## Repo layout
- `family-reunion-2028.html` — the built, self-contained deck (deployed page)
- `_shell.html` — the tab shell + verdict/vote/music source, with `[[NAME]]` placeholders
- `*-pitch.html` — the six standalone destination pitches
- To rebuild after editing: inject each pitch into the shell placeholders with `&` → `&amp;` and `"` → `&quot;` escaping (see project notes)
