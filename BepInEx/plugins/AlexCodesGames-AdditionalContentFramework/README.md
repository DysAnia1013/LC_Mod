
# Additional Content Framework v1.0.3
## About
This mod acts as a module loader for other mods, allowing you to easily add your own custom items to Lethal Company!

Please Note: For this mod to work, ALL players in your lobby need to have this mod (along with any content modules being used) downloaded!

[X (Twitter)](https://twitter.com/AlexCodesGames) | [Instagram](https://www.instagram.com/alexcodesgames/) | [Discord](https://discordapp.com/users/the_shadow_wizard)

## Instructions - Installation
Automatic: Click 'Install with Mod Manager' button (ensure you have the Thunderstore mod manager installed).

Manual: Export the main folder into your BepInEx/plugins folder.

After installation you will see the new suits when you launch the game.

## Instructions - Adding New Content
 Currently it only provides an interface for adding suits, but terminal items & scrap are planned as well.

### Adding Suits:
To add new suits to your game simply:
	
	1 - Download the 'AdditionalSuits' template folder from github [Here](https://github.com/AlexCodesGames/LC-Additional-Content-Framework/tree/main/ModTemplates)
	2 - Update the 'icon', 'readme', and 'manifest' files with your mod details
	3 - In the plugins folder, rename the resource folder (in the plugin folder) from 'resTemplateMod' to 'res' + your_mod_name (the mod folder MUST have 'res' as a prefix)
	4 - In the resource folder, replace the template suit textures with your own textures
	5 - In the resource folder, update the 'suit-defs.json', linking your new suits
	6 - Pack into a .zip file and upload to Thunderstore!

## Additional Info
If you are interested in the raw source, you can find the project file in this [GitHub Repo](https://github.com/AlexCodesGames/LC-Additional-Content-Framework/). Feel free to use it in any way you wish!

## Changelog
	- v1.0.3
		- Modified the json parser to be more error-out per def, not per file (meaning if 1 def is bad the others will still load)
	- v1.0.2
		- Minor bugfix
	- v1.0.1
		- Changed some logs around to make things more readable
	- v1.0.0
		- Release