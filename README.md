# Cameraman TD — v0.3 beta

By **@BssHarrierIIDeluxo**. Public protected distribution.

## Launch

Open CAMERAMAN TD, then run:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/BssHarrierIIDeluxo/Cameraman-TD-release/main/script.lua"))()
```

The first launch installs the bundled modules and avatar artwork into the executor workspace. Existing settings and macros are preserved; new installations start with gameplay automation off. Record your own macro with your own units before enabling farming. No account macros or personal settings are included.

Tested with **Real on Windows**. Other executors, Android/touch devices, and future game updates require separate verification. The hub uses executor filesystem functions, `getcustomasset`, `getloadedmodules`, `getconnections`, and `queue_on_teleport`. WindUI uses its official icon provider; Roblox supplies game artwork.

## Protection and credits

Based on Prometheus by Elias Oelschner, https://github.com/prometheus-lua/Prometheus

Own modules use string encryption and VM obfuscation around the native Luau source. This is not Luraph. Obfuscation makes the distributed code harder to read; it cannot guarantee source secrecy once executed on a client. The original development source is maintained separately.

WindUI by Footages is bundled under the MIT license. See [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt). No additional redistribution license is granted for the project's own code.

## Verification

All 36 protected modules were checked for exact source recovery. The installer passed isolated checks for all 37 modules, both image payloads, safe defaults, settings preservation, repeat installation, and rollback after a simulated write failure. The protected local bundle launched in Real and continued the existing Easy farm without console errors; focused Hunt, pause, profile, preflight, and Home journal checks passed.

This does not certify every map, every executor, real-money/game-currency purchases, or physical phone interaction. No external Discord messages were sent during these checks.
