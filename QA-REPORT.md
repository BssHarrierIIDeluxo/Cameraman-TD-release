# Public release verification — 2026-10-24

Artifact: script.lua, 5,108,360 bytes.
SHA-256: 63238f53df299998a1506c9ecaf3fa810159404cf23602671dc7c894952a0869
Git blob SHA-1: d90940cef5209b50086fbbcc2be686f1b512f221

All 36 protected modules recovered the exact original Luau source in a local Lua 5.1 round-trip check. The original source checks and earlier broad beta QA remain applicable to that recovered source.

The full public installer passed isolated checks for all 37 modules, both complete PNGs, automation disabled on a fresh installation, preservation of user settings, no writes on repeat installation, and rollback after a simulated filesystem error. These checks use a simulated filesystem and a stubbed UI launch.

The actual 5.1 MB local bundle compiled and launched in Real on Windows in 5.76 seconds. The exact published raw URL then launched the hub in Real in 7.96 seconds. A round/server change interrupted the tool response, but the successful launch proof was persisted and read back afterward. The existing Easy farm continued; the console returned zero errors/warnings after the HTTP launch.

Focused checks against the installed protected modules passed: Hunt goal statistics/pool (28), Hunt state and routing (14), threshold summoning (14), Home queue/journal (19), profiles (13), preflight (11), and six pause invariants. No user settings were reset by these isolated tests.

Unverified: physical phones/touch devices, executors other than Real, every map/difficulty/loadout, real Halloween purchases/opening during this run, actual rare-target drops, and external Discord delivery. No claim of exhaustive coverage or guaranteed source secrecy is made.
