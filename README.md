# Loita hack
A Soita-like Rainmeter skin that displays track information from and controls various media players. This is a mod of [Loita](https://www.deviantart.com/lgv91/art/Loita-265348874) by Lgv91 (itself a mod of Soita which added a settings skin with theme customization), that adds repeat and shuffle buttons to the interface and changes the outdated color picker to a functioning and non-.exe variant.

### Example screenshots:

**Player**

![image](https://github.com/undeadwanderer/loita-hack/assets/51511863/7e8a8e4c-314c-4466-bbfd-58986d111bad)

**Configuration**

![image](https://github.com/undeadwanderer/loita-hack/assets/51511863/2018d7b9-cc70-40dd-90fa-ee9151c6ac67)
 ![image](https://github.com/undeadwanderer/loita-hack/assets/51511863/95ce05c3-8820-47f3-9afd-a730473faef7)


### Disclaimer: 
* I don't plan to update the skin with more features because the only new feature I wanted to implement for now were the repeat and shuffle buttons and a better color picker; I'm also not sure what else can the NowPlying plugin do.

### Requirements:
* Rainmeter v4.5, only tested the skin in this version.

### Supported players:
* Basically all that NowPlaying supports (See "Known issues"). I don't currently plan to introduce support for more players.

### How to use:
* Middle-click the skin to show the options menu where you can choose the player the skin will get the data from and theme.

### Credits & included resources:
* [poiru](https://www.deviantart.com/poiru) for [Soita Rainmeter skin](https://www.deviantart.com/poiru/art/Soita-for-Rainmeter-209864541) (licensed under Creative Commons BY-NC-SA 3.0).
* [Lgv91](https://www.deviantart.com/lgv91) for [Loita Rainmeter skin](https://www.deviantart.com/lgv91/art/Loita-265348874) & config tool for it (licensed under Creative Commons BY-NC-SA 3.0).
* [Deathcrafter](https://github.com/deathcrafter) for [ColorPickerUI](https://github.com/deathcrafter/ColorPickerUI), Licensed under Creative Commons BY-NC-SA 3.0.
* "Repeat" and "Shuffle" button icons made by me.

### ColorPickerUI uses:
* [CursorColor Plugin](https://forum.rainmeter.net/viewtopic.php?t=23375) by [jsmorley](https://www.rainmeter.net/).
* [Mouse Plugin](https://github.com/NighthawkSLO/Mouse.dll) by [NightHawkSLO](https://github.com/NighthawkSLO).
* Segoe Fluent Icons font.

### Version history:

```
1.1.3.1 / April 18, 2024
• Updated ColorPickerUI to version 2.1.2 of my fork.
    • Now the current color of the element is loaded on picker skin initialization
      instead of a pre-set one when changing colors.
    • Fixed a typo in Functions.lua.

1.1.3 / May 24, 2023
• Player volume can now be adjusted by using the scrollwheel over any area of the main skin.
• Moved the image files into @Resources.
• Switched from RainRBG to ColorPickerUI by Deathcrafter.

1.1.2 / May 22, 2023
• The skin now uses RainRGB4 instead of RainRGB as color picker.
• Included RainRGB4 in the skin package.
    • The previous releases of the skin do not work without the version of RainRGB they used
      already installed (by installing the original Loita skin for example) because there was
      no way to include the earlier version of the addon into the package with the official
      package creator because it had a hardcoded installation path.
• Fixed the config and main skins not refreshing after changing colores with RainRGB,
  the config skin will now update all its measures after changing any of the other options.

1.1.1.2 / May 21, 2023
• Made changing the options in the config skin to only refresh Loita instead of all skins.

1.1.1.1 / May 20, 2023
• Fix for the config skin shortcut not working.

1.1.1 / May 20, 2023

• Initial commit and release.
• Changes from the original skin:
  • Added "Repeat" and "Shuffle" buttons.
```

### Known issues: 
* I've only tested the skin with iTunes; it might not work as well with other players; I saw people complaining about issues with other players on Loita's DeviantArt page; I assume that those issues are because of the NowPlaying plugin and not of the skin code so I can't do anything about it anyway.
* The icons could be better but I don't have much experience with pixel art; tried my best to make them blend in with the rest of the buttons.
* "Repeat" function only switches between "off" and "repeat track", can't do anything about that since it's a NowPlaying limitation.
