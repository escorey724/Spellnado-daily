# Spellnado daily catalog

Public **today + history** for [Spellnado](https://github.com/escorey724/Spellnado).

The working corpus (full word list, generator, unpublished future storms)
stays in the private repo. This tree only has storms whose Chicago date
has already arrived.

| File | What |
|---|---|
| `today.json` | America’s Chicago-date storm (letters, eye, frozen answers, hints) |
| `history/YYYY-MM-DD.json` | That calendar day’s file |
| `history/index.json` | Dates published so far |

Timezone `America/Chicago`. Epoch `2026-09-01`.

The iOS app fetches `today.json` and caches it. No token. Do not put
scores or player history here.
