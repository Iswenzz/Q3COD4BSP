# Q3->CoD4 Map Converter
Converts all of the Quake3 .BSP files, to CoD4 .MAP files, which are editable in CoD4's Level editor, Radiant. Generates a .GDT file that contains all materials used in the map file. It also generates a .BAT to compile every material faster. 

![](https://i.imgur.com/RkDPYn9.png)

1. Place every Q3 .BSP in the "BSP" folder.
2. Run converter.exe
3. Collect the new .MAP, .GDT, and .BAT files in the "out" folder.

If you have the CoD4 compile tools SDK (Radiant etc..) places the files:
.MAP in "CoD4/map_source"
.GDT in "CoD4/source_data"
.BAT in "CoD4/bin"

All of the map textures (and default quake3 textures) must be in
"CoD4/texture_assets/quake3" (create the quake3 folder)

Windows Download: https://www.dropbox.com/s/g4c7vf5km2l9a9r/Q3-CoD4%20Map%20Converter.zip?dl=1

Credits: Iswenzz, NitroFire, Phelix!
