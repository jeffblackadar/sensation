These are notes about making items for this project.

## Icons
### Making icons
* Used MS Paint.
* Resized to 32X32
* Magnified to 800%
* Used a simple design
* Employed some symbols from the Webdings font at 24pt size
* Named the png files with a _p

#### Make the icon background transparent
* Opened icon in Irfanview
* Saved as a new file without _p in the name.
* Specified Transparent and selected the background color on save.

## Designing the map
* Used QGIS
* Created a new project
### Added map as raster layer 
* Added the georeferenced map tif as a raster layer
* Added the shapefile of charcoal hearth points as a vector layer.
### Created a new Vector layer for Points
* file name: hopewell_selected_elements
* geometry: Points
* crs:EPSG:4326

Added fields
* type (string length 40)
* name (string length 80)
* desc (string length 254)

Added points for buildings and charcoal hearths

### Created a new Vector layer for Polygons
* file name: hopewell_selected_elements_polys
* geometry: Polygons
* crs:EPSG:4326

Added fields
* type (string length 40)
* name (string length 80)
* desc (string length 254)
 
Added polygons for landscapes (forest, field, creek, road, path)

## Sounds
I used freesound.org 
https://freesound.org/ . Sounds are licenced under Creative Commons.
I used Audacity https://www.audacityteam.org/ to edit the sounds.


* Furnace https://freesound.org/people/jokallset/sounds/395883/
* Road (horse) https://freesound.org/people/lefthandwinnie/sounds/403150/
* Path (footsteps, mud) https://freesound.org/people/mikaelfernstrom/sounds/68689/
* RCH (Charcoal raked by a spade) https://freesound.org/people/Hotlavaman/sounds/108676/
* Creek https://freesound.org/people/Zaku18/sounds/255246/
