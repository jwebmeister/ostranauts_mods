# ostranauts_mods

My collection of mods for the game "Ostranauts" by Blue Bottle Games.

![Alt text](./_docs/Question.png?raw=true "Question")

## Install instructions
- Download latest release from https://github.com/jwebmeister/ostranauts_mods/releases/latest
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
- Adds items to loot table to allow them to be spawned from console, mainly loose floors and walls that were missing.
- Version history
    - v0.2
        - Game version: 0.12.0.4  (also tested 0.12.0.6)
        - Removed all items from mod except the loose door, other items were added in the games update.
    - v0.1
        - Game version: 0.11.0.11
### Free Traits Mod 
- Changes cost of skills and traits so that selection during character creation adds zero years to the player characters age.
![Alt text](./_docs/FreeTraitsMod.jpg?raw=true "Free Traits Mod")
- Version history
    - v0.1
        - Game version: 0.11.0.11  (also tested 0.12.0.6)
### Starter Ship Plus Mod 
- Changes the starting selection of ships to high-tier ships, with no mortgage.
![Alt text](./_docs/StarterShipPlusMod.jpg?raw=true "Free Traits Mod")
- Version history
    - v0.3
        - Game version: 0.12.0.6
        - Removed Question ship, and unnecessary images (added in games update).
    - v0.2
        - Game version: 0.12.0.4  (also tested 0.12.0.6)
        - Added "bShipOwned" : true, to each ship.
    - v0.1
        - Game version: 0.11.0.11
