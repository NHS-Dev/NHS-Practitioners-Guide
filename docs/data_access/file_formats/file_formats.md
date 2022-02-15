---
title: File Formats 
template: about-template.html
---
<header class="major">
	<h2> CMC file naming convetions </h2>
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

<p> 
<b> File names and formats will vary based on the product. Refer to <a href="../../../available-datasets" > individual product </a> pages for more information. </b>
</p>


<header class="major">
	<h2> GRIB </h2>
</header>
<p>
GRIB (GRIdded Binary) is a mathematically concise data format commonly used in meteorology to store historical and forecast weather data.
It is standardized by the World Meteorological Organization's for archiving and exchanging gridded data. GRIB is a binary format, and data is packaged to decrease file size.
CMC uses the GRIB-2 convention for he storage and transport of gridded meteorological data, such as Numerical Weather Prediction model output.
</p>
<b> Note: </b> Variable names for GRIB2 files may differ from both the standard files and NetCDF files. 

<h3> Using GRIB2 data </h3>

<header class="major">
	<h2> NetCDF </h2>
</header>

<p> 
NetCDF (Network Common Data Form) is a set of software libraries and self-describing, machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data. 
NetCDF is commonly used to store and distribute scientific data. 
NetCDF data has an <i> .nc </i> extension. 
</p>



<h3> <i>.tar</i> package contents  </h3>

##### All files from a single run are merged into a tar file package. The tar packages follow the name convention: 
````
YYYYMMDDHH_ORGANIZATION _MODEL.nc.tar
````

<h3> Using NetCDF data </h3>
