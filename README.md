# Cameraman TD — v0.4 beta

By **@BssHarrierIIDeluxo**.

## Launch

Open CAMERAMAN TD, then run:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/BssHarrierIIDeluxo/Cameraman-TD-release/main/script.lua"))()
```

First-time users start with the Boar avatar, collapsed sections and gameplay automation off. Existing settings, avatar choices and personal macros are preserved. Sections start collapsed when the menu loads; expand the ones you need.

## Features

- Home activity, next actions, session metrics, journal and Stop Everything.
- Auto Join, map/mode selection, wave skip limits, replay and game speed controls.
- Macro recording/playback with placements, upgrades and sales; sharing, backups and required-unit equipment.
- Separate Macro Library with verified Toilet City Easy and Normal routes, requirements and route previews.
- Auto Summon, coin threshold/reserve and multi-target Hunt with roll/coin limits and banner alerts.
- Daily quest rewards, session statistics and farm goals.
- Halloween pass/rewards, event quests and candy-based crate controls.
- AFK World entry, confirmed rewards, session timer and return to previous farming.
- Themes, Boar/Taiga/custom avatars, larger interface mode, reduced motion and contextual explanations.
- Anti-AFK, reversible FPS Boost and optional webhook controls.

## Ready-made macros

Open **Macro Library**, expand the catalog, review the requirements/preview and add the chosen route to My Macros. Selection does not start farming. Easy requires one equipped Speakerman; Normal requires one equipped Large Cameraman. Inventory IDs bind to your own units. No personal account recordings or settings are distributed.

## Compatibility

Tested with **Real on Windows**. Delta/Android and physical touch devices require separate verification. The executor must provide filesystem functions, `getcustomasset`, `getloadedmodules`, `getconnections` and `queue_on_teleport`. Game updates may change native behavior.

See [QA-REPORT.md](QA-REPORT.md) for validation and remaining checks. Third-party notices are in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).
