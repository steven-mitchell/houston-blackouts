# Houston Blackouts
**Identifying the impacts of extreme weather**

### Purpose
This repository demonstrates my analysis of the 2021 blackouts in Houston resulting from an extreme winter storm.

### Skills and Techniques Demonstrated
- Manipulating raster data
- Manipulating vector data
- Spatial joins across data types
- Spatial analysis across data types


### Contents
```
.
├── README.md
├── gitignore
├──houston-blackouts.Rproj
├──houston-blackouts.html   # rendered report document
├──houston-blackouts.qmd    # non-rendered report with raw code
├──data                         # too large for github: see Data section
│   ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb     # census tract data
│   ├── gis_osm_buildings_a_free_1.gpkg     # data on buildings
│   ├── gis_osm_roads_free_1.gpkg           # data on roads
│   └── VNP46A1                             # rasters of night light data
│       ├── VNP46A1.A2021038.h08v05.001.2021039064328.tif
│       ├── VNP46A1.A2021038.h08v06.001.2021039064329.tif
│       ├── VNP46A1.A2021047.h08v05.001.2021048091106.tif
│       └── VNP46A1.A2021047.h08v06.001.2021048091105.tif
└──outputs
    ├── map_0207.png
    ├── map_0216.png
    ├── map_blackout_homes.html
    ├── map_blackout_tracts.html
    ├── plot_unaffected_income.png
    └── plot_blackout_income.png

```
### Data
The data used in this analysis is too large to be hosted on GitHub. Instead, download the data  <a href="https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view?usp=drive_link"> here </a> as a zipped folder, unzip, and move into the R project manually.


### Acknowledgements
This analysis and workflow was originally created by Dr. Ruth Oliver of the Bren School of Environmental Science & Management for the Masters of Environmental Data Science course, Geospatial Analysis and Remote Sensing. My initial work through of this analysis was conducted as part of a homework assignment for this class, and I later polished up this repository.

# Citations
| Data | Link |
| -----|  ------|
| Night Lights | https://ladsweb.modaps.eosdis.nasa.gov/|
| Open Street Map Roads | https://planet.openstreetmap.org/ |
| Open Street Map Buildings | https://planet.openstreetmap.org/ |
| Socioeconomic Data | https://www.census.gov/programs-surveys/acs |