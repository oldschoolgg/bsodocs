# Invention



Invention is a skill where you disassemble items to get materials, and then use those items to make inventions. Inventions are items which give you boosts and perks, at the cost of materials. You need level 90 Crafting to train Invention.

All aspects of the Invention skill are accessed using `/invention`

## Disassembling

* Use `/invention disassemble` , select the item you want to disassemble.
* You will disassemble those items into materials. The materials you get are dependent on the _group_ the item is in. For example, items in the _Food_ group will give _Organic_ materials at a 100% ratio. However, some items are obviously more valuable, like a Shark vs a Trout.
* Use `/invention materials` to see what materials you own. Note: They are not tradeable, and cannot be transferred to other players.
* The difference between items (e.g. Shark vs Trout) is their _level_, a Shark has a higher level - and the level determines the _Junk Chance_ of the item, so a Shark is much less likely to become junk. Everything has a chance (high or small) of becoming junk.
* The amount of XP you get from disassembly is dependent on the _level_ of the item, and your invention level.



## Research

* Now you have materials!&#x20;
* Use `/invention research` to research with a particular material type, effectively sending your minion to use this material and try to research and discover things it can make with it.
* If successful, you will discover a _blueprint_ which uses the material that you are researching with. For example, if a particular invention uses _sharp_ materials, and you're researching with _sharp_ materials, you have a chance to unlock the blueprint for it.
* Blueprints only need to be unlocked once, and they grant you the ability to create that invention.

## Inventing

* Now you have materials, and the blueprint for the Invention you want!
* Use `/invention invent` to create the particular invention you want.
* Inventions cost _materials_ to make, and some inventions cost items to make. These are one-time costs.
* Once you have made an invention, if its one that works from the bank, its ready to go! If it's one that needs to be equipped (like Silverhawk boosts), then you'll need to equip them.
* Inventions cost a small amount of _materials_ each time you use them.
* You can use `/config user toggle_invention invention:name` to temporarily toggle a invention off, if you don't want to use it.
* That's it! Your inventions will never break or need to be created again. You cannot trade inventions.

## Inventions

| Invention (level)                                 | Effect                                                                                                                                | Materials \[Weight]                           |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| Superior Bonecrusher (70)                         | 25% bonus xp over Gorajan Bonecrusher                                                                                                 | Pious\[5] Sharp\[1] Magic\[4]                 |
| Dwarven Toolkit (80)                              | 35% speed boost to disassembly                                                                                                        | Dwarven\[8] Metallic\[2]                      |
| Superior Inferno Adze (80)                        | Automatically burns logs chopped and smelts ores mined. Costs nothing to use.                                                         | Sharp\[3] Base\[3] Metallic\[1] Magic\[3]     |
| Superior Dwarf Multicannon (80)                   | 37%-65% speed boost to pvm when cannoning                                                                                             | Strong\[4] Heavy\[2] Metallic\[4]             |
| Mecha Rod (85)                                    | 45% speed boost to fishing                                                                                                            | Flexible\[5] Organic\[3] Strong\[2]           |
| Master Hammer and Chisel (90)                     | 45% speed boost to crafting                                                                                                           | Simple\[3] Sharp\[2] Metallic\[2] Swift\[3]   |
| Quick Trap (90)                                   | 25% speed boost to box-trap hunting                                                                                                   | Precious\[1] Magic\[6] Organic\[3]            |
| Silverhawk Boots (90)                             | 1.9x speed boost to agility, up to 36k agility xp/hr _fully_ passive                                                                  | <p>Swift[5] Protective[1] Dextrous[4]<br></p> |
| Mecha Mortar (95)                                 | 45% speed boost to herblore                                                                                                           | Organic\[8] Metallic\[2]                      |
| Portable Tanner (95)                              | Tans hides you get from PvM                                                                                                           | Metallic\[2] Plated\[3] Organic\[5]           |
| Drygore Saw (105)                                 | 40% speed boost to construction                                                                                                       | Drygore \[7] Sharp \[3]                       |
| Arcane Harvester (110)                            | Increases farming yield by 20%                                                                                                        | Organic\[5] Magic\[5]                         |
| Clue Upgrader (110)                               | Chance to upgrade Beginner-Elite clues to next tier when received as loot in PvM.                                                     | Treasured\[8] Metallic\[2]                    |
| Abyssal Amulet (120)                              | Boosts runecrafting by varying amounts depending on the rune                                                                          | Magic\[4] Metallic\[2] Treasured\[2]          |
| [RoboFlappy](../custom-items/pets.md#perks) (120) | Provides extra loot from minigames, like the discontinued [Flappy](../custom-items/pets.md#discontinued-pets) but with material costs | Magic\[4] Organic\[2] Metallic\[4]            |

## Tips

* There are bank filters for every material to show all items in your bank which give a particular material. For example, if you want _sharp_ materials, you could do `/bank filter:sharp-material` to see all items you can disassemble to get some
* If your goal is just to train Invention, or to reach level 120, you can just disassemble cheap items! You don't have to disassemble expensive, valuable items.
* There's a collection log for Invention, showing all the Inventions, and the pet it comes with.

## Boosts

### Disassembly Boosts

#### Master capes Disassembly Boosts

Master capes give a 5% junk chance reduction for a group relating to their skill. For example, the Mining master cape reduces the junk chance of the Ores group by 5% - meaning that when you're disassembling items from the Ores group, you'll be getting effectively 5% more materials!

| Master cape              | Group That It Reduces |
| ------------------------ | --------------------- |
| Smithing master cape     | Metals                |
| Mining master cape       | Ores                  |
| Woodcutting master cape  | Logs                  |
| Firemaking master cape   | Ashes                 |
| Herblore master cape     | Potions               |
| Farming master cape      | Organic               |
| Cooking master cape      | Food                  |
| Fishing master cape      | Raw Food              |
| Construction master cape | Planks                |
| Fletching master cape    | Bows, Unstrung Bows   |
| Crafting master cape     | Jewelry               |
| Runecraft master cape    | Talisman, Runes       |
| Ranged master cape       | Projectiles           |
| Attack master cape       | Swords, Longswords    |
| Strength master cape     | Blunt Weapons, Maces  |
| Defence master cape      | Shield, Defender      |
| Magic master cape        | Magic                 |
| Prayer master cape       | Bones                 |

#### Other Disassembly boosts

| Name                        | Boost                  |
| --------------------------- | ---------------------- |
| Dwarven toolkit (Invention) | 35% faster disassembly |
| Invention master cape       | 5% faster disassembly  |
| Invention master cape       | 5% extra materials     |







