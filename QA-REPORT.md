# Cameraman TD v0.4 beta — verification,25 October2026

Artifact: script.lua, 5,522,221 bytes.
SHA-256: ce595ca4b50d5f0363007b8d0eda4350c7bca0b6973f2202f52fffe39210c93b

Beta readiness: ready for the tested Real/Windows environment, with the compatibility limits below. This is not a guarantee that every device, map and game update is bug-free.

## Fresh validation

- All50 project modules passed Real Luau analysis with zero errors/warnings. Bundled third-party WindUI compiled during the actual installer launch.
- All50 obfuscated project modules recovered the exact original Luau source in the local round-trip check.
- The installer passed isolated tests for all51 modules and both full PNG payloads, automation off on clean installation, preserving user settings, no writes on identical repeated install and rollback after a simulated write failure.
-31 functional suites passed against installed protected modules: AFK controller; match routing/voting/speed/skip/replay; avatars; session goals/summon guards; Halloween reward/candy/crate rules; Home queue/journal; multi-target Hunt, budgets, counters and alerts; recording/sales/selection/backups/equipment; master pause; notification filters; reversible FPS Boost/Anti-AFK listeners; preflight/profiles/daily quests; Easy/Normal catalog binding; sale confirmation; threshold/reserve; toast geometry; grid boundaries; webhook with simulated HTTP; text layout and current typography.
-11 live tabs visited and all30 sections expanded/collapsed. The built installer launched in Real: beta label present,30 sections initially collapsed, Boar fresh-install default and no changed saved user preferences.
- Initial legacy test expectations for old typography and unisolated graphics pause were corrected. The summon diagnostic fixture now provides the session dependency used by history. No network warning from that fixture remains. Failed initial evidence is retained locally.
- Close confirmation separately passed three frame-sampled fades without height/text-offset changes, actual close and reopening.

## Prior live integration evidence retained

Verified library Easy and Normal routes completed full winning matches. Macro sale recording/playback and checkpoint continuation were exercised in complete matches. Explicit required-unit equipment was confirmed natively. Daily quest/pass rewards were confirmed. AFK World entry,5 native coins in60seconds, timed exit and return to Easy farming passed.

## Remaining checks

Physical phones/Delta/Android, every map/loadout, overnight recovery and future game updates remain unverified. Real Halloween candy spending/crate opening and a rare Hunt target drop were not performed during this release check. Spending/reward edge cases were tested with simulated responses. Webhook HTTP behavior was simulated; no Discord messages were sent.

## Distribution

Existing preferences, account macros and pause state are preserved. New installations start gameplay automation off. Boar is the default portrait, and sections start collapsed. Only bundled code and two avatar assets are distributed; saved user JSON, credentials and personal recordings are excluded. Development source is retained separately. Previous release commit is available for rollback.
