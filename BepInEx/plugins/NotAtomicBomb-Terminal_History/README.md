# Terminal History

## Overview

Allows you to goto previously sent terminal commands using the up and down arrow keys.

## Installation

Just drag and drop the BepInEx folder to your Lethal Company root folder(Where the Lethal Company.exe is).
Or just use the ThunderStore mod loader.

## Changelog

### Version 1.0.0

- Release

## Version 1.0.1 

- Fixed an error if you input more than 20 different commands, credits: [NickolasFleim](https://github.com/NotAtomicBomb/TerminalHistory/pull/1)

## Version 1.0.2

- Implemented [LethalCompany InputUtils](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils/) and reformed everything to support this new way of handling the keybinds. This now gives the mod functionality to change the keybinds in-game. credits: [CTN-Originals](https://github.com/8CTN8)

## Version 1.0.3

- Implemented the command draft functionality. If they user has typed out anything already without sending it and instead uses the (up) keybind to go back in command history, it will save the drafted command they typed out and if they return to index -1 with the (down) keybind it will be restored.in-game. credits: [CTN-Originals](https://github.com/8CTN8)
- fixed a bug where if you go out of the terminal while already having used the back keys, the next time you use them it would not have been reset to the beginning. credits: [CTN-Originals](https://github.com/8CTN8)

## Version 1.0.4

- Added the terminal functionality for when a previous command is edited(whether added or deleting) it will set the current index to -1 and will be saved as a command draft