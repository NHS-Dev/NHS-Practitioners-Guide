---
title: File Formats 
template: about-template.html
tags: 
- NetCDF
- FST
---

<header class="major">
	<h2> NetCDF </h2>
</header>
##### File names are structured generally as: 

````
YYYYMMDDTHHZ_ORGANIZATION _DATASET _VARIABLE_LEVEL_GRID_PTXXXH.nc
````

<h5> The elements of the filenames are as follows: </h5>

| String      | Description |
| ----------- | ----------- |
| **YYYYMMDDTHHZ**      | The issue date and time       |
| **ORGANIZATION**   |  Refers to the group that creates the files        |
| **DATASET**      | Refers to the forecast model. If the data is an analysis the format is MODEL-Analysis.       |
| **LEVEL**      | Refers to the vertical coordinate (pressure level, surface, sub-surface, etc.).  DBL = Depth Below Surface, AGL =  Above Ground Level   |
| **GRID**   |  Refers to to the projection and grid resolution in degrees      |
| **PTXXXH**   | Refers to the forecast hour. If not applicable, the default is PT0H (e.g. analyses)         |
 
##### An example file name:
````
20211201T00Z_MSC_DHPS_River-Discharge_Sfc_ RLatLon0.008_PT001H.nc 
````

<header class="major">
	<h2> <i>.tar</i> package contents  </h2>
</header>


##### All files from a single run are merged into a tar file package. The tar packages follow the name convention: 
````
YYYYMMDDHH_ORGANIZATION _MODEL.nc.tar
````

<p> 
<b> File names and formats will vary based on the product. Refer to <a href="../../../available-datasets" > individual product </a> pages for more information. </b>
</p>
