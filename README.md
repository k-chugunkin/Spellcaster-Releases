# Spellcaster v2.2.0 Release Notes
## Application
### Minor Changes
-	added restriction to launch more than 1 instance of the app on one machine
-	unserialized DSharp events no longer display in the Log

## Commands
-	`/origin species` restructured to work with options lacking image
-	restructured `/armor` and `/weapon` - redundent code removed, minor formatting for better readability
-	restructured `/gear adv` and `/random gear` commands to accommodate Source
-	`private static readonly string invisibleSpace` removed as redundent
-	new command added: `/class fighter arcane_shot`

## Content
-	Arcana Unleashed (2026): Backgrounds, Feats, Spells, Subclasses, Magic Items (exc. Evolving) added.
-	Standard Armor descriptions added
-	Bastions from "Eberron: Forge of the Artificer (2025)" added
-	Bastions from "Ravenloft: The Horrors Within (2026)" added
-	"Icewind Dale: Rime of the Frostmaiden (2020)" adventuring gear added

### Minor Changes
-	thumbnail for Genie Robe added
-	DndBeyond Drop, August 2026 added
-	Drops Errata (as of August 2026) implemented
-	Source added for Adventuring Gear, Bastions, Speicies, Spells

## Bugs fixed:
-	`/origin species Dhampir`: "Image not found. Please check the path." fixed (see Commands category)

# Spellcaster v2.0.1 Release Notes
## Application
### Minor changes
-	"House Rules" thread link in `?gamepolicy` has changed due to remodelling of the Discord server
-	added link to "Release Notes" in About window.
-	converted Background images to .jpeg reducing size by 28.4 MB

## Commands
-	Restructured `/class bard features` to the liking of Artificer for image attachment
-	Restructured `/class paladin features` to the liking of Artificer for image attachment
-	Fix: `/roll` command returning "Invalid number of dice" when entered A/D for number of dice
-	`/gear poison` is now limited to "Dungeon Master" role only
-	`/origin background` now includes source

## Content
-	added all subclasses from "Ravenloft: The Horrors Within (2026)"
-	added all background from "Ravenloft: The Horrors Within (2026)"
-	added all subclasses from "Forgotten Realms: Heroes of Faerun (2025)"
-	added all background from "Forgotten Realms: Heroes of Faerun (2025)"
-	added all background from "Eberron: Forge of the Artificer (2025)"


# Spellcaster v2.0.0 Release Notes
## Application
- 	New UI
- 	Automatic Update
- 	Explicit version control

### Optimization
- 	Restructured `/random magicitem` and `/random hoard` to include DndBeyond Drops
- 	Magic Items with rarity "varies" have been split into several items with relevant rarity. `/magic_item` has been adjusted to retain images and thumbnails population
- 	optimized `/magicitem` and `/random magicitem` commands to call for an external MagicItemInvoker function
- 	restructured `BotCommands` class for better "Commands in DMs" control implementation
- 	trimmed `using` across various classes

## Content
- 	added species from "Eberron: Forge of the Artificer (2025)"
-	added species from "Ravenloft: The Horrors Within (2026)"
