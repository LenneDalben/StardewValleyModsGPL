# (CP) It Takes a Village - Class Events

This mod is in development! Penny will recruit fellow townspeople to teach Vincent and Jas something they know.

Features include randomized lesson orders and semi-dynamic dialog based on which lesson(s) played first! In repeat playthroughs, you may see the lessons in a different order, and with slightly different dialog, some which is seasonal.

||Background||

As a novice eventsmith, I was looking for simple-yet-interesting mod ideas to implement, and Airyn suggested a lessons series! The idea was "it takes a village to raise a child". Penny will recruit fellow townspeople to teach Vincent and Jas something they know. This year-and-9-months labor of love has been incredibly fun, so I hope you enjoy :)

Each lesson is an event in Pelican Town where t will share their thoughts townspeople react afterward. Some are supportive, some are judgmental, etc. Check out the screenshots for some examples! The Minimum Days Between Lessons config determines the duration for townspeople to share thoughts (known as Conversation Topics or CTs by modders).

Fair warning: most of the events have the player being passive or just not there, so if that's not your thing, give the mod a pass.

Translations are welcome! You can submit either the language.json to me or the strings in another language for all the strings and I will incorporate it into the mod. See more information on the <a href="https://stardewvalleywiki.com/Modding:Translations">wiki</a>.


||Getting started||

To begin the lesson series, reach 6 hearts with Penny, then visit the town on a sunny or windy day between 8:50am and 6:10pm for an event with Penny outside the Library. By default, at least 7 days later, a lesson will happen somewhere in town! Then after that lesson, at least 7 days will pass before the next lesson. Refer to the Configuration section on how to customize the Minimum Days Between Lessons.


Check the spoiler guide for instructions on activating additional lessons, some of which involve weather or time conditions.


||Configuration||

Config Options

* Minimum Days Between Lessons: After starting the lessons, at least 7 days must pass between each one by default. That's how long you have to talk to the villagers after each lesson to hear their thoughts. To see all the lessons and the final event, it'll take a minimum of 20 in-game weeks. If you'd like, you can adjust this interval between 1 and 28 days to speed up or extend the lesson schedule.
* * Author recommendation: if you're like me and it's an achievement if you make it to year 2 but you want to see all the events, set this to 4 days. Then it will take you ~12 weeks instead of 20 weeks. The downsides are you'll miss Kent's content and will need to quickly talk to the right people post-events (check the spoiler guide).

* Skippable Config: Specify if you want the events in the series to be skippable (true, false). Default is true. Useful if you're worried about getting stuck during an event due to a mod that changes maps.

* Portrait and Sprite Overlay Goggle Config: Specify if you want the Maru electronics lesson to include a portrait and sprite goggle overlay as a fun feature (true, false). Default is true. The overlays were designed for vanilla and Diverse Stardew (DSV), and will work for Seasonal Outfits - Slightly Cuter Aesthetic. If you use any other portrait or sprite mod that affect Maru, Jas, and/or Vincent, you may want to set this to false for immersion.

* Load Blacksmith Config: Default is true. Set this to false to avoid a Load error if you have a mod that adds events to the Blacksmith shop besides Clint Marriage Mod, Looking for Love, Lucikiel, or East Scarp. ITAV automatically detects Clint Marriage Mod, Looking for Love, Lucikiel, and East Scarp, so adjusting this setting is not needed for those mods.

* Edit Penny 8 Heart Event: Default is true. The first question in Penny's 8 heart event is adjusted to mention the lessons. This edit is compatible with atravita's Penny 8 Heart Event Adjusted, Hanatsuki's Gender Neutrality Mod, Hanatsuki's Fix Dialog Differences, Not a Farmer - Job Title Replacer, and Villager Name Replacer. Set this to false if you have a different mod editing Penny's 8 heart event.

* Progression Mode: Default is false. This leads to a completely random lesson order and you'll have a chance of seeing more varied bonus dynamic dialog. Set this to true if you want events to be grouped and play in a semi-randomized sequence following bracket grouping (check the spoiler guide), but see a smaller variety of dynamic dialog.

Note that the mod does not come packaged with a config file. The config file will be generated after you run the game with the mod installed at least once.


||Optional Add-On: Lasting Conversation Topics||

If the Minimum Days Between Lessons config options isn't right for you, try the <a href="https://www.nexusmods.com/stardewvalley/mods/14377">Lasting Conversation Topics</a> add-on under Optional Files! It keeps all CTs active until you've spoken to every NPC for that lesson (check the spoiler guide), to avoid missing dialog before the next lesson.


||Compatibility||

If you have a mod that changes map layouts, use the Skippable Config setting. It will allow you to skip the event if you or an NPC gets stuck.

