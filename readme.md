Hi
This is a weather effect library for gzdoom written on zscript.

Library contain weather effects for snow, rain and ashes. Currently they are disabled, since it not intentioned to be used as is.
Sadly, for now it would work only with pack archives, AKA no WAD files support.

# HOW USE IT
- Step 1) Copy __ALL(bold)__ content of this folder to you mod pack
    -1.1 If you already have zscript file in you folder, just copy include line from this mod zscript file into your mod zscript file
- Step 2) Open WEATHDEF file
    -2.1 Read instruction of how to use it
- Step 3) Follow instruction in WEATHDEF and define specific weather for specific map

There are a bunch of comments what thing do what and how. So if you want to change something it should be easy.

In short, library work like this. It spawn some actors, shows it as snow/rain/etc. until it hit sector floor and then warp it into infinity to reuse them later. Not the greatest solution, but fastest