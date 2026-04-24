# SustainWater Map Data

This repository contains the GeoJSON overlay data and reference CSVs used by the SustainWater interactive water testing map.

## Structure

- `data/geojson/` — GeoJSON overlay files for fluoride, hardness, water company boundaries, source protection zones, and ONS boundaries
- `data/csv/` — Reference CSV files including property age by postcode district

## Data Sources

- Fluoride and hardness data derived from DWI consumer guidance maps, Open Government Licence
- Water company boundaries derived from Ofwat data, Open Government Licence
- Source Protection Zone data © Environment Agency, Open Government Licence
- ONS boundary data © Office for National Statistics, Open Government Licence
- Property age data derived from Energy Performance Certificate summary data

## Usage

All files in this repository are fetched directly by the Leaflet map embed via raw GitHub URLs. The repository must remain public for these fetches to work.