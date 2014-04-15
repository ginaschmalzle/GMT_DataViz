GMT Data Visualizations
==========================

Class on using GMT for mapping and data visualization.

See geodesygina.com for more information.

Example data visualization with General Mapping Tools, version 4: http://gmt.soest.hawaii.edu/gmt4/, by Gina Schmalzle, 14APR2014
Be aware that some adjustments to the scripts will need to be made if you are using GMT 5. For exmaple, you will need to write 'gmt' before executing the GMT command.  Also, some of the options have changed.  I plan to make these changes in the near future.


ETOPO1_Bed_g_gmt4.grd is the ETOPO1 topography model taken from <http://www.ngdc.noaa.gov/mgg/global/relief/ETOPO1/data/bedrock/grid_registered/netcdf/ETOPO1_Bed_g_gmt4.grd.gz> 
anss_eq_2000_2012.dat is the file that contains earthquake parameters from the ANSS database, which are labeled inside the file.
cascadia_seis.com A non-verbose version of the code that generates the map
cascadia_seis.ps The postscript image generated
cascadia_seis_wcomments.com A commented version of the code that generates the map
center.dat Defines the center of the projection
projection.dat File generated using GMT's 'project' command.
seis.cpt Color palette file generated in script for earthquake data
topo.cpt Color palette file generated in script for topography data

