Open OSGEO4W prompt
cd folder path
In the folder it is necessary that the raster file has the name imput.tif and the shapefile to cut the area of interest with the name of imput.shp
```
gdalwarp -cutline INPUT.shp -crop_to_cutline -dstalpha INPUT.tif OUTPUT.tif
```
The final clipped file will have the output.tif
