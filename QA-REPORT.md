# Public release verification — 2026-10-24

Artifact: script.lua, 5,184,986 bytes.
SHA-256: 7a149ff457e282c064105c9d1b36c1ee06c99986da0e97d1020a0927f041472e
Git blob SHA-1: bbaad154832e6718c08c931f327f991a93300cf2

All 39 protected modules recovered the exact original Luau source in a local Lua 5.1 round-trip check. The original source checks and earlier broad beta QA remain applicable to that recovered source.

The full public installer passed isolated checks for all 40 modules, both complete PNGs, automation disabled on a fresh installation, preservation of user settings, no writes on repeat installation, and rollback after a simulated filesystem error. These checks use a simulated filesystem and a stubbed UI launch.

The updated 5,169,541-byte protected bundle launched through the exact published raw URL in Real on Windows in 7.28 seconds. The successful launch proof was persisted and read back afterward despite an interrupted tool response. The original macro selection and Easy farming remained enabled; the console returned zero errors/warnings after the HTTP launch.

Ready-made macro update: the new protected bundle loaded in Real, and its installed catalog modules passed the same 39 logic assertions and 48 layout assertions as the source version. The catalog UI's Select action selected the imported macro. A fresh live Toilet City Easy match using that imported template completed all 45/45 actions and ended Won. The testing account differs from the original recording author. The prior macro selection and farming were restored afterward. Card layouts passed at widths 260/540 in Russian and English; this is not a physical phone test.

Focused checks against the installed protected modules passed: Hunt goal statistics/pool (28), Hunt state and routing (14), threshold summoning (14), Home queue/journal (19), profiles (13), preflight (11), and six pause invariants. No user settings were reset by these isolated tests.

Unverified: physical phones/touch devices, executors other than Real, every map/difficulty/loadout, real Halloween purchases/opening during this run, actual rare-target drops, and external Discord delivery. No claim of exhaustive coverage or guaranteed source secrecy is made.

Text-layout regression fix: 15 focused checks passed for narrow startup width, hidden-page visibility, restore, language/font/scale changes, multiline descriptions, native geometry preservation, unrelated custom UI and cleanup. Six live page visits (Home/Main/Halloween/Macro/Settings/Home) checked 144 native label appearances with no vertical-text findings. The final public HTTP bundle launched in 10.94 seconds and the console returned no problems. A discarded experiment with fixed heights was rolled back and was never published; the final implementation preserves native automatic sizing.
