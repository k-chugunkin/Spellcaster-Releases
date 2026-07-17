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
