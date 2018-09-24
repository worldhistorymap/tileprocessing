# historymap-tileprocessing
Contains the code to process and raster historical maps for use in map APIs. 

To Use:
For each region that one wants to create raster tiles for: 
Within each base folder (named after each region) for each region:
1) Place all maps from different years in a folder (default name - original)
2) Place mask for maps in a folder (default name-mask)
3) Place gdal translate coordinates for mask in txt file (default name - translate_file.txt)
4) Run raster_tile_workflow.py using the region name as the relevant parameter
