# city-parks

Find parks in your city using OSM maps

## Prep

- Get URL for country OSM PBF file from https://download.geofabrik.de
- Locate GADM file for your country from https://gadm.org
- Get GADM Level 1 (city level) GeoJSON
- Add city key and value from GADM file to `config.json`.

## Run

```
make # Env setup
make country # Get country OSM
make polygon # Create city polygon
make city # Extract city OSM
```