The discussion after the Shane lesson includes dialog for <a href="https://www.nexusmods.com/stardewvalley/mods/9999">Sterling from Always Raining in the Valley (ARV)</a>, if you have ARV installed.

If you're using Event Lookup, ITAV events are listed even if they're not actually going to happen that day, because of the random token. There Can Be Only One ITAV event per day, regardless of what Event Lookup says.

Writing the vanilla version of this was a huge undertaking, so I will not add kids from other mods or add lessons led by custom NPCs. Authors of custom NPC mods are welcome to create their own lessons for their NPCs in a similar format!

A note on Stardew Valley Expanded (SVE): I don’t use it and never will, so I will not add compatibility for it. Use ITAV and SVE together at your own risk.


||Installation||

1. Install <a href="https://www.nexusmods.com/stardewvalley/mods/2400">SMAPI</a> (version 3.9.3 or higher)
2. Install <a href="https://www.nexusmods.com/stardewvalley/mods/1915">Content Patcher (CP)</a> (version 1.21.0 or higher)
- Optional: Install <a href="https://www.nexusmods.com/stardewvalley/mods/8626">Custom Companions (CC)</a> (version 1.4.3 or higher)
3. Download the mod from ModDrop (link TBD) and unzip the mod folders into Stardew Valley/Mods.
- If you do not use CC, you can delete that folder from your Mods folder.
4. Play the game using SMAPI!


||Shout Outs||

My SO, wonderful soul who proofread my work and provided emotional support <3

<a href="https://www.nexusmods.com/stardewvalley/users/70148453?tab=user+files">Airyn</a>, fantastic modder and friend. You provided the initial idea, created most of the custom sprites, and provided so much support and editing guidance on wording, in-character-ness, dynamic token magic, random token magic, etc. Without you, this mod would never have happened. Thank you so much!

<a href ="https://www.nexusmods.com/stardewvalley/users/116553368?tab=user+files">Atravita</a>, for helping me out with event forks and lighting

<a href ="https://www.nexusmods.com/stardewvalley/users/114762643?tab=user+files">Calcite / CopperSun</a>, for the skippable token idea and some help with wording

<a href ="https://www.nexusmods.com/stardewvalley/users/92469153?tab=user+files">Arknir</a>, for being an expert eventsmith, teaching me through code and answering questions

<a href ="https://www.moddrop.com/stardew-valley/profile/225898/mods">KediDili</a>, for providing some suggestions

<a href ="https://www.nexusmods.com/stardewvalley/users/5575844?tab=user+files">Lumina / Lumisteria</a> and <a href ="https://www.nexusmods.com/stardewvalley/users/48380238?tab=user+files">foggywizard</a>, for guidance on CTs stuff

<a href ="https://www.nexusmods.com/stardewvalley/users/95265773?tab=user+files">max / skellady</a>, for information on Saloon schedules, fades, and being a beta tester

<a href ="https://www.nexusmods.com/stardewvalley/users/120958053?tab=user+files">Elizabeth / violetlizabet</a>, for helping me figure out some conditions for CTs and fun with randomization

<a href ="https://www.nexusmods.com/stardewvalley/users/108124018?tab=user+files">Hime / Himetarts</a>, for letting me poke at Sterling's excellent draft event code

<a href="https://www.nexusmods.com/stardewvalley/users/68088657?tab=user+files">Lemurkat</a>, for helping me troubleshoot

<a href="https://www.nexusmods.com/stardewvalley/users/92060238?tab=user+files">Taiyo</a>, <a href ="https://www.nexusmods.com/stardewvalley/users/112768378?tab=user+files">tiakall</a>, and <a href="https://www.nexusmods.com/stardewvalley/users/2893756?tab=user+files">Yri</a> for some art feedback and encouragement on sprites I drew. Tiakall was also a beta tester.

<a href="https://www.nexusmods.com/stardewvalley/users/104804993?tab=user+files">nicole / beyondrecovery</a>, for help with figuring out the "walking off screen while fading out" effect, advancedMove, encouragement / accountability, wording help, and being a beta tester

<a href="https://www.nexusmods.com/stardewvalley/users/69153238?tab=user+files">shekurika</a>, for help with figuring out Clint's hammering animation and fades

<a href="https://www.nexusmods.com/stardewvalley/users/7439530?tab=user+files">ZoeDoll</a>, for being a beta tester

<a href="https://www.kdau.com/scrollish/">kdau's scroll generator</a>, for the scroll captions in the preview images

<a href="https://www.nexusmods.com/stardewvalley/users/1552317?tab=user+files">Pathoschild</a>, author of SMAPI and Content Patcher, without them, this mod wouldn't be possible