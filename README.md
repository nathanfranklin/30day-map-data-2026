# 30day-map-data-2026

Static data for the "DesignSafe on the map" story map (#30DayMapChallenge 2026, Day 1 · Points), served with GitHub Pages:

https://nathanfranklin.github.io/30day-map-data-2026/

This repo holds data only. The story's code lives in the `30daymapchallenge-2026` repo, so this one can be replaced or deleted without touching it.

## Files

| File | What it is |
|---|---|
| `day1_designsafe/published_ds_maps_20260818T131449Z.pmtiles` | An unchanged copy of the GeoAPI published-maps archive built 2026-08-18 13:14:49 UTC: every feature from the public Hazmapper maps of DesignSafe published projects, as vector tiles (66 MB, zoom 2–14). |
| `day1_designsafe/story/projects.geojson` | One point per DesignSafe published project event location, from the DesignSafe publications API (snapshot 2026-10-28). 25 locations with a flipped sign are corrected. |
| `day1_designsafe/story/maps.geojson` | One point per public Hazmapper map, with its feature counts and extent, derived from the archive. |
| `day1_designsafe/story/summary.json` | Counts used in the story's text. |

The three `day1_designsafe/story/` files are built by `story_designsafe_points/build_data.py` in the `30daymapchallenge-2026` repo.

## Credits and licences

- **Data:** the data comes from the [NHERI DesignSafe](https://www.designsafe-ci.org/) Data Depot. It belongs to each project's authors and is published under each project's own licence. Please cite the DesignSafe publication of any project you reuse.
- **Archive:** the archive was built by GeoAPI (TACC) from the public Hazmapper maps.
- **This repo:** a mirror of public data. The original archive is listed at `https://hazmapper.tacc.utexas.edu/geoapi/designsafe/published-maps/pmtiles`.

