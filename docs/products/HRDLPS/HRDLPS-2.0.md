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
<li> Snow depth </li>
<li> Soil mositure </li>
<li> Hourly hydrological fluxes (i.e. subsurface runoff, subsurface lateral flow, and drainage. </li>
<br>
</details>

<details>
<summary>How do I access the data? </summary>
<br>
<p> <i> Currently HRDLPS data is only available through ECCC's internal Science Network.</i> </p>
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
