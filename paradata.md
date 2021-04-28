Macro Paradata: 
1.	Why has the resource being created and for what audience?
   This virtual map is created for three audiences:
      1. Users who would like to discover landmarks of Hopewell Furnace by walking to a virtual placement of them.
      2. People who would like to create their own virtual maps.
      3. Users of Leaflet who may wish to adapt the techniques.

Although I am working with a specific map, this project could be applied to other maps. Archaeological sites, urban landscapes or even fictional places can be mapped and redrawn around a user’s present location.

2.	How will the resource be put to use? Is it sustainable and accessible?
a.	Maps can be created and used by people as a way to get outside and discover a historical landscape on foot during a time of travel restrictions.
b.	The code is open and uses open source components. The techniques can be adapted for other projects.
c.	Creating the maps can be done using Google Colab which is free to users with a computer and internet connection. Using a map as a mobile user does require a smartphone with location services. 
3.	Why have you chosen to use the approach/methods applied? (e.g., why is it static or interactive; high or low in detail; photorealistic or schematic; digital or analogue; impressionistic or grounded only in available data; etc.)
a.	I choose to make an interactive map to encourage people to get a sense of distance and historical landmarks on foot.
b.	The map is light on detail. It is meant to convey a sense of placement rather than offer great detail. Providing only light detail allowed the project to be completed. I wish I could have added much more historical detail, particularly from the US National Parks website.

Micro Paradata: 
1.	What are the basic steps you followed in putting together the resource?
a.	Modified an R notebook I had to generate a Leaflet interactive map.
b.	Created a prototype Leaflet map on an HTML page.
c.	Added the ability to place the user’s location on the map.
d.	Created a shapefile of points, including metadata from a historical map.
e.	Programmed a function to transfer the points from the historical map to the user’s location.
f.	Programmed a function to read the shapefile of points and generate instructions to make the map.
g.	Repeated steps d-f for polygons to represent the landscape.
h.	Added custom icons and some sound files
i.	Tested and refined the process.
j.	Documented instructions

2.	What supporting evidence did you rely upon?
My main sources of information are the 1860 map and a dataset of locations of charcoal hearths in the area, provided by Dr. Ben Carter. Based on information from the United States National Parks Service, most or all of these charcoal hearths were likely present in 1860, but I don’t have the age of each hearth. They are present to provide a sense of what the landscape was like.
a.	The 1860 map of Pennsylvania – Provided by Dr. Ben Carter
b.	A shapefile of relic charcoal hearths – Provided by Dr. Ben Carter and Weston Conner
c.	United Stated National Parks website for Hopewell Furnace
i.	https://www.nps.gov/hofu/index.htm
ii.	https://www.nps.gov/parkhistory/online_books/popular/14/ps14-1.htm

3.	How have you acknowledged uncertainty in the resource? Where might alternative interpretations have been made or where are such interpretations otherwise available for viewing audiences to refer to?
As a proof-of-concept I have made a guess at the types of landscape on the map, using topography and the location of features.  The areas near building were likely pastures or gardens.  The area containing charcoal hearths was likely forest, since trees were the raw material.
I have added some sounds to provide a sense of some features, such as the furnace.  These sounds are just representative and not factual.
a.	For sounds, I added text to the player: “Sounds are fictional representations”.
b.	For charcoal hearths, I added the text: “The date of construction of this charcoal hearth is unknown. It is possible it was constructed later than 1860.”
c.	For landscape polygons: “Landscape types and descriptions are imagined based on the map.”
