# teet

A toolkit for Twilight's Eve Evo RPG: a static optimization dashboard plus
preserved personal notebooks and scripts. No official affiliation with the game
is implied, and no current game-data accuracy is claimed.

## Scope and sources

- Read `README.md` before editing.
- Read the [snowball principles](https://snowball-projects.github.io/principles/)
  before product or data changes.
- Keep the original notebooks, scripts and history as a record of the founder's
  personal project. Do not remove historical material because the dashboard
  supersedes an entry point.

## Development and verification

- Run `npm test`, `python3 -m unittest discover -s tests -v`, and
  `npm run build`.
- Keep web assets local; no CDN runtime dependencies.

## Interface behavior

- The public dashboard is static. Optimization is exact for the documented
  linear weighted model and constraints; it is not a combat simulator.
- Check infeasibility, class and dungeon eligibility, and selected totals.
- No credentials or telemetry.

## Desktop automation

- Automation is Windows-only and started explicitly through the loopback
  companion. The public site cannot control a game.
- Never start keyboard or mouse automation during development or tests.
- Preserve Host/Origin checks, bounded validated commands, foreground-game
  checks, stop controls and synthetic-only tests.

## Publication

- Publish only a verified build. Verify the workflow and live assets before
  claiming deployment; do not force-push.

## Stewardship

- Write `teet` and `snowball` in lowercase.
- Original software is MIT; game data and third-party materials keep their own
  rights.
- Do not add AI-builder labels or production credits to public copy.
- `CLAUDE.md` imports this file. Keep operational detail in docs rather than
  duplicating agent instructions.
