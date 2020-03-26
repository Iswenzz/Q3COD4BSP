# Q3->CoD4 Map Converter

[![Build status](https://ci.appveyor.com/api/projects/status/f3et0j2sjonn3yua?svg=true)](https://ci.appveyor.com/project/Iswenzz/q3-to-cod4-map-converter)
[![codecov](https://codecov.io/gh/Iswenzz/Q3-to-CoD4-Map-Converter/branch/master/graph/badge.svg)](https://codecov.io/gh/Iswenzz/Q3-to-CoD4-Map-Converter)
[![CodeFactor](https://www.codefactor.io/repository/github/iswenzz/q3-to-cod4-map-converter/badge)](https://www.codefactor.io/repository/github/iswenzz/q3-to-cod4-map-converter)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This program converts `.BSP` files taken from Quake3 levels, and converts them to Call of Duty 4's `.MAP` format. These files can be opened and edited using Call of Duty 4's level editor Radiant. This program also creates a `.GDT` file which stores all of the materials used in the level, as well as any properties those materials may have. The `.BAT` file generated by this program serves to allow the user to compile the materials much faster than trying to do it manually. The purpose of this program is mainly to speed up the process of porting Quake3 levels to Call of Duty 4.

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
