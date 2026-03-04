# NaowhUIBypass

A companion addon that unlocks NaowhUI without requiring a third-party token.

NaowhUI gates certain features (profile setup, installer, options) behind a time-limited token generated from an external website. This addon removes that requirement entirely.

## Installation

1. Download the [latest release](https://github.com/mkccl/NaowhUIBypass/releases/latest)
2. Extract the `NaowhUIBypass` folder into your `World of Warcraft/_retail_/Interface/AddOns/` directory
3. The folder structure should look like:
   ```
   Interface/AddOns/
   ├── NaowhUI/
   └── NaowhUIBypass/
       ├── NaowhUIBypass.toc
       └── NaowhUIBypass.lua
   ```
4. Restart the game or reload the UI (`/reload`)

NaowhUI must be installed for this addon to work. You can get it from [CurseForge](https://www.curseforge.com/wow/addons/naowhui). No configuration needed — all gated features are unlocked automatically on load.
