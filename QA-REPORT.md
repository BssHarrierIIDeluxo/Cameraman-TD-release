# Public release verification — 2026-10-24

Artifact: script.lua, 5,169,541 bytes.
SHA-256: a31ee49d09c4ba6f4018b1c25fb635905ed4f63751bcafdf7f170a38275afc53
Git blob SHA-1: c127cf592e3a930e2d59e01ec0925afd4eec6b3c

All 38 protected modules recovered the exact original Luau source in a local Lua 5.1 round-trip check. The original source checks and earlier broad beta QA remain applicable to that recovered source.

The full public installer passed isolated checks for all 39 modules, both complete PNGs, automation disabled on a fresh installation, preservation of user settings, no writes on repeat installation, and rollback after a simulated filesystem error. These checks use a simulated filesystem and a stubbed UI launch.

The updated 5,169,541-byte protected bundle launched through the exact published raw URL in Real on Windows in 7.28 seconds. The successful launch proof was persisted and read back afterward despite an interrupted tool response. The original macro selection and Easy farming remained enabled; the console returned zero errors/warnings after the HTTP launch.

Ready-made macro update: the new protected bundle loaded in Real, and its installed catalog modules passed the same 39 logic assertions and 48 layout assertions as the source version. The catalog UI's Select action selected the imported macro. A fresh live Toilet City Easy match using that imported template completed all 45/45 actions and ended Won. The testing account differs from the original recording author. The prior macro selection and farming were restored afterward. Card layouts passed at widths 260/540 in Russian and English; this is not a physical phone test.

Focused checks against the installed protected modules passed: Hunt goal statistics/pool (28), Hunt state and routing (14), threshold summoning (14), Home queue/journal (19), profiles (13), preflight (11), and six pause invariants. No user settings were reset by these isolated tests.

Unverified: physical phones/touch devices, executors other than Real, every map/difficulty/loadout, real Halloween purchases/opening during this run, actual rare-target drops, and external Discord delivery. No claim of exhaustive coverage or guaranteed source secrecy is made.
