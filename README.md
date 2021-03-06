# ClassicUO World Map Markers for UO:Renaissance

A simple repository to store the map marker points to be used with the World Map in the [ClassicUO](https://github.com/andreakarasho/ClassicUO) client.

While the vast majority of the locations in these markers will apply to any Felucca map, these have been updated to only include areas specifically found on [UO:Renaissance](http://www.uorenaissance.com/).

![example](https://imgur.com/jvjntAD.gif)

## Installation

- [Download](https://github.com/markdwags/uor-markers/archive/master.zip) this repository.
- Extract all the files into `Data\Client` located at the root of the ClassicUO folder.
- Open the World Map or right-click and select `Reload markers`.

If you just want to download the map icons, [click here](https://raw.githubusercontent.com/markdwags/uor-markers/master/MapIcons.zip).

## Format

Creating your own marker file is simple. Create an empty file and enter it using this format:

`x,y,mapindex,name of marker,iconname,color,zoom level`

The `iconname` must match the name of the image in the `Data\Client\MapIcons` folder. If no icon exists, it will display a simple dot using the color defined.

`zoom level` defines when the icon will show/hide when zooming.  `0 = furthest` and `9 = closest` so if you had a marker zoom level set to 1 (for example dungeon entrances), it will show at any zoom level except if you're all the way out (at 0). Default level is 3.
