Hi
This is a weather effect library for Gzdoom written entirely on Zscript.

Library contain weather effects for snow, rain and ashes.
Sadly, for now it would work only with pack archives, AKA no WAD files support.

# HOW TO USE IT?

Copy "thirdparty", "sprites" and "sounds" folders into you mod folder. Copy content of "zscript.zc" file into your mod zscript root file (optionally delete version nmumber if you already use one)  "cvarinfo", "sndinfo" and "zmapinfo" files and thats it.

**IMPORTANT**, copy "WEATHERDEF" file as is!!!!

## HOW DEFINE WEATHER?
Open WEATHDEF file. Read instruction of how to use it.
Follow instruction in WEATHDEF and define specific weather for specific map

**NOTE TO MAPPERS**: make sure that height of outdoor sectors at least four times high than player height, otherwise snow/rain would pop up into existance right before player eyes.

There are a bunch of comments what thing do what and how. So if you want to change something it should be easy.

In short, library work like this. It spawn some actors, shows it as snow/rain/etc. until it hit sector floor and then warp it into infinity to reuse them later. Not the greatest solution, but fastest