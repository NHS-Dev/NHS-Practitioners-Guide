---
title: HRDLPS
template: content-template.html
tags: 
- Hydrology
- Discharge
- Real-time forecast 
---

## ** High Resolution Deterministic Prediction System (HRDLPS) **

### **Overview**

<p>

HRDLPS is a 2.5-km high resolution land surface predicition system that produces high-resolution medium-range forecasts of surface and near surface variables, 
and provides high quality input fields to operational hydrological systems. The system uses <a href = "../../CALDAS-SAT/CALDAS-SAT-2.1.3"> CaLDAS-Sat  </a>  
analyses for initial conditions and forcing fields from HRDPS and GDPS. HRDLPS generates the necessary input fields for the <a href = "../../DHPS/DHPS-3.1.0"> Deterministic Hydrological Prediction System (DHPS) </a>.

</p>

** Current version: ** 2.1 2.0.0 
<br>
<!-- ** Past versions: **

* [x.x](./previous_versions/old_version.md)
* [x.x](./previous_versions/old_version.md)
 -->
### **What is the spatial resolution and coverage of this data?**

<p>

HRDLPS is run on a 2.5-km national grid.

</p>

### **What is available?**

<details>
<summary>What is the timestep and time period covered by this data? </summary>
<br>
<p> HRDLPS is run every 12 hours (00 and 12 Z), and currently produces hourly forecasts up to 6-days (144h) into the future. </p>
</details>

<details>
<br>
<summary>What are the outputs from this product? </summary>
<h5> HRDLPS produces hourly forecasts with lead times up to 144h of near-surface, surface, and sub-surface variables such as:</h5>
<li> 1.5-m temperature and dewpoint, 10-m wind </li>
<li> Surface temperatures (bare ground, vegetation, snow) </li>
<li> Soil mositure </li>
<li> Hourly hydrological fluxes (i.e. subsurface runoff, subsurface lateral flow, and drainage. </li>
<br>
<div class="table-wrapper">
	<table>
		<thead>
			<tr>
				<th>Variable </th>
				<th>Variable long name</th>
				<th>Unit </th>
				<th>Level </th>
				<th>Frequency (analysis/forecast) </th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>ACWF </td>
				<td>Land surface evaporation amount</td>
				<td>kg m-2</td>
				<td>Surface</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>ALAT </td>
				<td>lateral subsurface runoff amount</td>
				<td>kg m-2</td>
				<td> 2m (depth below ground surface)</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>MF </td>
				<td>Model orography</td>
				<td>m</td>
				<td>Surface</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>O1 </td>
				<td>Drainage amount through base of soil model</td>
				<td>kg m-2</td>
				<td>2m (depth below ground surface)</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>TKD </td>
				<td>1.5-m dew point temperature</td>
				<td>K</td>
				<td>1.5m (above ground level) </td>
				<td>12h</td>
			</tr>
			<tr>
				<td>TG </td>
				<td>Aggregate surface radiative temperature</td>
				<td>K</td>
				<td>Surface</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>TJ </td>
				<td>1.5-m air temperature</td>
				<td>K</td>
				<td>1.5m (above ground level)</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>TRAF </td>
				<td>Surface runoff amount</td>
				<td>kg m-2</td>
				<td>Surface</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>WSOL </td>
				<td>Volumetric water content of soil</td>
				<td>m3 m-3</td>
				<td>0.025, 0.075, 0.15, 0.3, 0.7, 1.5, 2.5 (depth below ground surface)</td>
				<td>12h</td>
			</tr>
			<tr>
				<td>WT </td>
				<td>Surface area fraction</td>
				<td>-</td>
				<td>Surface</td>
				<td>12h</td>
			</tr>
	</table>
</div>
</details>

<details>
<summary>How do I access the data? </summary>
<br>
<p> <i> Currently HRDLPS data is only available through ECCC's internal Science Network.</i> </p>
</details>

<details>
<summary>What is the file structure and format?</summary>
<br>
<i> Currently HRDLPS data is available in NetCDF file format, click   <a href = "../../../data_access/file_formats/file_formats">  here  </a>  information on file formats <i>
<br>
<br>
<h4> <i>.tar</i> package for each run contains at <i> .nc </i> for each HRDLPS variable: </h4>
<ul>
<li> <code> ACWF-Accum </code> Contains accumulation of land surface evaporation. </li>
<li> <code> ALAT-Accum </code> Contains lateral subsurface runoff amount 2 m below ground surface. </li>
<li> <code> MF </code> Contains the model orography, which is the  </li>
<li> <code> O1-Accum </code> Contains the drainage amount through base of soil model 2 m depth below surface. </li>
<li> <code> TDK </code> Contains the dew point temperature at 1.5 m above ground level. </li>
<li> <code> TG </code> Contains the surface temperature. </li>
<li> <code> TJ </code> Contains the air temperature 1.5 m above ground level </li>
<li> <code> TRAF </code> Contains the surface runoff amount divided into 5 surface types; "ice_free_land", "land_ice", "ice_free_sea","lake_ice_or_sea_ice", "all_area_types"</li>
<li><code> WSOL_DBS</code> Contains the volumetric water content of soil at 7 depths below surface (0.025, 0.075, 0.15, 0.3, 0.7, 1.5, 2.5 m ).</li>
<li> <code> WT </code> Contains the surface area fraction for each of the 5 surface types; "ice_free_land", "land_ice", "ice_free_sea","lake_ice_or_sea_ice", "all_area_types" </li>

</ul>
<br>
<br>
</details>


<details>
<summary> What is the status of this product? </summary>
<br>
<b>Current Status</b>: Operational
<br>
<p> click  <a href = "../../../additional_information/operational-statuses/operational-status">  here  </a>  for descriptions of various operational statuses </p>
</details>

### **Where can I find additional information?**
** [Technical note](documentation/Tech_note_dhps_v310_e_Final_20210915.pdf) **
<br>
** [Specifications](./) **
<br>
** [Change log](../Status_definitions/status.md) **

### **License**

The [End-User Licence for Environment and Climate Change Canada's Data Servers](../../license/license.md) specifies the conditions of use of this data.
