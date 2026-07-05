# MapIQ Data Files

This folder keeps large quiz datasets out of `index.html` so each game mode can load only what it needs.

## Files

- `metadata/countries.json`: country metadata, ISO codes, capitals, regions, timezones, currency, translations.
- `metadata/states.json`: global state/region/province metadata keyed back to country codes.
- `shapes/countries-110m.json`: small country TopoJSON for fast globe rendering.
- `shapes/countries-50m.json`: medium country TopoJSON.
- `shapes/countries-10m.json`: detailed country TopoJSON.
- `shapes/us-states-10m.json`: U.S. state TopoJSON.
- `shapes/us-counties-10m.json`: U.S. county TopoJSON, also includes states and nation objects.
- `flags/*.svg`: 4x3 flag SVGs.
- `flag-index.json`: list of available flag SVG codes and paths.
- `data-manifest.json`: machine-readable index of these files and sources.

## Sources

- Countries/states: https://github.com/dr5hn/countries-states-cities-database, ODbL-1.0 attribution required.
- Country shapes: https://github.com/topojson/world-atlas, ISC.
- U.S. shapes: https://github.com/topojson/us-atlas, ISC.
- Flags: https://github.com/lipis/flag-icons, MIT.

The downloaded `sources/` archives and full city import are kept local only; they are not tracked in Git.
