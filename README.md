# Cameraman TD — v0.3 beta

By **@BssHarrierIIDeluxo**.

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
