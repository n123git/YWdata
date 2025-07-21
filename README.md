# YWdata
YW data and asset dumps, primarily focused on YW2

## Wallpaper Stich
There are 10 folders named `001` through `010` respectively. 001 is wallpaper ID 0 aka Cool Blue, 002 = ID 1 etc.</br>
 These hold dumps of every wallpaper in YW2. in 3 forms: combined, overlay and spritesheet.</br>
`combined` can be found as `canvas.png` and is what you'd see ingame (but it's one still frame; not animated).</br>
`overlay` is `001.png` and is the tiled white overlay i.e. flowers.</br>
`spritesheet` is stored as `000.png` and is the main background displayed as a spritesheet.</br>
This tool also comes with `wallpaperstitch.html` which can be used to stitch wallpapers yourself, which can be useful for reasons including but not limited to the following:
* Dumping wallpapers yourself i.e. for yw3
* Merge wallpapers
* Preview/Test Custom Wallpapers</br>

I am planning to make a reversestitch to aid in making custom wallpapers for mods (and planning to dump yw3 wallpapers too) :D</br>
Note: the dumps dont include the error/debug wallpaper (IDs 10-255) as it is plain-black, not in the files and isn't supposed to occur in-game.

### Stitching Tool Guide
The tool has the following settings:
* Main Image (Required): This is the main spritesheet/background (000.png)
* Overlay Image (Optional): This is the tiled overlay (001.png)
* Columns: This is either 2 or 4, if the main image contains a gradient choose mode 4, otherwise 2.
* Gradient Height (Broken): This is currently broken, DO NOT TOUCH IT.
* Show Gradient (Disable this): Gradients are currently broken, disable this.</br>

For example to dump Cool Blue, you'd import the 000.png as the Main Image, 001.png as the Overlay Image. Set it to 4 columns and disable Show Gradient. Then right-click the preview and click "Save as" or "Save Image as".
  
## Translator Tool
A tool to translate and grab the IDs of Yo-kai watch things via the official translations ripped from the game, currently only supports YW2, and YW1 (YW1 added in v1.1). Although YW3, YWB1, YWB2 and Sangokushi support is planned.</br>
This tool supports MacOS, Linux, Windows and ANY modern OS that can run a up-to-date version of a web browser.</br>
Open the `APP.html` to start.
* Select your category i.e. `Key Items`
* Then select your input language - this is what you translate **from**
* Also select your output language to translate **to**.
* Finally, input your search query i.e. "bracelet" or "cheap brac" etc, and select Search.</br>
You will be given the item it found in the input AND output language, along with it's ID.</br>
Note that the Korean Attitude translations for yw2 may not be accurate.
Credits to togenyan for alot of the data (more data is coming).


## Location Dumper v42 (v1.0)
Input a decrypted save file and it dumps (and lets you edit) your Location and XYZ coordinates. Useful for people who don't like save editing but still may need it i.e. modders.

## Save Editor
this is an entirely different repo, just wanted to drop it here (give me a star pls XD). Find it [here](https://github.com/n123git/YWSaveEditor) :)

## QRbel
This website (can be downloaded optionally) functions as a sort of library of babel - pick a coin and scroll down forever as it generates near-infinite QR codes for that coin.

### Features
- Every coin in supported games
- Millions-Billions of QR codes for *each* coin in *each* game.
- current supported games: YW2
- planned supported games: YW1, YW1S, YW1P, YW3, YWB, Sangokushi, YWB2, Yo-kai Watch Land, Yo-kai Watch Puni Puni

## Notes
- These store data in folders next to the main `.html` - this is important as opening them without extracting the `zip` (double clicking it on windows instead) can cause it to not have access to these files, breaking the tools.

