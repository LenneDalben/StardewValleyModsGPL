# (CP) Artisan Equipment for Sale

Have you ever been rolling in the gold, flooded with cash, or just had some extra money, but you can't craft mayo machines because you don't have enough earth crystals, and you thought to yourself, "it would be great if I could just buy some mayo machines with all this money"? Well, now you can!

With this mod, the shop owners in the valley (and in the desert) will sell artisan equipment after you have unlocked it, every Thursday, and only to their friends.

Translations are welcome! You can submit either the language.json to me or the strings in another language for all the orders and I will incorporate it into the mod. See more information on the <a href="https://stardewvalleywiki.com/Modding:Translations">wiki</a>.

German translation courtesy of Nexus user kupiqo.


||Compatibility - Integration||

For the machines Marlon sells, there's built-in integration. If you use <a href="https://www.nexusmods.com/stardewvalley/mods/2569">Befriend Marlon and Gunther</a> or <a href="https://www.nexusmods.com/stardewvalley/mods/7018">Make Marlon Real</a>, there is a friendship requirement. If you use none of those mods, there's a different requirement.


||Configuration||

* Artisan Equipment Letter Only Sends Once: Choose whether to receive the letter reminder only once (default: false). This means the letter repeats every week on Thursdays.
* * NOTE: if you set this to 'true', the reminder won't repeat, even if you set this to 'false' later. If you change your mind, you will need to use the SMAPI console command `debug action MarkActionApplied Current LenneDalben.ArtisanEquipmentforSale_LetterTrigger false`
* * If you don't know how to use console commands, you can join the <a href="https://discord.gg/stardewvalley">Stardew Valley Discord community</a> to ask for help.

Note that the mod does not come packaged with a config file. The config file will be generated after you run the game with the mod installed at least once.


||Installation||

1. Install <a href="https://smapi.io/">SMAPI</a> (version 4.2.1 or higher)
2. Install <a href="https://www.nexusmods.com/stardewvalley/mods/1915">Content Patcher (CP)</a> (version 2.6.0 or higher)
3. <a href="https://www.moddrop.com/stardew-valley/mods/1034704">Download the mod from ModDrop</a> and unzip the mod folders into Stardew Valley/Mods.
4. Play the game using SMAPI!


||Uninstallation||
Delete the folders from this mod.


||Shout Outs||

Nexus user kupiqo for providing the German translation for the letter.

<a href="https://www.nexusmods.com/stardewvalley/users/88107803?tab=user+files">Jonqora</a> and <a href="https://www.nexusmods.com/stardewvalley/users/8049772?tab=user+files">Draylon</a>, who helped me with tweaking the requirements to buy the equipment and its availability to balance the mod.

<a href="https://www.nexusmods.com/stardewvalley/users/1552317?tab=user+files">Pathoschild</a>, author of SMAPI, without them, this mod wouldn't be possible.

<a href="https://www.nexusmods.com/stardewvalley/users/34250790?tab=user+files">spacechase0</a>, who gave me some ideas about what to include in the letter.

HUGE thanks to <a href="https://www.nexusmods.com/stardewvalley/users/3590100?tab=user+files">CherryChain</a>, author of Shop Tile Framework (STF) for the old version of the mod. Without them, this mod wouldn't be possible either. Extra thanks to CherryChain for their continued help in the Stardew Valley Discord with troubleshooting. 

<a href="https://www.nexusmods.com/stardewvalley/users/2186381?tab=user+files">Digus</a>, author of Mail Framework Mod (MFM) for the old version of the mod. Without them, the letter component of this mod wouldn't be possible.


Equipment available for sale (who sells what and for how much):

                 Clint

|   Machine        | Purchase Price |

Lightning Rod      |      2500      |

Furnace            |      5000      |

Geode Crusher      |      13975     |

Charcoal Kiln      |      3000      |

Heavy Furnace      |      20000     |

                 Dwarf

|   Machine        | Purchase Price |

Crystalarium       |     47400      |

                 Krobus

|   Machine        | Purchase Price |

Bee House          |      5750      |

                 Marlon

|   Machine        | Purchase Price |

Bone Mill          |      2180      |

Slime Egg-Press    |      8000      |

Slime Incubator    |     20000      |

                 Marnie

|   Machine        | Purchase Price |

Mayonnaise Machine |      8300      |

Cheese Press       |      8300      |

Loom               |      3200      |

Ostrich Incubator  |      26600     |

                 Pierre

|   Machine        | Purchase Price |

Scarecrow          |      3000      |

Quality Sprinkler  |      3500      |

Seed Maker         |     10000      |

Dehydrator         |      3000      |

Solar Panel        |     30500      |

                 Robin

|   Machine        | Purchase Price |

Preserves Jar      |      7500      |

Tapper             |      4000      |

Keg                |      7500      |

Mushroom Log       |      2000      |

Cask               |      2500      |

