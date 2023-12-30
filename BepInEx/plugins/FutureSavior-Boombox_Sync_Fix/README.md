# Boombox Sync Fix
This mod fixes a base game bug where the Boombox plays different songs between the client(s) and host if it's already in the ship at the start of the lobby.

## What is this bug, exactly?

You may notice that whenever you buy a new boombox, the music is the exact same for everyone no matter how many times you use it. However, if you join a game where a boombox is already spawned in the ship, this is no longer the case, meaning that the client(s) and the host will very likely hear different songs, and they're no longer in sync.

## Installation guide

Install this like any other BepInEx mod, either manually of with r2modman / Thunderstore.

When installing manually, install the mod in the following directory:
```
\GAME_LOCATION\Lethal Company\BepInEx\plugins
```

I STRONGLY recommend for everyone in the lobby to have this mod installed, even though this mod is *technically* client-side.

## (In)compatibility list

This mod should be compatible with most boombox mods, and most notably, Stevens Custom boombox mods. However, here's a list of known incompatibilities / mods that just straight up don't need this mod because they handle the syncing themselves:

- YoutubeBoombox

## FAQ

### I'm using the Custom Boombox music mod and it's desynced, why?

Make sure that everyone has the EXACT same songs installed -- if there's even one more song then it will completely change the randomizer, resulting in desync.

Other than that, make sure that there aren't any weird errors being printed it the BepInEx console when you're launching the game / playing.

### I found a bug / compatibility issue, where can I report this?

You can create an issue on my GitHub page linked at the very top, go to the #mod-releases forum on the community discord server (https://discord.gg/lethal-company), or just DM me on Discord (nickname: futuresavior)

## Credits
Thank you to Steven (the creator of Custom Boombox Music) for helping me figure out what exactly caused this bug <3
