# Sao Paulo Floods Project Workflow 
----
# Geocoding floods using Google Maps 
* Using 2016 - 2017 floods data, generate unique LOCAL - REFERENCIA pairs 
* Using Google Maps, look up locations for LOCAL - REFERENCIA pairs 
* See Appendix for which segments were omitted and why
* Save as KML file
* Import KML file into ArcMap (Conversion Tool -> From KML)
* Generate X and Y coordinates using ArcMap (In attribute table, Add Field -> Calculate Geometry)
* X = LONG, Y = LAT
* Save as shapefile 
* Load shapefile on Rstudio
* Save coordinates as data frame 
* Write coordinates data frame to xlsx
* Merge using coordinates with road segment names using Google Sheets
