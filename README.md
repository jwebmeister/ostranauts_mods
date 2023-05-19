# ostranauts_mods

My collection of mods for the game "Ostranauts" by Blue Bottle Games.

![Alt text](./StarterShipPlusMod/images/ships/Question.png?raw=true "Question")

## Install instructions
- Copy all files and folders into your Ostranauts "Mods" folder.
    - Check your game's Options->Files screen to show you where your Mods folder should be.
    - e.g. for my install, "loading_order.json" should be located "Steam\steamapps\common\Ostranauts\Ostranauts_Data\Mods\loading_order.json".
- NOTE: you may run into issues if the installed game version differs from the mods specified game version within "mod_info.json".

## Uninstall instructions
- **Do not delete "loading_order.json"**.
- Delete all *other* files and folders within your Ostranauts "Mods" folder.
- Open "loading_order.json" in notepad and change the relevant text:
    - Old: 
        - `"aLoadOrder" : ["core", "mod1", "mod2", "..."],`
    - New: 
        - `"aLoadOrder" : ["core"],`

## Version history & features
### Added Loot Mod 
- v0.1
    - Game version: 0.11.0.11
    - Adds items to loot table to allow them to be spawned from console, mainly loose floors and walls that were missing.
### Free Traits Mod 
- v0.1
    - Game version: 0.11.0.11
    - Changes cost of skills and traits so that selection during character creation adds zero years to the player characters age.
### Starter Ship Plus Mod 
- v0.1
    - Game version: 0.11.0.11
    - Changes the starting selection of ships to high-tier ships, with no mortgage.
