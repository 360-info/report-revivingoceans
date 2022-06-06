# Data in this report

[`totals`](./totals), which is populated by [`_globalfish.qmd`](../globalfish.qmd), includes figures from the Global Fisheries Landings dataset aggregated by year and by grid cell. The figures are in three formats:

  - [`csv`](./csv): Comma Separated Format files lengthened by year and grid cell. Grid cell location data has been merged in.
  - [`raster`](./raster): GeoTIFFs of the maps. Different measures are included in the same file as separate layers.
  - [`png`](./png): PNG maps rendered with `ggplot2`. Separate measures are rendered as separate maps.

Industrial and non-industrial fishing are computed separately. Measures include:

- Reported catch
- Estimated IUU (Illegal, Unreported and Unregulated) catch
- Estimated discarded fish
- Total catch (reported + IUU)

Figures have been translated from tonnes to kgs/year and kgs per square kilometre per year. Estimated IUU and discard have also been calculated as fractions of the total catch.

## Source

* [Global Fisheries Landings V4.0](https://metadata.imas.utas.edu.au/geonetwork/srv/api/records/5c4590d3-a45a-4d37-bf8b-ecd145cb356d). The accompanying paper is [Watson (2017)](https://www.nature.com/articles/sdata201739).

**Please attribute 360info and the data sources when you use and remix these visualisations.**
