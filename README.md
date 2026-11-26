# Operation Insight

Vanilla+ **1PP PVP** DayZ server configs for Chernarus — survival-first, raid weekends, Insight Cell jobs, one custom trading post.

- **Discord:** https://discord.gg/EW9ds9Vq8Y
- **Site:** https://sk3tch-dev-ux.github.io/operation-insight/

## Repo layout

| Path | Purpose |
|------|---------|
| `docs/` | GitHub Pages site |
| `server/` | Live-oriented configs (mission Expansion settings, profiles, EditorFiles, economy hooks) |

Secrets (admin passwords, Highwatch API keys, player ATM/permission dumps) are **not** committed.

## Highlights

- Raid window: Fri 18:00 → Mon 06:00 (server local)
- Spawns: Svetloyarsk, Berezino, Elektrozavodsk, Chernogorsk (2 points each)
- Single safezone / trader zone at the Insight Trading Post (`sk3tchTrader.dze`)
- Insight quest chain + board jobs under `server/profiles/ExpansionMod/Quests`

## Applying configs

Copy the relevant trees into your Highwatch/DayZ server mission + `profiles` folders, then restart. Prefer diffing against your live server before overwriting economy XML that CE may have rewritten at runtime.
