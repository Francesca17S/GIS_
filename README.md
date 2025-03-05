# GIS_

Goal: to observe the global distribution of Greater Flamingos (Phoenicopterus roseus) using research-grade observational data obtained from iNaturalist.
Data were obtained from iNaturalist (iNaturalist. (2025). iNaturalist Research-Grade Observations. Retrieved March 5, 2025, from https://www.inaturalist.org).
5000 observations of Greater Flamingo (Phoenicopterus roseus) were called and filtered (research-grade only) down to 4623 points (as of 5 March 2025).
The data were converted to a shape file.
The coordinate reference system was defined using Transverse Mercator (since I was looking at the global distribution of Greater Flamingos).
A static map and an interactive map were plotted using created shape file.

Packages used:

sf,
rinat,
ggplot2,
rosm,
ggspatial,
leaflet,
htmltools,
mapview,
leafpop,
dplyr,
tidyverse.

Document was knitted as an html document and can be viewed at:
https://htmlview.glitch.me/?https://github.com/Francesca17S/GIS_/blob/main/README.html
