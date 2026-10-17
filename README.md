# Sega NN Tools

A Python library for Blender for games using Sega's NN libraries. \
Please don't use this codebase to train AI, make things using this with AI, or make modifications to this with AI. Thank you :)

## Requirements
 - Blender 4.1.1.
 - The files you want to import must not be compressed / packed.

## Installation
 1. [Download the plugin.](https://github.com/Argx2121/Sega_NN_tools/releases)
 2. Install the addon in blender:
    1. In the top bar: Edit > Preferences
    2. In Preferences: Addons > Install
    3. In Blender File view: Navigate to where you downloaded the zip file, select the file and select Install Add-on.
    4. In Preferences: Check the box for Sega NN tools.
 - On updating you need to install the new version and restart Blender.
 - If downloading a zip from GitHub before release, you'll have to rename the folder from "Sega NN Tools (version number)" to "Sega_NN_tools" inside the zip.

## Usage
1. Open from either
   - 3d view > Sidebar (press n on your keyboard!) > Sega NN tools > import
   - Top bar > file > import 
2. Choose the correct *no format and game that the file originates from.
 - Importing files in batch opens the console on Windows and prints file information while processing files.

## Games
 - With all games files should be extracted. Files without the appropriate file extension (.cno, .eno, lno, etc.) will not be read.
 - All games have a slightly different file format - please specify the game for the tool so it can import the model correctly. If no game is specified the tool may import the model incorrectly.
 - The tool comes with some file extractors. Please use them when applicable. 

## Supported Game Formats

| Sno / PS2                                | Cno / PS3               | Uno / PSP                 | Gno / GameCube                  | Xno / Xbox             | Yno / Xbox | Eno / Xbox 360                              | Zno / DirectX 2              | Lno / Lindbergh                        | Ino / Mobile                        |
|------------------------------------------|-------------------------|---------------------------|---------------------------------|------------------------|------------|---------------------------------------------|------------------------------|----------------------------------------|-------------------------------------|
| Sonic Riders Zero Gravity                | The House of the Dead 4 | K-On! After School Live!! | Ghost Squad                     | Sonic Riders           |            | Sonic Free Riders                           | Sega Golden Gun              | Sonic 4 Episode 2                      | Sonic 4 Episode 1                   |
| Sega Superstars                          | Sonic 4 Episode 1       |                           | Super Monkey Ball: Step & Roll  | Sonic (2006)           |            | Sonic the Hedgehog 4: Episode I (Prototype) | Sonic 4 Episode 1            | The House of the Dead 4                | Sonic 4 Episode 1 (Pre 2016 Update) |
| Sega Ages 2500 Series Vol. 5: Golden Axe | Sonic 4 Episode 2       |                           | Sonic and the Black Knight      | Phantasy Star Universe |            |                                             | Transformers: Human Alliance | Loving Deads: The House of the Dead EX |                                     |
|                                          |                         |                           | Sonic Unleashed                 |                        |            |                                             |                              |                                        |                                     |
|                                          |                         |                           | Sonic Riders Zero Gravity       |                        |            |                                             |                              |                                        |                                     |
|                                          |                         |                           | Sonic and the Secret Rings      |                        |            |                                             |                              |                                        |                                     |
|                                          |                         |                           | Bleach: Shattered Blade         |                        |            |                                             |                              |                                        |                                     |
|                                          |                         |                           | Super Monkey Ball: Banana Blitz |                        |            |                                             |                              |                                        |                                     |
|                                          |                         |                           | Sonic Riders                    |                        |            |                                             |                              |                                        |                                     |

Regarding texture issues:
- Pink textures mean that the image files is likely damaged or malformed
- An image node without a texture means the image file could not be found. Occasionally the model file has incorrect texture names listed, but it may also be that the images need to be extracted.
- The riders series stores texture information in a particular way for maps. Please use my tools file extractor after decompressing with a different tool to get that information.

## About

### Developers
 - Arg!!
 
### Special thanks
 - firegodjr
 - Radfordhound
 - Sewer56
 - Shadowth117
 - Yacker

### Links
[Discord Link](https://discord.gg/CURRBfq) 

[GitHub Link](https://github.com/Argx2121/Sega_NN_tools/)
