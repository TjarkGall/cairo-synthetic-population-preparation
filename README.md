
# Agent-based Simulation for Greater Cairo Region

## Introduction
We're creating an agent-based simulation of the Greater Cairo Region in Egypt. This work should be entirely reproducible, because it only depend on *open data and open software tools*. All the code and instructions to reproduce the simulation are in this repository.

## Downloading the raw datasets
### OSM Buildings/Addresses
We use [HOT Export](https://export.hotosm.org/) to download OSM data.

**Method 1 (Direct Download)**

HOT Export Tool publicly caches exports. So, you can directly download the same exact export data we did at [this link](https://export.hotosm.org/downloads/de73c006-9bbd-43c9-a03d-ff33a9995ad3/GCR_addresses_gpkg.zip)

**Method 2 (Re-create the OSM)**
1. Open the [HOT Export tool](https://export.hotosm.org/). 
2. In the formats tab, the `Geopackage (.gpkg)` option.
3. In the "Data" tab, choose the YAML config option and paste the following configuration
    ```yaml
    planet_osm_point:
    types:
        - points
    select:
        - 'addr:housenumber'
        - 'addr:street'
        - building
        - name
    ```
4. On the right-hand side map, set the bounding box (in the search bar) to `30.5, 29.5, 32.0, 30.5`. The bounding box is in the format `xmin, ymin, xmax,ymax`.
5. Proceed to the export step and download the data.


### Labor Force Survey Data

### MAPTIS Traveller Survey
