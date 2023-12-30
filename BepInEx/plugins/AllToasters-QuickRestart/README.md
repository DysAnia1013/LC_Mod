# Quick Restart v1.2
## by alltoasters
https://github.com/EBro912/QuickRestart


### Installation
 Requires the latest version of [BepInEx 5](https://github.com/BepInEx/BepInEx). After BepInEx has been installed, drag `QuickRestart.dll` into the `BepInEx/plugins` folder in the game's root directory. You will need to run the game once for the `QuickRestart.cfg` file to generate.

### Usage
While your ship is in orbit, as the host, type /restart into the chat. You will be given a prompt to CONFIRM or DENY the restart. Typing DENY into chat will cancel the restart and nothing will happen. Typing CONFIRM into chat will proceed with the restart, and the ejection cutscene will begin after a few seconds and your game will restart.

### Config Options
Located in `BepInEx/config/QuickRestart.cfg`

Set "Override Confirmation" to true to bypass the confirmation, and false to keep the confirmation step in place.