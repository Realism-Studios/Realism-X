# Realism-X
Probably the buggiest and most unplayable Realism upon release, several updates have been made to make it better.

If you're interested in reading the changelog, see the Changelog section at the bottom of this readme file.

And if you have any questions or concerns, ask in our [Discord Server][discord].

# What's Here?

## Source Code
This is the code that makes Realism X run. It's built off of [NSMBWer+], an updated & revamped version of the
original NSMBWer, which brings NewerSMBW's features to the retail game, while supporting the original worldmaps.

### Kamek
This is where all of the code is located. For specifics regarding this, see [here][explainKamekFolder].

[NSMBWer+]: https://github.com/Ryguy0777/NSMBWerPlus
[explainKamekFolder]: https://github.com/Ryguy0777/NSMBWerPlus?tab=readme-ov-file#kamek
[discord]: https://discord.gg/ycRTYaYPu3

### Bootstrap
This is the code to compile the `Loader.bin` file used to inject the custom code into the game. Unfortunately,
this code is the very same code seen in the very first releases of NewerSMBW's source code.

Compiling it is a hassle that I personally haven't successfully done, so the chances of this being useful is probably
very small. However, it's still here just for the sake of having *all* of the source code present.

## Riivolution Patch
This is the content you actually see in-game! The folder structure is pretty straight-forward, the names are pretty
self-explanatory, so there shouldn't really be any confusion there.

The majority of the unused stuff in this patch has been removed in previous updates for the project, and all of the
models have been compressed with ExtendedLZ77 to save some space.

# Changelog
## Realism X v4.5 - January 6th, 2024
This update addresses some issues related to the game's code! However there's one more issue, it's built using an outdated version of the source code.
Here's a list of what's been fixed:
- Fixed the invalid read errors seen on the File Selection screen
- Updated the Exception Handler text to point any future bug reports in the right direction
	
As mentioned previously, this is built using an OUTDATED VERSION of the source code, which means several features are missing, such as:
- Lemmy Ball suit throwing the wrong item (hammers)
- Luigi sounds on Message Blocks
- Clouds giving you Lemmy Ball suit
- ...and likely many others.

Since this fixes several code bugs, it's still worth releasing, however, if you want the FULL experience of the mod, please use v4.

## Realism X v4 - January 4th, 2024
This update attempts to fix some known bugs with Realism X, as well as make some minor additions/fixes! 
Here's a list of what's been changed:
- Fixed a crash in 8-7 related to missing tilesets
- 9-1 can now be completed
- It's no longer possible to access levels on the world map that haven't gotten a new level made for them (mostly affects Worlds 8 and 9)
  - Note that any retail levels between two (or more) new levels are still accessible 
- Removed a bunch of unnecessary and/or unused files, and compressed some files
  - This results in total decrease in size of around 175MB!
- The titlescreen now uses a region-free 'openingTitle.arc' file, which saves on space, as well as adds support for all regions.
- The included 100% save file now comes with versions for all regions of the game
- Custom text strings will now load for Korean and Taiwanese versions
- Added partial support for the Japanese, Korean, and Taiwanese versions of the game. Support is considered to only be partial for the following reasons:
  - These versions are NOT tested at all
  - There's no support for any languages besides English (you aren't missing out on much though, the text is mostly unreadable anyways)
- Added a texture for the collision switcher sprite, since it seemingly was planned to be added, yet never was (note that this may not have any effects on gameplay)
- Made the Riivolution XML file more efficient
- Made loading the 100% save file easy and optional (no more having to manually remove it from the download)
  - To load it, enable the "Load 100% Save" option in Riivolution
  - If loading the save causes any crashes, simply disable the option. Do NOT report it as a bug, the crashes are due to a bug with Riivolution itself, and has nothing to do with our mod.
- It's no longer possible to get stuck at the 2-Cannon node
	
Known Bugs:
- 1 to 3 invalid read errors appear on the File Selection screen (currently unfixable, and will almost certainly stay that way)
	
## Realism X v3 - October 11th, 2023
- Added PAL support
- Other unspecified changes
	
## Realism X v2 - October 10th, 2023
- Removed NSMLW powerup models from the download
	
## Realism X v1 - October 9th?, 2023
- Initial release