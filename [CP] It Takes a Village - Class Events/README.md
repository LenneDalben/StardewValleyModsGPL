# (CP) It Takes a Village - Class Events

This mod is in development! NPCs help out Penny teach the kiddos (Vincent and Jas) by giving lessons.

Features include semi-randomized order of lessons and dynamic dialog based on which lesson(s) played first! In repeat playthroughs, you may see the lessons in a different order, and with slightly different dialog, some which is seasonal.

||Background||

As a novice eventsmith, I was looking for event modding ideas that would be relatively simple but interesting to implement, and Airyn, who has many wonderful ideas, suggested a lessons series! The idea was "it takes a village to raise a child", so Penny will recruit fellow townspeople to teach Vincent and Jas something they know. This mod has been an incredibly fun labor of love, so I hope you enjoy :)

Each lesson or class is an event, taking place somewhere in Pelican Town. After each class, the townspeople will share their thoughts on the topic or how the lesson went. Some are supportive, some are judgmental, etc. Check out the screenshots for some examples! The Minimum Days Between Lessons config setting is how long the townspeople will share their thoughts for (for modders, these are Conversation Topics).

Fair warning: most of the events have the player being passive or just not there, so if that's not your thing, give the mod a pass.

Translations are welcome! You can submit either the language.json to me or the strings in another language for all the strings and I will incorporate it into the mod. See more information on the <a href="https://stardewvalleywiki.com/Modding:Translations">wiki</a>.


||Getting started||

To begin the lesson series, reach 6 hearts with Penny, then visit the town on a sunny day between 9:30am and 7pm. An event will play with Penny outside the Library / Museum. By default, at least 7 days later, a lesson event will happen somewhere in town! Refer to the Configuration section on how to customize the Minimum Days Between Lessons.

Refer to the spoiler guide for details on activating the other events (a few have weather conditions).


||Configuration||

Config Options

* Minimum Days Between Lessons: After kicking off the lessons, at least 7 days must pass between the lessons by default. That's how long you have to talk to the villagers after each lesson to hear their thoughts. This also means it'd take at least 20 weeks in-game to see all the lessons and the wrap up event. If you'd like to reduce the time between lessons to see them faster, or increase the time to spread out the lessons even more, you can! You can select a number between 1 day and 28 days for minimum days between lessons.

* Skippable Config: Specify if you want the events in the series to be skippable (true, false). Default is true. Useful for repeat playthroughs if you want to pick and choose which events you see, or if you're worried about getting stuck during an event due to a mod that changes maps.

* Portrait and Sprite Overlay Config: Specify if you want the Maru electronics lesson to include a portrait and sprite overlay as a fun feature (true, false). Default is true. The overlays were designed for vanilla and Diverse Stardew (DSV). If you use any other portrait or sprite mod that affect Maru, Jas, and/or Vincent, you may want to set this to false for immersion.

* Load Blacksmith Config: Set this to false if you have a mod that adds events to the Blacksmith shop besides Clint Marriage Mod, Looking for Love, or Lucikiel. ITAV automatically detects Clint Marriage Mod, Looking for Love, and Lucikiel so adjusting this setting is not needed for those mods. Default is true.

* Edit Penny 8 Heart Event: For immersion reasons, Penny's 8 heart event is tweaked to include a reference to the lessons. Set this to false if you have another mod that edits Penny's 8 heart event. Default is true.

Note that the mod does not come packaged with a config file. The config file will be generated after you run the game with the mod installed at least once. 


||Compatibility||

A note on Stardew Valley Expanded (SVE): I don’t use it and never will, so I will not add compatibility for it. Use ITAV and SVE together at your own risk.


||Installation||

1. Install <a href="https://www.nexusmods.com/stardewvalley/mods/2400">SMAPI</a> (version 3.9.3 or higher)
2. Install <a href="https://www.nexusmods.com/stardewvalley/mods/1915">Content Patcher (CP)</a> (version 1.21.0 or higher)
3. Download the mod from ModDrop (link TBD) and unzip the mod folder into Stardew Valley/Mods.
4. Play the game using SMAPI!


||Future Plans||

I would like to include the kids from Ridgeside Village (RSV) and East Scarp (ES) someday in a future update, but I don't have a target date for that, or detailed plans to ask for permission. Writing the vanilla version of this has been a huge undertaking as it is.


||Shout Outs||

<a href="https://www.moddrop.com/stardew-valley/profile/182160/mods">Airyn</a>, fantastic modder and friend. You provided the initial idea, and so much support and editing guidance on wording, in-character-ness, dynamic token magic, random token magic, etc. Without you, this mod would never have happened. Thank you so much <3

<a href ="https://www.nexusmods.com/stardewvalley/users/116553368?tab=user+files">Atravita</a>, for helping me out with event forks

<a href ="https://www.nexusmods.com/stardewvalley/users/114762643?tab=user+files">Calcite / CopperSun</a>, for the skippable token idea and some help with wording

<a href ="https://www.nexusmods.com/stardewvalley/users/92469153?tab=user+files">Arknir</a>, for being an expert eventsmith, teaching me through code

<a href ="https://www.moddrop.com/stardew-valley/profile/225898/mods">KediDili</a>, for providing some suggestions

<a href ="https://www.nexusmods.com/stardewvalley/users/5575844?tab=user+files">Lumina / Lumisteria</a> and <a href ="https://www.nexusmods.com/stardewvalley/users/48380238?tab=user+files">foggywizard</a>, for guidance on conversation topics stuff

<a href ="https://www.nexusmods.com/stardewvalley/users/95265773?tab=user+files">max / skellady</a>, for information on Saloon schedules

<a href ="https://www.nexusmods.com/stardewvalley/users/120958053?tab=user+files">Elizabeth / violetlizabet</a>, for helping me figure out some conditions for conversation topics and fun with randomization

<a href ="https://www.nexusmods.com/stardewvalley/users/108124018?tab=user+files">Hime / Himetarts</a>, for letting me poke at Sterling's excellent draft event code

<a href="https://www.nexusmods.com/stardewvalley/users/68088657?tab=user+files">Lemurkat</a>, for helping me troubleshoot.

<a href="https://www.nexusmods.com/stardewvalley/users/1552317?tab=user+files">Pathoschild</a>, author of SMAPI and Content Patcher, without them, this mod wouldn't be possible.