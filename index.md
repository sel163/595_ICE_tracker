## New Jersey ICE tracker

### Here's my project tracking ICE spottings and comparing them to census data!
Made by Sean Lamb for 545 - Command Line GIS course taught by Professor Will Payne at Rutgers University

<iframe src="ICE_tracker.html" height="855" width="95%"></iframe>

### What's the scoop?
The source for ICE sightings is https://www.stopice.net/. This site collects user-submitted ICE reports. The data is pulled in XML format, clipped to NJ and cleaned manually for any discrepencies. The source is updated daily, but the data is pulled manually for this project. This data was last updated on 12/15/2025.

The source for population data is the American Community Survey 2019 5-year estimates. These were originally downloaded in tabular form and joined to shapefiles at the tract level. Some tracts contained poor data quality estimates which are addressed by white hatching in the static maps.

<iframe src="Foreign-Born_North.png" height="855" width="45%"></iframe>

Notice an issue? Let me know at sean.lamb@rutgers.edu!

You can explore this map [as its own web page here](ice_locations.html).
