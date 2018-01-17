EARTHQUAKE
LAB: EARTHQUAKE
Save your solution in a directory in practice/, in a branch, and make a GitHub pull request all named earthquake.
Your HTML file should be named index.html, your CSS file named site.css, and your JS file named site.js in that directory.

The USGS has feeds of earthquake locations.
Using their feed of all earthquakes over the past seven days, and the OpenLayers JS library, create a map visualization of all of the earthquakes.

Asynchronously download the most recent earthquake data
Display earthquake locations on a map as dots
USING OPENLAYERS
In general when starting to use a new library, I try to read the super basic tutorials first, to get a sense of the vocabulary.
Then, I try to find examples that do something like or some of what my goal is and look at their code and understand it.
Then, I look at API docs to see the specifics of function calls and creating data of the correct type.

Start by reading the concept tutorial to get an idea of what are the nouns that OL uses.

Then take a look at the Synthetic Points example.
It randomly generates a ton of points and places them on a map.
You’re doing something similar but with non-random data.

Map projections are a pretty complicated topic to fully understand, but for this problem you only need to know two basic facts.
The points from the data source are in the EPSG:4326, or WGS84 or latitude and longitude in degrees.
Almost all web maps use EPSG:3857, or Web Mercator projection, and OpenLayers uses that by default on basic maps.
Thus, if you want to properly render a latitude longitude pair on those maps, run it through ol.proj.fromLonLat([lon, lat]) first and add that to the map source.

ADVANCED
Have the size of each dot correspond to the strength of the earthquake
Have the opacity of each dot correspond to how old the earthquake event is
The Icon Colors example shows how to assign different styles to different points.

The feed is updated every five minutes, so have your page automatically fetch new data on that interval
SUPER ADVANCED
Display a special animation for new earthquake points.

There’s some animation functions as part of OpenLayers.
Check out the Custom Animation example
CSS animations also might come in handy.