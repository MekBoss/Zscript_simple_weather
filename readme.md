Hi
This is a weather effect library for gzdoom written on zscript.

Library contain weather effects for snow, rain and ashes. Currently they are disabled, since it not intentioned to be used as is. To activate it follow instruction in a zscript.zc file. There are a bunch of comments what thing o what and how properly activate it.

In short, library work like this. It spawn some actors, shows it as snow/rain/etc. until it hit sector floor and then warp it into infinity to reuse them later. Not the greatest solution, but fastest