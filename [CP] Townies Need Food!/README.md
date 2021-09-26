# [CP] Townies Need Food!

With Townies Need Food (TNF), villagers will ask for cooked meals you can make in the kitchen, and reward you with gold and friendship. You'll have 7 days to complete the special orders. For the special orders to show up on the special orders board, you must have a kitchen, either from the first house upgrade, or from one of the mods listed in the Compatibility section. There are also milestone requirements (for orders involving the island recipes). By default the friendship requirements are turned off, but you can manually turn those on in the config. The friendship requirements are also automatically turned on if you have Friends Forever or CJB Cheats Menu installed. For the full specifics, refer to the spoiler guide.

The NPCs request every vanilla recipe (including from the 1.5 update), with the exceptions of: Strange Bun (because no one in town likes it), Pale Broth and Algae Soup (I've no good reason for excluding these, I just did :I ). You may notice that the NPCs ask for recipes they enjoy, hint hint~ The villagers only ask for vanilla recipes (base game), no PPJA / JA recipes.

Korean translation courtesy of jina2ya (Kaya).

||Configuration||

Config Options
Repeatable: true or false, default is true
IncludeIslandContent: true or false, default is true (toggle special orders requiring recipes from the island)
FriendshipConfig: If you don't use a mod to stop friendship decay, but you still want to toggle the friendship requirements, set this to true. Default is false. If you have Friends Forever or CJB Cheats Menu installed, TNF will auto-detect it and apply this setting.

With regards to the "sparseness" of the orders: the game picks from a pool of the available orders, so if you'd prefer to get through some of the vanilla special orders first, install this mod later in your playthrough.

By default, there are no friendship requirements. You can turn them on manually in the config, or by using Friends Forever or CJB Cheats Menu (TNF automatically detects if you have those mods installed). This is because of <a href="https://github.com/Pathoschild/StardewMods/blob/develop/ContentPatcher/docs/author-guide.md#known-limitations">a limitation with the way the game reads modifications to the special orders</a>, if your friendship decays enough that you no longer meet the requirement, you could get a crash. Do not manually turn on the friendship requirements unless you accept the risk.

Note that the mod does not come packaged with a config file. The config file will be generated after you run the game with the mod installed at least once.

||Compatibility||

Townies Need Food will recognize if you have one of the following mods installed, so special orders will show up on the special orders board before you have the first house upgrade:

Froststar11's Tiny Kitchen

Kitchen Nook for 1st Farmhouse by Allayna

BS New Farmhouse Design and Kitchen Corner﻿ by BURAKMESE

Seasonal Garden Farmhouse V2 by DustBeauty

CCS Kitchen Station Set by jina2ya

Minerva's Bigger Farmhouses by minervamaga

1.5 FarmHouse1, 2 with Bathroom by muscat (CP version)

Cozier Default Farmhouses by DexMods

Cozy Starter Farmhouse with Kitchen by isaonhieno

TNF will also auto-detect if you have Friends Forever or CJB Cheats Menu installed to toggle on friendship requirements.

||Installation||

1. Install <a href="https://smapi.io/">SMAPI</a> (version 3.9.0 or higher)
2. Install <a href="https://www.nexusmods.com/stardewvalley/mods/1915">Content Patcher (CP)</a>  (version 1.20.0 or higher)
3. <a href="https://github.com/LenneDalben/StardewValleyModsGPL/releases/">Download the mod</a> and unzip the mod folder into Stardew Valley/Mods.
4. Play the game using SMAPI!


||Updating||

⚠️⚠️⚠️ATTENTION: Version 2.0.0 of TNF is a COMPLETE REWRITE. If you're updating from a 1.x version, make sure you complete or cancel any quests you had in your journal from TNF first. Then, completely delete all the folders for TNF (you cannot overwrite).⚠️⚠️⚠️Once you've done that, then you can update TNF by following the install instructions above.


||Un-installation||

⚠️⚠️⚠️Make sure you complete or cancel any quests (from versions 1.x) or special orders (from versions 2.x) you had in your journal from TNF first.⚠️⚠️⚠️Once you've done that, delete the folders for this mod from your Stardew Valley/Mods folder.

Note that if the game was going to include special orders from TNF in the next round of special orders, you may still see some special orders listed from this mod. They will reset the following week. User stardewswag confirmed they uninstalled TNF and accepted the special order that still showed, and they crashed. Do not accept a special order from TNF after uninstalling it in order to avoid the crash.

||Shout Outs||

Jonqora, for ideas and suggestions that were incorporated in this mod. Jonqora was also INSTRUMENTAL in the dynamic token component of this mod. Jonqora, you are a legend <3

Lumina, for their Lumisteria Special Orders mods, which helped me in writing this mod. Extra thanks to Lumina for their help in the Stardew Valley Discord.

Gervig91, for helping me test the 2.0.0 update.

Thanks very much to jina2ya (Kaya) for the Korean translation!

Pathoschild, author of SMAPI and Content Patcher, without them, this mod wouldn't be possible either.
