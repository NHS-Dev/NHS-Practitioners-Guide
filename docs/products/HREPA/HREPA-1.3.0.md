---
title: HREPA
template: content-template.html
tags: 
- relevant
- tags
---

## **High-Resolution (2.5 km) Ensemble Precipitation Analysis**

### **Overview**

<p>
HREPA is a system that provides a 24-member set of analysis for accumulations of high resolution precipitation over Canada and northern United States every 6-hours. 
HREPA produces one control member that is equivalent to a deternministic analysis, which combines observations from precipitation gauges and radar precipitation estimates (QPE's). 
The other members follow the same data assimilation approach but use randomly disturbed input data at each valid hour of the analysis.
The ensemble forecast from HREPA is currently integrated as an internal module in CaLDAS as a component of NSRPS.
<br>

</p>

** Current version: ** 1.3.0
<br>
<!-- ** Past versions: **

* [x.x](./previous_versions/old_version.md)
* [x.x](./previous_versions/old_version.md) -->


### **What is the spatial resolution and coverage of this data?**

<p>

HREPA provides analyses and ensemble forecasts over Canada and the United States at a 2.5-km spatial resolution.  

</p>

![alt text](domain-images/domain.png)

### **What is available?**

<details>
<summary>What is the timestep and time period covered by this data? </summary>
<br>
<p> HREPA produces four sets of cumulative precipitation analyses (6-hour amounts per day) valid at synoptic hours (00, 06, 12, and 18Z) each day.  </p>
</details>


<details>
<br>
<summary>What are the outputs from this product? </summary>
<h5>Outputs from HREPA include:</h5>
<ul>
<li>24-member set of analysis for accumulations of high resolution precipitation</li>
<li>one control member that is equivalent to a deternministic analysis</li>
</ul>
<h5>Outputs currently available via NetCDF</h5>
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
				<td>q025 </td>
				<td>25th precipitation amount percentile</td>
				<td>kg/m2</td>
				<td>Surface</td>
				<td>6h</td>
			</tr>
	</table>
</div>
</details>

<details>
<summary>What is the file structure and format?</summary>
<br>
<i> Currently only the 25th precipitation amount percentile estimated through the 25 members of the ensemble is available in the NetCDF file format, click   <a href = "../../../data_access/file_formats/file_formats">  here  </a>  information on file formats </i>
</ul>
</details>


<details>
<summary>How do I access the data? </summary>
<br>
<p> <i> Currently HREPA data is only available through ECCC's internal Science Network.</i> </p>
</details>

<details>
<summary> What is the status of this product? </summary>
<br>
<b>Current Status</b>: Operational 
<br>
<p> click  <a href = "../../../additional_information/Operational-statuses/operational-status">  here  </a>  for descriptions of various operational statuses </p>
</details>

### **Where can I find additional information?**

<b> <a href = https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_capa_hrepa-130_e.pdf > Technical Note </a></b>
<br>
<b> <a href = https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_specifications/tech_specifications_HREPA_1.3.0_e.pdf > Technical Specifications </a></b>
<br>
** [Change log](./path/to/doc) **

### **Product license**

The [End-User Licence for Environment and Climate Change Canada's Data Servers](../../license/license.md) specifies the conditions of use of this data.

 