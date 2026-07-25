# Family Reunion 2028 — Destination Vote

A six-destination comparison deck for a 20-person, three-generation family reunion (late June/July 2028), with researched pitches for Greece, an Alaska cruise, Slovenia, Hawaii, the Norwegian fjords, and Portugal (Azores + Algarve) — plus a neutral verdict tab, synthesized theme music, and ranked-choice (instant-runoff) voting for the 11 adult voters.

**Live site:** deployed via GitHub Pages — `index.html` is the built deck, served from the `main` branch root.

## How to vote
Open the site on any phone or computer, go to the **🗳️ Vote** tab, enter your name, drag the destinations into your order of preference, and hit **Submit my ballot**. Ballots collect automatically in a shared ballot box; re-submitting under the same name replaces your earlier ballot. If the shared box is ever unreachable, the page falls back to **Copy ballot code** — text the code to the organizer, who imports it and runs the count.

## Repo layout
- `family-reunion-2028.html` — the built, self-contained deck (deployed page)
- `_shell.html` — the tab shell + verdict/vote/music source, with `[[NAME]]` placeholders
- `*-pitch.html` — the six standalone destination pitches
- To rebuild after editing: inject each pitch into the shell placeholders with `&` → `&amp;` and `"` → `&quot;` escaping (see project notes)
