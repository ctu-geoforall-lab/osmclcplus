# OSM/CLCplus
Supplementary materials for creating hybrid **OSM/CLCplus** land cover tiles for EU countries. This land cover product is based on freely available OpenStreetMap which was processed in several steps. The resulting land cover tiles with a spatial resolution of 2 m contain a total of 19 land cover classes and are available on Zenodo for [2018](https://zenodo.org/records/15039461) and [2022](https://doi.org/10.5281/zenodo.15639392).

## Translation tables
Three translation tables are available.

The translation of OSM polygon elements into LULC classes is contained in the table:

``translation-tables/osm_polygon_to_lulc.csv``

The translation of OSM line elements into LULC classes together with the buffer values is contained in the table:

``translation-tables/osm_line_to_lulc.csv``

The translation of the CLCplus classes is contained in the table:

``translation-tables/clcplus_to_lulc.csv``

## Supplementary tables
Target nomenclature:

``supplementary-tables/lulc_codes.csv``

Codes for individual OSM keys:

``supplementary-tables/osm_key_coding.csv``

Symbology table for resulting raster tiles:

``supplementary-tables/lulc_symbology.csv``

## Tiles
The 30 km × 30 km tiles in GPKG format covering the whole of Europe are available here:

``tiles/osm_tiles.gpkg``

Tables with tile IDs for each country of the European Union are available in the folder:

``country-tiles-id``

## Boundaries for clipping
The tiles can eventually be clipped to the national borders. The borders of each EU country in GPKG format are in the folder:

``boundaries``
