# Randomizer-PAW
A fork of the [Randomizer](https://github.com/FortyTwoFortyTwo/Randomizer) SourceMod plugin, with additonal optional features:
- Pickup Any Weapon (PAW) functionality - anyone can pick up any weapon off the ground regardless of class
- The ability to create your own weapon loadout which gets applied when you spawn/resupply

Please note that this project is **currently a work-in-progress**, functionality listed in this readme is not guaranteed to be final and might be broken or completely missing.

## ConVars
Same as Randomizer, plus:
- `randomizer_paw`: Allow/Disallow players to pick up any weapon off the ground
  - Make sure you have `randomizer_droppedweapons` set to 1
- `randomizer_custom`: Allow/Disallow players to customize their own weapon loadouts
  - Setting this to 1 will disable `randomizer_weapons`

## Commands
Same as Randomizer, plus:
- `sm_loadout`: Opens a menu where players can customize their own weapon loadouts
