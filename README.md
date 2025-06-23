# YWdata
YW data and asset dumps, primarily focused on YW2

## Wallpaper Stich
There are 10 folders named 001-010, 001 is wallpaper ID 0 aka Cool Blue, 002 = ID 1 etc.</br>
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
A tool to translate and grab the IDs of Yo-kai watch things via the official translations ripped from the gamer, currently only supports YW2. Although YW3, YW1, YWB1 and YWB2 support is planned.</br>
This tool supports MacOS, Linux, Windows and ANY modern OS that can run a up-to-date version of a web browser.

## Save Editor
this is an entirely different repo, just wanted to drop it here (give me a star pls XD)

