# Data overview

This folder stores raw and processed geospatial data used in the High Mountain Asia (HMA) water project.

## Directory structure

The tree below lists the main folders and selected files. Individual tiles, station records, and supporting documents are omitted for brevity.

```text
data/
├── basemap/
│   └── ne_10_coastline.gpkg
├── climate/
│   ├── cmip6/
│   │   ├── historical/
│   │   ├── ssp126/
│   │   ├── ssp245/
│   │   └── ssp585/
│   ├── era5_from_gee/
│   └── hma_era5_land_monthly_mean/
├── dem/
│   ├── hma-subregions/
│   ├── tiles/
│   ├── dem_stats.gpkg
│   ├── hma_SRTMGL3.tif
│   └── hma_SRTMGL3_005deg.tif
├── hma_extent/
│   ├── TPlateau/
│   ├── basins/
│   ├── hma/
│   ├── permafrost/
│   ├── hma_tiles_100km_buf10km.gpkg
│   └── hma_tiles_1deg_buf01deg.gpkg
├── lake/
│   ├── hydrolake_hma/
│   │   └── HydroLakes_v10_hma.gpkg
│   ├── rsimg_site/
│   ├── sui2025_hma_lakes/
│   ├── wang2026_tibet_lakes/
│   ├── GLWD_L1.gpkg
│   └── GLWD_L1_hma.gpkg
├── reservoir/
│   ├── GDW_reservoirs_v1_0.gpkg
│   ├── GDW_reservoirs_v1_0_hma.gpkg
│   ├── gdw_barriers_v1_0.gpkg
│   ├── hma_GDW_reservoirs.gpkg
│   └── hma_GDW_reservoirs_stat.gpkg
├── river/
│   ├── global_major_rivers.gpkg
│   ├── hma_major_rivers.gpkg
│   └── hma_rivers_reaches_sword_v16.gpkg
├── validation/
│   ├── lake_bathymetry/
│   ├── lake_height/
│   │   ├── lake_station.gpkg
│   │   └── lake_station_lakes_all.csv
│   └── lake_sample_2020.gpkg
├── water_height/
│   ├── TP_lakeVolumeChange_1970_2020_v20220408/
│   ├── dahiti/
│   ├── hydroweb/
│   │   ├── hma_lakes/
│   │   └── hydroweb_stations_hma.gpkg
│   └── merged_data.gpkg
└── readme.md
```

## Data folders

- `basemap/`: background maps, relief rasters, and coastline data.
- `climate/`: CMIP6 historical and scenario data, ERA5-Land data, and derived climate statistics.
- `dem/`: SRTM elevation data, regional and tiled DEMs, and terrain statistics.
- `hma_extent/`: HMA and Tibetan Plateau boundaries, subregions, river basins, permafrost maps, and processing grids.
- `lake/`: HydroLAKES and GLWD inventories, published HMA and Tibetan Plateau lake datasets, and selected satellite imagery.
- `reservoir/`: Global Dam Watch reservoir and barrier datasets, HMA subsets, and reservoir statistics.
- `river/`: global and HMA major rivers, and SWORD river reaches for HMA.
- `validation/`: in situ lake water levels, station locations, bathymetry, and lake validation samples.
- `water_height/`: DAHITI and Hydroweb water-level products, lake volume-change data, and matched water-level observations.
