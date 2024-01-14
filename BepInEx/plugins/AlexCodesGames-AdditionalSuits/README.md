# Additional Suits v2.0.0
## About
Adds 8 more standard suits to your initial closet at the start of the game! Great for organizing larger crews!

Please leave a thumbs up if you enjoyed the mod, you can't imagine how much it means to me!

Follow my socials to stay in the loop for new updates, mod, and games I'm working on! (Thank you for all your support <3!!)

[X](https://twitter.com/AlexCodesGames) | [Instagram](https://www.instagram.com/alexcodesgames/) | [Discord](https://discordapp.com/users/the_shadow_wizard)

## Instructions - Installation
This mod relies on [AdditionalContentFramework](https://thunderstore.io/c/lethal-company/p/AlexCodesGames/AdditionalContentFramework/), so you need to download that as well

Automatic: Click 'Install with Mod Manager' button (ensure you have the Thunderstore mod manager installed).

Manual: Export the main folder into your BepInEx/plugins folder.

After installation you will see the new suits when you launch the game.

## Instructions - Adding New Suits
All suite definitions are in the 'suit-defs.json', this includes details such as each suit's name & if it needs to be unlocked to be used (ComingSoon[TM]). To add a new suite to your game just follow these steps:

    1 - Place your new texture file in the resource folder ('resAdditionalSuits')
    2 - Create a new JSON entry in the 'suit-defs.json' file to represent your suit

When you load your game your new suit should be added!

## Additional Info
If you are interested in the raw source, you can find the project file in this [GitHub Repo](https://github.com/AlexCodesGames/LC-Additional-Content-Framework/). Feel free to use it in any way you wish!

## Changelog
	- v2.0.0
		- Split project into a modular framework (this mod is now just a module that plugs into loader framework), this *should* fix a TON of conflicts & make it easier to add/share your own suits
	- v1.1.3
		- Formatting x_x
	- v1.1.2
		- Bug fix
	- v1.1.1
		- Minor code update
	- v1.1.0
		- Rewrote system to load suits based on JSON defs (prep for adding suits to the terminal shop)
	- v1.0.2
		- Added black suit
	- v1.0.1
		- Minor code update
	- v1.0.0
		- Release