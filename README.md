# Cameraman TD — v0.3 beta

By **@BssHarrierIIDeluxo**. Public protected distribution.

## Launch

Open CAMERAMAN TD, then run:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/BssHarrierIIDeluxo/Cameraman-TD-release/main/script.lua"))()
```

The first launch installs the bundled modules and avatar artwork into the executor workspace. Existing settings and macros are preserved; new installations start with gameplay automation off. Personal account recordings and settings are not distributed.

## Ready-made macros

Open **Macro → Ready-made Macros**. The first template is **Toilet City · Easy**, requiring one equipped **Speakerman**. It contains 45 actions and 15 separate placements. Choose **Add to My Macros** to import it, then **Select This Macro** while farming/recording is stopped. Selection does not start farming or change speed. Choose the required map and Easy difficulty before starting.

The template resolves the exact equipped Speakerman inventory ID on your own account; it does not contain the recording author's inventory IDs. Missing or unequipped units block import. Existing strict ownership, map, loadout and speed checks still apply. Repeated imports reuse an unchanged copy and preserve user-edited recordings. You can also record your own macro.

Tested with **Real on Windows**. Other executors, Android/touch devices, and future game updates require separate verification. The hub uses executor filesystem functions, `getcustomasset`, `getloadedmodules`, `getconnections`, and `queue_on_teleport`. WindUI uses its official icon provider; Roblox supplies game artwork.

## Protection and credits

Based on Prometheus by Elias Oelschner, https://github.com/prometheus-lua/Prometheus

Own modules use string encryption and VM obfuscation around the native Luau source. This is not Luraph. Obfuscation makes the distributed code harder to read; it cannot guarantee source secrecy once executed on a client. The original development source is maintained separately.

WindUI by Footages is bundled under the MIT license. See [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt). No additional redistribution license is granted for the project's own code.

## Verification

All 38 protected modules were checked for exact source recovery. The installer passed isolated checks for all 39 modules, both image payloads, safe defaults, settings preservation, repeat installation, and rollback after a simulated write failure. Catalog checks passed 39 assertions, including two account bindings, missing/unequipped units, collision preservation and no automatic start. Card layout checks passed 48 assertions at widths 260/540 in Russian/English. See [QA-REPORT.md](QA-REPORT.md) for runtime evidence and limits.

This does not certify every map, every executor, real-money/game-currency purchases, or physical phone interaction. No external Discord messages were sent during these checks.
