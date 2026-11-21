# Product roadmap

This roadmap is provisional and will be prioritized using feedback from Cyberpunk 2077 mod users.

## Phase 0 — Validate demand (current)
- Publish the visual prototype and four screenshots.
- Collect pain points from at least 20 players who already mod the game.
- Ask which one feature would make them use a new tool rather than an existing manager.
- Track **unique feedback**, GitHub stars, issues, and demo visits separately; do not equate stars with actual product demand.

## Phase 1 — Safe read-only MVP
- Windows path selector and game directory recognition.
- Detect supported mod folders; document limitations.
- Inventory archive / RED4ext / CET / redscript paths when applicable.
- Report actual installed files, with error handling and a reproducible test suite.
- No file modification in this phase.

## Phase 2 — Trusted diagnostics
- Maintain an explicit rules registry with sources and tested version ranges.
- Detect verifiable missing dependencies; warn when a dependency cannot be checked.
- Differentiate hard conflicts, suspected conflicts, and informational notices.
- Export JSON and human-readable reports with sensitive paths redacted by default.

## Phase 3 — Backup and restore
- User-selectable, clearly scoped backups.
- Transactional writing, integrity checks, and recovery after interruption.
- Explicit confirmation before modifying game folders.
- Test with clean and intentionally corrupted copies, not only a production install.

## Phase 4 — Desktop releases
- Package and sign a Windows release where feasible.
- Publish SHA-256 checksums, release notes, and reproducible build instructions.
- Verify licensing and rights to assets or third-party integrations.

## Out of scope for the prototype
Scanning real files, installing mods, automatic conflict resolution, and backup or restore of real game data.
