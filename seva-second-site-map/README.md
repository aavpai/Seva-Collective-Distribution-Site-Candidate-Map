# Seva Second-Site Explorer

Interactive ZIP-level map for exploring potential additional Seva Collective food-distribution locations in Orange County, California.

## What the map includes

- ZIP-level recipient household bubbles
- Recipient-density heat map
- Current Seva distribution site
- Four exploratory candidate ZIP-centroid scenarios
- Approximate travel-burden layer showing straight-line distance from recipient ZIP centroids to the current site

## Data privacy

This repository contains **aggregated ZIP-level data only**. It does **not** contain recipient names, Guest IDs, household addresses, or raw Guest/Visit exports. Do not upload the raw FoodBank Manager exports to a public repository.

## Files

- `index.html` — interactive map; this is the GitHub Pages entry point
- `data/seva_second_site_map_data.csv` — aggregated ZIP-level data used for analysis/reference
- `.nojekyll` — tells GitHub Pages to serve files directly without Jekyll processing

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `seva-second-site-map`.
2. Upload the contents of this folder to the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose the `main` branch and `/ (root)`, then click **Save**.
7. After deployment, GitHub will show the public Pages URL.

The published URL will usually look like:

`https://YOUR-USERNAME.github.io/seva-second-site-map/`

## Interpretation notes

- Candidate points represent ZIP centroids, not recommended facility addresses.
- Travel burden is based on straight-line distance from ZIP centroids, not driving time or transit time.
- The map is intended for exploratory site-planning analysis. A final site decision should also consider existing pantry locations and schedules, facility availability, transportation access, parking, operating costs, and community partnerships.

## Current scenario areas

- 92704 — Southwest Santa Ana
- 92703 — West Santa Ana
- 92707 — South Santa Ana
- 92780 — Tustin / east cluster

## Next analytical upgrade

A stronger site-selection model would overlay existing food-distribution sites and schedules, then compare candidate locations based on recipient density, repeat-use intensity, estimated travel reduction, and existing service coverage.
