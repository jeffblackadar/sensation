<p>Macro Paradata:</p>

<ol>
	<li>Why has the resource being created and for what audience?
	<ol style="list-style-type:lower-alpha;">
		<li>This virtual map is created for three audiences
		<ol style="list-style-type:lower-roman;">
			<li>Users who would like to discover landmarks of Hopewell Furnace by walking to a virtual placement of them.</li>
			<li>People who would like to create their own virtual maps.</li>
			<li>Users of Leaflet who may wish to adapt the techniques.</li>
		</ol>
		</li>
	</ol>
	</li>
</ol>

<p style="margin-left:36.0pt;">Although I am working with a specific map, this project could be applied to other maps. Archaeological sites, urban landscapes or even fictional places can be mapped and redrawn around a user&rsquo;s present location.</p>

<p></p>

<ol>
	<li value="2">How will the resource be put to use? Is it sustainable and accessible?
	<ol style="list-style-type:lower-alpha;">
		<li>Maps can be created and used by people as a way to get outside and discover a historical landscape on foot during a time of travel restrictions.</li>
		<li>The code is open and uses open source components. The techniques can be adapted for other projects.</li>
		<li>Creating the maps can be done using Google Colab which is free to users with a computer and internet connection. Using a map as a mobile user does require a smartphone with location services.</li>
	</ol>
	</li>
	<li value="3">Why have you chosen to use the approach/methods applied? (e.g., why is it static or interactive; high or low in detail; photorealistic or schematic; digital or analogue; impressionistic or grounded only in available data; etc.)
	<ol style="list-style-type:lower-alpha;">
		<li>I choose to make an interactive map to encourage people to get a sense of distance and historical landmarks on foot.</li>
		<li>The map is light on detail. It is meant to convey a sense of placement rather than offer great detail. Providing only light detail allowed the project to be completed. I wish I could have added much more historical detail, particularly from the US National Parks website.</li>
	</ol>
	</li>
</ol>

<p></p>

<p>Micro Paradata:</p>

<ol>
	<li>What are the basic steps you followed in putting together the resource?
	<ol style="list-style-type:lower-alpha;">
		<li>Modified an R notebook I had to generate a Leaflet interactive map.</li>
		<li>Created a prototype Leaflet map on an HTML page.</li>
		<li>Added the ability to place the user&rsquo;s location on the map.</li>
		<li>Created a shapefile of points, including metadata from a historical map.</li>
		<li>Programmed a function to transfer the points from the historical map to the user&rsquo;s location.</li>
		<li>Programmed a function to read the shapefile of points and generate instructions to make the map.</li>
		<li>Repeated steps d-f for polygons to represent the landscape.</li>
		<li>Added custom icons and some sound files</li>
		<li>Tested and refined the process.</li>
		<li>Documented instructions</li>
	</ol>
	</li>
</ol>

<p></p>

<ol>
	<li value="2">What supporting evidence did you rely upon?</li>
</ol>

<p style="margin-left:54.0pt;">My main sources of information are the 1860 map and a dataset of locations of charcoal hearths in the area, provided by Dr. Ben Carter. Based on information from the United States National Parks Service, most or all of these charcoal hearths were likely present in 1860, but I don&rsquo;t have the age of each hearth. They are present to provide a sense of what the landscape was like.</p>

<ol style="list-style-type:lower-alpha;">
	<li>The 1860 map of Pennsylvania &ndash; Provided by Dr. Ben Carter</li>
	<li>A shapefile of relic charcoal hearths &ndash; Provided by Dr. Ben Carter and Weston Conner</li>
	<li>United Stated National Parks website for Hopewell Furnace
	<ol style="list-style-type:lower-roman;">
		<li><a href="https://www.nps.gov/hofu/index.htm">https://www.nps.gov/hofu/index.htm</a></li>
		<li><a href="https://www.nps.gov/parkhistory/online_books/popular/14/ps14-1.htm">https://www.nps.gov/parkhistory/online_books/popular/14/ps14-1.htm</a></li>
	</ol>
	</li>
</ol>

<p></p>

<ol>
	<li value="3">How have you acknowledged uncertainty in the resource? Where might alternative interpretations have been made or where are such interpretations otherwise available for viewing audiences to refer to?</li>
</ol>

<p style="margin-left:72.0pt;">As a proof-of-concept I have made a guess at the types of landscape on the map, using topography and the location of features.&nbsp; The areas near building were likely pastures or gardens.&nbsp; The area containing charcoal hearths was likely forest, since trees were the raw material.</p>

<p style="margin-left:72.0pt;">I have added some sounds to provide a sense of some features, such as the furnace.&nbsp; These sounds are just representative and not factual.</p>

<ol style="list-style-type:lower-alpha;">
	<li>For sounds, I added text to the player: &ldquo;Sounds are fictional representations&rdquo;.</li>
	<li>For charcoal hearths, I added the text: &ldquo;The date of construction of this charcoal hearth is unknown. It is possible it was constructed later than 1860.&rdquo;</li>
	<li>For landscape polygons: &ldquo;Landscape types and descriptions are imagined based on the map.&rdquo;</li>
</ol>
