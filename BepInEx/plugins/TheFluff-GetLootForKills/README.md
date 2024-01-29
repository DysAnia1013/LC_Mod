A mod that makes enemies drop loot after death. All modded items and modded mobs, including all of the vanilla mobs and items, should be configurable after you start a lobby. It needs this to know what items and mobs exist after loading into the ship. To config the items all you need to do is give the item name, min item amount to drop, max item amount to drop, min value of drop, max value of drop, and the chance of the item dropping. 

The following example drops a random item with a chance to drop 0-3 of a random item of a value between 0-100 with a 100% chance of dropping the random items.
Example: RANDOM, 0, 3, 0, 100, 1000 

The example below this will drop a vanilla item called Flask with a chance to drop 1-1 of a value between 50-150 with a 10% chance of dropping the flask item.
Example: Flask, 1, 1, 50, 150, 100

This last example will drop nothing.
Example: NONE

If you want to drop a random item without actually configging it just leave the line empty.
