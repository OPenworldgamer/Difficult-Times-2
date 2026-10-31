# Difficult Times 2 — MCT Settings

Recommended **Mod Configuration Tool (MCT)** settings for the **Difficult Times 2** Total War: WARHAMMER III mod collection.

**Steam Workshop collection:**  
https://steamcommunity.com/sharedfiles/filedetails/?id=3790122430

## Download

### [Download Difficult Times 2 MCT Settings (.ZIP)](https://github.com/OPenworldgamer/Difficult-Times-2/archive/refs/heads/main.zip)

The ZIP contains `mct_registry.lua` together with these instructions.

## Installation

1. Download the ZIP above and extract it.
2. Subscribe to and enable the Difficult Times 2 collection, including MCT.
3. Launch Total War: WARHAMMER III at least once with MCT enabled, then close the game.
4. Press **Win + R**.
5. Paste:

   ```text
   %APPDATA%\The Creative Assembly\Warhammer3\scripts\
   ```

6. Back up your existing `mct_registry.lua` if you want to preserve your current MCT settings.
7. Copy the downloaded `mct_registry.lua` into that folder and replace the existing file.
8. Launch the game and check the MCT menu.
9. Start a **new campaign**.

## Important

Install the preset **before starting a new campaign**. MCT settings can be stored in campaign saves, so replacing the registry later may not fully change an existing campaign.

Replacing `mct_registry.lua` also replaces your global MCT configuration. Keep a backup if you use different settings for other mod lists.

## What is included

This shared preset was cleaned before publishing. It keeps the MCT entries used by the Difficult Times 2 setup and removes old campaign snapshots and unrelated records from previously used mods.

The preset includes the intended custom settings for:

- Dynamic Difficulty
- Progressively Harder Battles
- Progressively Harder Expansion
- Map Replacer Framework
- Hecleas AI declaration-of-war settings
- MCT itself
