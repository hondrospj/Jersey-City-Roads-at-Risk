# Jersey City Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Jersey City municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01392650, Newark
- PETSS / NOAA station: 8530743
- NAVD88 thresholds: 4.27 ft minor, 5.47 ft moderate, 6.97 ft major
- MLLW thresholds: 7.3 ft minor, 8.5 ft moderate, 10 ft major
- MLLW = NAVD88 + 3.03 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Jersey City boundary at 10.0-foot adaptive resolution.
