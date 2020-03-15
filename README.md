# gee
Recently, I am a contributor in real-world AI challenge organized by Omdena, hosted by Nigeria-based NGO. This challenge aims to spot suitable area for installing solar panel. It is due to the estimation that half of Nigeria population (198 millions) are living without/shortage of electricity. 
This repository collect script solving the challenge. There are more than 30 data scientists, AI expert working on this project so scripts, ideas are not is not only contributed by me. 
We was using night time light satellite image from VIIRS as proxy for have/have not energy area and worldpop data as population in Negeria. Mapping this two satellite images to filter out pixel without energy but populated. These pixels will be clusters to area and ranking from most priority to least one due to some factors: number of school/hospital, area, close/not close to national electrical grid, population. 
The repo includes: 
  + Function to download satellite image from Google Earth Engine to google drive via Python in GEOTIFF format
  + Mapping two .tiff file
  + clustering satellite image
  + Assign cluster centroid to it's political administrative level 3
  + Ranking most suitable area. 

