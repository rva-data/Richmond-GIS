# \[Unoffocial\] City of Richmond GIS files JSONified

These files were converted from the original shapefile format as
provided to the public by the [City of Richmond's GIS services
group](http://www.richmondgov.com/content/GIS/index.aspx).

The source files can be downloaded via their [FTP
site](ftp://ftp.ci.richmond.va.us/GIS/).

### File organization

The files are organized around the first sub-level of logical
directories in the `Shapefiles` directory with all sub-directories
flattened.

    ├── Basemap
    ├── Centerlines
    ├── Contours
    ├── Environmental
    ├── Landmarks
    ├── Parcels
    └── Thematic

The file `Richmond_City.shp.geojson` is a shapefile for the orthophoto
collection.

### Missing files

Due to considerations around sharing the files simply over Git, the
largest files (over 50M) have been gzipped and kept out of the
repository. These are the files:

- [Basemap/RoadEdge.shp.geojson](http://richmond-gis.s3.amazonaws.com/Basemap/RoadEdge.shp.geojson.gz)
- [Basemap/Structure.shp.geojson](http://richmond-gis.s3.amazonaws.com/Basemap/Structure.shp.geojson.gz)
- [Basemap/TransportationSurface.shp.geojson](http://richmond-gis.s3.amazonaws.com/Basemap/TransportationSurface.shp.geojson.gz)
- [Contours/Contours.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours.shp.geojson.gz)
- [Contours/Contours_NE_a.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_NE_a.shp.geojson.gz)
- [Contours/Contours_NE_b.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_NE_b.shp.geojson.gz)
- [Contours/Contours_NW_a.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_NW_a.shp.geojson.gz)
- [Contours/Contours_NW_b.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_NW_b.shp.geojson.gz)
- [Contours/Contours_SE_a.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_SE_a.shp.geojson.gz)
- [Contours/Contours_SE_b.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_SE_b.shp.geojson.gz)
- [Contours/Contours_SW_a.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_SW_a.shp.geojson.gz)
- [Contours/Contours_SW_b.shp.geojson](http://richmond-gis.s3.amazonaws.com/Contours/Contours_SW_b.shp.geojson.gz)
- [Environmental/ForestCanopy.shp.geojson](http://richmond-gis.s3.amazonaws.com/Environmental/ForestCanopy.shp.geojson.gz)
