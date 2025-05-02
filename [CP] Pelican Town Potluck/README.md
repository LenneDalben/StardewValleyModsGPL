# (CP) Pelican Town Potluck
This mod changes references to the Luau in mail, calendar, and dialog to say Potluck instead. Airyn also kindly changed the decorations, specifically the torches, totems, and rugs, so they weren't Luau themed. In version 1.1.0 the decoration changes extend to the totem pole furniture item, which is now the Summer Flower Tower.


||Background||

There was discussion on the Diverse Stardew (DSV) Discord server about how the Luau could be called something else. K.S.P Forever suggested calling it a Beachside Potluck, which stuck with me for several days before I decided to just search for the word Luau in the strings and dialog. Airyn then mentioned decoration changes, and after several tests, existentialdread recommended Pelican Town Potluck for the name, which has a nice ring to it! There are preview images in the download, but they're quite large so they're listed at the bottom of the description. :)

Translations are welcome! You can submit either the language.json to me or the strings in another language for all the orders and I will incorporate it into the mod. See more information on the <a href="https://stardewvalleywiki.com/Modding:Translations">wiki</a>.

Turkish translation provided by <a href="https://www.moddrop.com/stardew-valley/profile/225898">KediDili</a>!


||Configuration||

Config Options:
* Potluck Style: Choose the Potluck flooring - blanket (default), sand, or leaves (vanilla). To use blanket without visual glitches, set PotluckMapEdits to 'true'.
* Potluck Map Edits: Choose whether to edit the Luau map (true, default) or only the festival tilesheets (false). Set to true if you're using 'blanket' for PotluckStyle to prevent visual glitches. If you use another mod that edits the Luau map (excluding RSV and SBV which are already compatible), you may want to set this to false and use 'sand' or 'leaves' for 'PotluckStyle' to avoid conflicts. If PotluckStyle is set to 'leaves', this setting doesn't do anything.
* RSVRailing: Select between colorful or green bunting for the Ridgeside Village (RSV) railing. Default is colorful. If you don't have RSV installed, this setting doesn't do anything.

||Compatibility||

Pelican Town Potluck has built-in compatibility with <a href="https://www.nexusmods.com/stardewvalley/mods/9972">FarmerJack's Dialog Expansions</a>, <a href="https://www.nexusmods.com/stardewvalley/mods/2612">Immersive Festival Dialog by tangeriney</a>, <a href="https://www.nexusmods.com/stardewvalley/mods/7286">Ridgeside Village (RSV)</a>, and <a href="https://www.nexusmods.com/stardewvalley/mods/11111">Sunberry Village (SBV)</a>. For RSV, the compatibility applies to the latest version as well as the Android version!

In version 1.1.0 there is now built-in compatibility with <a href="https://www.nexusmods.com/stardewvalley/mods/2544">Canon-Friendly Dialogue Expansion (CFDE) by gizzymo</a>!

If you're interested in adding a compatibility patch for your mod (say you make custom NPCs or dialog mods), it's easy enough to do! I personally searched the RSV and Immersive Festival Dialog mod folders for the word Luau using VS Code to easily see where the word was used. Then I modified the relevant dialog lines in my mod and made sure the Target matched the location of the line. For more informal speech I just used Potluck. For RSV adults, I had them refer to it by the full name, Pelican Town Potluck, since they're from out of town.


||Installation||

1. Install <a href="https://smapi.io/">SMAPI</a> (version 4.2.1 or higher)
2. Install <a href="https://www.nexusmods.com/stardewvalley/mods/1915">Content Patcher (CP)</a> (version 2.6.0 or higher)
3. <a href="https://www.moddrop.com/stardew-valley/mods/1032927-pelican-town-potluck">Download the mod from ModDrop</a> and unzip the mod folder into Stardew Valley/Mods.
4. Play the game using SMAPI!


||Uninstallation||

Delete the folder from this mod.


||Shout Outs||

K.S.P Forever on the Diverse Stardew (DSV) Discord server, who suggested the mod!

existentialdread on the DSV Discord server, who provided the mod name!

<a href="https://www.moddrop.com/stardew-valley/profile/182160/mods">Airyn</a> on the DSV Discord server, who provided art assets for decorations, Ysabelle's summer 1 line, one of Sean's puns, encouragement, and ideas on compatibility patches!

The DSV server as a whole, folks there have the best mod suggestions! <3

<a href="https://www.nexusmods.com/stardewvalley/users/25845075?tab=user+files">tangeriney</a>, author of the excellent Immersive Festival Dialog mod.

<a href="https://www.nexusmods.com/stardewvalley/users/66167516?tab=user+files">Rafseazz</a> and the rest of the team working on the excellent RSV mod.

<a href="https://www.nexusmods.com/stardewvalley/users/6238934?tab=user+files">Gizzymo</a>, author of the excellent CFDE mod.

<a href="https://www.nexusmods.com/stardewvalley/users/6976914?tab=user+files">sophiesalacia</a>, and <a href="https://www.nexusmods.com/stardewvalley/users/112768378?tab=user+files">tiakall</a>, who provided the other 2 puns for Sean.

<a href="https://www.nexusmods.com/stardewvalley/users/1552317?tab=user+files">Pathoschild</a>, author of SMAPI and Content Patcher, without them, this mod wouldn't be possible.

||Preview Images||

![Calendar Change](Preview%20Images/Calendar%20Change.png)

![Mail Change](Preview%20Images/Mail%20Change.png)

![Lewis Dialog Change](Preview%20Images/Lewis%20Dialog%20Change.png)

![Decorations Changes](Preview%20Images/Decoration%20Changes.png)

![Furniture Change](Preview%20Images/Furniture%20Change.png)

||2.0.0 Changelog||
* Updated for 1.6 to fix visual glitches with festival map and totem pole furniture rename to Summer Flower Tower.
* Added new config option to customize the decorations at the festival
* Added new config option to choose the map edit
* Added Sunberry Village (SBV) compatibility