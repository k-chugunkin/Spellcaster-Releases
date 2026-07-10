# Spellcaster v1.4 Release Notes (OSX ARM)
### New items
- 	added "?v" - for current version	
- 	added spells from "Sword Coast Adventurer's Guide (2015)"
- 	added [spells, magic items] from DndBeyond Drops (June 2026)
- 	added [magic items, feats] from DndBeyond Drops (July 2026)
- 	all statblocks from PHB (2024) have been added

### Minor fixes
- 	"Circle of Power" spell description corrected
- 	All spells avaiable to Artificer class have been marked as such (excl. Subclass-only spells)
- 	Replaced "Amulet of the Planes" table with image for better readability

	
### Optimizations
- 	Restructured `/random magicitem` and `/random hoard` to include DndBeyond Drops
- 	Magic Items with rarity "varies" have been split into several items with relevant rarity. `/magic_item` has been adjusted to retain images and thumbnails population
- 	optimized `/magicitem` and `/random magicitem` commands to call for an external MagicItemInvoker function
- 	restructured `BotCommands` class for better "Commands in DMs" control implementation
- 	trimmed `using` across various classes
