# City of Richmond GeoJSON files

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
repository.
