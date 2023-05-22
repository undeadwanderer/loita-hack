# Loita hack
A Soita-like Rainmeter skin that displays track information from various media players. This is a mod of Loita by Lgv91, itself a mod of Soita, that adds repeat and shuffle buttons to the interface.

Disclaimer: I don't plan to update the skin with more features because the only new feature I need atm is the repeat and shuffle buttons; I'm also not sure what else can the NowPlying plugin do, plus I'm not much of a programmer and made this mod for personal use.

Requirements:
* Rainmeter v4.5, only tested the skin in this version.

How to use:
* Middle-click the skin to show the options menu where you can choose the player and theme.

Credits & included resources:
* [poiru](https://www.deviantart.com/poiru) for [Soita Rainmeter skin](https://www.deviantart.com/poiru/art/Soita-for-Rainmeter-209864541).
* [Lgv91](https://www.deviantart.com/lgv91) for [Loita Rainmeter skin](https://www.deviantart.com/lgv91/art/Loita-265348874).
* [jsmorley](https://www.rainmeter.net/) for [RainRGB4 addon](https://forum.rainmeter.net/viewtopic.php?t=6215).
* "Repeat" and "Shuffle" button icons made by me.

Version history:

1.1.2 / May 22, 2023
* The skin now uses RainRGB4 instead of RainRGB as color picker.
* Included RainRGB4 in the skin package.
	* The previous releases of the skin do not work because there was no way to include the earlier version of the addon into the package with the official package creator because it had a hardcoded installation path.
* Fixed the config and main skins not refreshing after changing colores with RainRGB, confing skin will now update all its measures after changing any of the other options.

1.1.1.2 / May 21, 2023
* Made changing the options in the config skin to refresh only the main Loita skin instead of all skins.

1.1.1.1 / May 20, 2023
* Fix for the config skin shortcut not working.

1.1.1 / May 20, 2023

* Initial commit and release.
* Changes from the original skin:
  * Added "Repeat" and "Shuffle" buttons.

Known issues: 
* I've only tested the skin with iTunes; it might not work as well with other players; I saw people complaining about issues with other players on Loita's page; I assume that those issues are because of the NowPlaying plugin and not of the skin code so I can't do anything about it anyway.
* The icons could be better but I don't have much experience with pixelart; tried my best to make them blend in with the rest of the buttons.
* "Repeat" function only switches between "off" and "repeat track", can't do anything about that since it's a NowPlaying limitation.

To do:
* Looking into a possibility of replacing RainRGB with ColorPicker so the skin won't depend on any executables.