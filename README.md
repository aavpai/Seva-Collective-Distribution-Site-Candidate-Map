# Seva Second Distribution Site Map

Complete GitHub Pages package.

## Upload
Extract the ZIP and upload the CONTENTS directly to the repository root:

- index.html
- .nojekyll
- README.md
- CHECKSUMS.txt
- data/zip_summary.csv
- data/candidate_summary.csv

Do not upload the enclosing folder.

## GitHub Pages
Settings → Pages → Deploy from a branch → main → /(root)

## Technology
The site uses Leaflet loaded from jsDelivr and standard OpenStreetMap road/city tiles.
There is no CARTO, Mapbox, Google Maps, or API-key tile provider.
The California boundary and Seva data are embedded directly in index.html.

## Privacy
The public map uses aggregated ZIP-level data only. No household street addresses are published.

## Caveat
Travel reductions are preliminary straight-line ZIP-centroid estimates, not household-level driving or public-transit travel times.
