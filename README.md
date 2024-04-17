In this code, I have computed the LAI which is very important for monitoring of crop health. You can copy and paste this code into your GEE code editor and change the region of interest according to your interest. 
Thanks!
Formula used: 
1. Enhanced Vegetation Index (EVI) = 2.5*((NIR-RED)/(NIR+6*RED-7.5*BLUE +1))
2. Leaf Area Index (LAI) = (3.618* EVI - 0.118)
Reference:  (Boeghat et al., (2002))

Note: I have used the Sentinel-02 image in this code, but you can change the satellite image according to your preference and change the band number because sentinel and other images have different band numbers and don't match with the sentinel satellite.
