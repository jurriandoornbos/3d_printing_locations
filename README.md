A tutorial on how to make your own 3d-printable areas. This deals with how you can get some of the nice dataand visualizations to print. I delved more into the Netherlands side of it, and that can go a bit nicer as I know which government data is available. 

The broad idea here is to get your data all nicely aligned to a grid of squares which will fit the printerbed. Then cut the data out to that area, attach it to the square and export as stl's.


# Other countries 
There is probably better ways to go about this, but I did not research it, and this is probably good enough for some basic prints.

## Pre-requisites
- Install Blender + BlenderGIS (Not necessary to get GDAL installed, we'll be working with open-source data from OpenStreetMap, and no conversions are necessary)


# Netherlands
There is a million ways to go about this ofcourse, I present here a few steps to get (for NL): 
You can of course do only a single step of these.

1. Buildings, 
2. A terrain model (basically the elevation of the area DEM/DTM) 
3. Roads 
4. Water

## Pre-requisites
- Install Blender + BlenderGIS (Preferably with GDAL also installed, see their [Github page](https://github.com/domlysz/BlenderGIS/wiki/Install-and-usage) about that).
- Figure out where the data-files from your government/state/municipality are (they have a LOT of info/data about their areas, so dive into that).
