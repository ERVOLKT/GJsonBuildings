# GJsonBuildings

**-simple osm buildings download webmap-**

This webmapping tool downloads open street map buildings on a leaflet basis.
It downloads from the overpass api and processes the files with help of:
- turf
- osmtogeojson
- jquery

. It also uses:
- leaflet
- hammer

Specify the download area with a zoombox (hold shift and draw rectangle) or by pressing two corners on touch devices.

Results will be saved as `sample.geojson` files within your default download location.

The osm buildings attributes are reduced and changed to have only a "nutzung" (usage) field which was designed for my convenience in field mapping.

_Please use wisely .. it is designed for a "quick and dirty" approach and will possibly not work for larger areas as well._

Find it on https://ervolkt.github.io/GJsonBuildings/
