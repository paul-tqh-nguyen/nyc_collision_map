# New York City Motor Vehicle Collisions 

This is an interactive visualization of motor vehicle collisions at varying scales across New York City from 2012-2020. 

The live demonstration can be found at [https://paul-tqh-nguyen.github.io/nyc_collision_map/](https://paul-tqh-nguyen.github.io/nyc_collision_map/).

Feel free to  [reach out](https://paul-tqh-nguyen.github.io/about/#contact)  for help or to report problems or make suggestions for improvement!

### Data Sources

Data was gathered from the following sources:
- [NYC Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- [NYC Boroughs](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm)
- [NYC ZIP Codes](https://github.com/fedhere/PUI2015_EC/blob/master/mam1612_EC/nyc-zip-code-tabulation-areas-polygons.geojson)

### Tools Used

The following tools were heavily utilized to create this visualization:

- [D3.js](https://d3js.org/)
- [Shapely](https://shapely.readthedocs.io/en/latest/manual.html)
- [Pandas](https://pandas.pydata.org/)
- [Pandarallel](https://github.com/nalepae/pandarallel)

Other Python libraries used include [json](https://docs.python.org/3/library/json.html),  [datetime](https://docs.python.org/3/library/datetime.html),  [tqdm](https://github.com/tqdm/tqdm),  [numpy](https://numpy.org/), and  [multiprocessing](https://docs.python.org/3/library/multiprocessing.html).

### Usage:

Click on "Crash Map" in the navigation bar at the top of this page to view the visualization.

The 5 boroughs are shown in different colors. Above them are tooltips showing the number of collisions on the current date.

The current date is shown on the right-hand display panel. The current date can be changed via the date dropdown menu or via the "Previous Date" and "Next Date" buttons.

Click on a borough to zoom in on the borough. The locations of each collision on the current date will be revealed. Hover over them to view details of the collision.

ZIP code boundaries will also be revealed. Hover over the ZIP code regions to view the total number of collisions within the ZIP code. Click on the ZIP code regions to zoom in on them further.

When zoomed in on an individual ZIP code region, click anywhere to zoom back out to view all of New York City.