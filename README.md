# Difficult Times 2 — MCT Settings

Recommended **Mod Configuration Tool (MCT)** settings for the **Difficult Times 2** Total War: WARHAMMER III mod collection.

**Steam Workshop collection:**  
https://steamcommunity.com/sharedfiles/filedetails/?id=3790122430

## Download

**[Download mct_registry.lua](https://raw.githubusercontent.com/OPenworldgamer/Difficult-Times-2/main/settings/mct_registry.lua)**

If the link opens the file as text, save it as `mct_registry.lua`.

## Installation

1. Subscribe to and enable the Difficult Times 2 collection, including MCT.
2. Launch Total War: WARHAMMER III at least once with MCT enabled, then close the game.
3. Press **Win + R**.
4. Paste:

   ```text
   %APPDATA%\The Creative Assembly\Warhammer3\scripts\
   ```

5. Back up your existing `mct_registry.lua` if you want to preserve your current MCT settings.
6. Replace it with the downloaded Difficult Times 2 `mct_registry.lua`.
7. Launch the game and check the MCT menu.
8. Start a **new campaign**.

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
