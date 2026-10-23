TURNER THEN & NOW - HISTORIC HOMESITE MAP V2
================================================

IMPORTANT: Use in a normal HTTPS web browser, preferably GitHub Pages.
Some iPhone file previews (including previews inside chat apps) block interactive scripts and remote map images, producing a blank map. Do not rely on the in-chat HTML preview.

GitHub Pages deployment:
1. Create a public repository on GitHub (or use one with Pages access).
2. Upload the included index.html into the repository root.
3. Go to Settings > Pages. Under Build and deployment, choose Deploy from a branch > main > / (root), then Save.
4. After deployment, open your GitHub Pages URL in Safari on your phone. The URL usually looks like https://YOURNAME.github.io/REPOSITORY/.
5. The map uses live imagery (online connection needed).

FEATURES
- Drag, wheel, pinch/zoom Turner map.
- Compare 1997 and 2024 county aerial tile services via slider.
- Street map fallback if either aerial service fails.
- Tap any point for GPS coordinates and an attempt to look up the county parcel.
- Save leads on device, export a CSV, copy permission letter.
- Links to 1885 Edwards historical map and 1941 aerial index.

CAUTIONS
The 1885 and 1941 resources are not aligned overlays in v2. No historical homesites have been independently pinpointed. Parcel data is provisional and can be unavailable depending on browser/network. Verify owners at the official county appraiser before contacting them. Obtain permission before metal detecting.

MAP SOURCES
1997: https://tiles.arcgis.com/tiles/Qo2HHQp8vgPs2wg3/arcgis/rest/services/Aerial_Photos_1997/MapServer
2024: https://tiles.arcgis.com/tiles/Qo2HHQp8vgPs2wg3/arcgis/rest/services/i2024_v7/MapServer
Parcel: https://gisweb.wycokck.org/arcgis/rest/services/GISPUB/UGMAPS_4_V02/FeatureServer/0
1885: https://www.loc.gov/item/2012593083/
OSM: https://www.openstreetmap.org/

Validation: JavaScript syntax checked, UI map rendering/panning/selection/saved-list controls tested in headless Chromium using mocked tile and parcel responses. Live aerial image loading on your phone has not been independently verified.
