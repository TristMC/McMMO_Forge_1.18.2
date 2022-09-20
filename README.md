# McMMO_Forge_1.18.2
McMMO for modded tools in version 1.18.2 (install this too https://www.curseforge.com/minecraft/bukkit-plugins/nbt-api/download/3672335 or it won't work.)

This is a modification of nossr50's McMMO plugin that changes five functions in ItemUtils: isSword(), isHoe(), isShovel(), isAxe(), and isPickaxe().

It uses NBTAPI to convert the item in hand to an NBT item, and then it converts that NBT item to a string.  The five functions modified above read that converted string to see if it contains keywords like "pick" or "shovel" to decide what tool it will be treated as.  