Heavy Tapper       |      6150      |

                 Sandy

|   Machine        | Purchase Price |

Garden Pot         |      1320      |

Oil Maker          |     10000      |

                 Willy

|   Machine        | Purchase Price |

Recycling Machine  |      5500      |

Fish Smoker        |      5000      |

Worm Bin           |      6925      |

Bait Maker         |      8000      |

Deluxe Worm Bin    |     10000      |



If you want to know the full details of who sells what, for how much, and exactly what the requirements are, see the ⚠️⚠️⚠️Full Spoiler Description:⚠️⚠️⚠️

                 Clint

|   Machine        | Purchase Price | Requirements

Lightning Rod      |      2500      | Learn recipe and 3 hearts with Clint

Furnace            |      5000      | Learn recipe and 4 hearts with Clint

Geode Crusher      |     13975      | Learn recipe and 4 hearts with Clint

Charcoal Kiln      |      3000      | Learn recipe and 5 hearts with Clint

Heavy Furnace      |     20000      | Learn recipe and 7 hearts with Clint

                 Dwarf

|   Machine        | Purchase Price | Requirements

Crystalarium       |     47400      | Learn recipe and 8 hearts with Dwarf

                 Krobus

|   Machine        | Purchase Price | Requirements

Bee House          |      5750      | Learn recipe and 5 hearts with Krobus

                 Marlon

|   Machine        | Purchase Price | Requirements

Bone Mill          |      2180      | Learn recipe, and if using Befriend Marlon and Gunther or Make Marlon Real, 3 hearts with Marlon. 

Slime Egg-Press    |      8000      | Learn recipe, and if using Befriend Marlon and Gunther or Make Marlon Real, 6 hearts with Marlon. If you're not using any of those mods, then getting to the bottom of the mines once

Slime Incubator    |     20000      | Learn recipe, and if using Befriend Marlon and Gunther or Make Marlon Real, 7 hearts with Marlon. If you're not using any of those mods, then getting to the bottom of the mines once

                 Marnie

|   Machine        | Purchase Price | Requirements

Mayonnaise Machine |      8300      | Learn recipe and 4 hearts with Marnie

Cheese Press       |      8300      | Learn recipe and 5 hearts with Marnie

Loom               |      3200      | Learn recipe and 7 hearts with Marnie

Ostrich Incubator  |     26600      | Learn recipe and 9 hearts with Marnie

                 Pierre

|   Machine        | Purchase Price | Requirements

Scarecrow          |      3000      | Learn recipe and 2 hearts with Pierre

Quality Sprinkler  |      3500      | Learn recipe and 3 hearts with Pierre

Seed Maker         |     10000      | Learn recipe and 5 hearts with Pierre

Dehydrator         |      3000      | Learn recipe and 6 hearts with Pierre

Solar Panel        |     30500      | Learn recipe and 9 hearts with Pierre

                 Robin

|   Machine        | Purchase Price | Requirements

Preserves Jar      |      7500      | Learn recipe and 3 hearts with Robin

Tapper             |      4000      | Learn recipe and 4 hearts with Robin

Keg                |      7500      | Learn recipe and 5 hearts with Robin

Mushroom Log       |      2000      | Learn recipe and 6 hearts with Robin

Cask               |      2500      | Learn recipe and 7 hearts with Robin

Heavy Tapper       |      6150      | Learn recipe and 9 hearts with Robin

                 Sandy

|   Machine        | Purchase Price | Requirements

Garden Pot         |      1320      | Learn recipe and 3 hearts with Sandy

Oil Maker          |     10000      | Learn recipe and 5 hearts with Sandy

                 Willy

|   Machine        | Purchase Price | Requirements

Recycling Machine  |      5500      | Learn recipe and 3 hearts with Willy

Fish Smoker        |      5000      | Learn recipe and 4 hearts with Willy

Worm Bin           |      6925      | Learn recipe and 5 hearts with Willy

Bait Maker         |      8000      | Learn recipe and 7 hearts with Willy

Deluxe Worm Bin    |     10000      | Learn recipe and 9 hearts with Willy


||2.0.0 Changelog||
* Updated for 1.6. Now requires SMAPI version 4.2.1+ and CP version 2.6.0+. No longer requires STF or MFM. If updating from previous version, delete all previous mod folders before installing the update.
* Removed specific check for SVE for Marlon's machines. SVE users can still buy items from Marlon by unlocking recipes and getting to the bottom of the mines once.
* Added config option Artisan Equipment Letter Only Sends Once: Choose whether to receive the letter reminder only once (default: false). This means the letter repeats every week on Thursdays.
* Added new machines: heavy furnace, dehydrator, mushroom log, heavy tapper, fish smoker, bait maker, and deluxe worm bin.
* Adjusted some of the heart requirements; refer to readme above.
* Updated mayonnaise machine price to match cheese press price.
* Fixed oil maker price typo (it's 10,000g, not 1,000g).