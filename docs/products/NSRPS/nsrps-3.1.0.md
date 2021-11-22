# **National Surface and River Prediction System (NSRPS)**

## **Overview**

<p> NSRPS is a Complete hydro-meteorological prediction system, which aims to provide the best possible representation of the current 
and future states of the land surface, as well as the movement of water over and through the soil column and through the lake and river networks. </P>

## **Version Summary**

**Curent Version**: 3.1.0
<br>
**Past Versions**: NA 
<!-- <li> *[old_version](../NSRPS/previous_versions/nsrps.md)</li>
 -->
## **Product Summary**

{{ read_csv('docs/products/NSRPS/nsrps_summary.csv') }}


## **Domain**

<p>Discharge outputs from NSPRS are currently implemented at a 1-km resolution over six major river basins representing ~50% of Canada.

NSRPS is currently established in the following basins: 
<ul>
<li> Yukon River Basin </li>
<li> Mackenzie River Basin </li>
<li> Nelson River Basin  </li>
<li> Churchill River Basin </li>
<li> Great Lakes and St. Lawrence River Basin </li>
</ul> 
</p>

![alt text](NSRPS_domain.png "Title")

 <p> As NSRPS is composed of different sub-systems, both the domain and spatial resolution vary based on the which sub-system the output is derived. </p>
 
## **System Components**
<p> NSRPS is an integrated chain of numerical prediction systems, driven by high-resolution atmospheric forcing fields from the 
High Resolution Deterministic Prediction System (HRDPS). The component systems of NSRPS include: </p>

<details>
<summary>High Resolution Ensemble Precipitation Analysis (HREPA)</summary>
<li> Purpose : Precipitation analyses</li>
<li> Domain : Most of Canada plus transboundary areas of U.S.</li>
<li> Spatial Resolution: 2.5 km </li>
<li> Temporal Resolution : 6-hourly </li>
<li> Frequency : 4x / day at 00, 06, 12 and 18 UTC </li>
<li> Lead-time : 6 days (144 hrs) </li>
<li> Current Version : </li>
<li> Additional Information : </li>
</details>


<details>
<summary> Canadian Land Data Assimilation System (CaLDAS-Sat)</summary>
<li>  Purpose : Land surface analyses </li>
<li>  Domain : Most of Canada plus transboundary areas of U.S. </li>
<li>  Spatial Resolution : 2.5 km </li>
<li>  Temporal Resolution : Hourly </li>
<li>  Frequency : 2x / day at 00 and 12 UTC </li>
<li>  Lead-time : NA </li>
<li>  Current version : 2.1.3 </li>
<li>  additional information :  </li>
</details>


<details>
<summary> High Resolution Deterministic Land Prediction System (HRDLPS)</summary>
<li>  Purpose : Land-surface predictions </li>
<li>  Domain : Most of Canada plus transboundary areas of U.S. </li>
<li>  Spatial Resolution : 2.5 km </li>
<li>  Temporal Resolution: Hourly </li>
<li>  Frequency : 2x / day at 00 and 12 UTC </li>
<li>  Lead-time : 6 days (144 hrs) </li>
<li>  Current Version :  </li>
<li>  Additional Information : </li> 
</details>


<details>
<summary> Deterministic Hydrological Prediction System (DHPS)</summary>
<li>  Purpose :  Flow analyses and predictions </li> 
<li>  Domain : currently established in six major basins, including the Yukon, Mackenzie, Nelson, and Churchill rivers, 
the Great Lakes – St. Lawrence River basin, and the terrain draining into the Gulf of St. Lawrence. The Columbia, Skeena and St. John rivers are currently in development. </li> 
<li> Spatial Resolution : 1 km </li> 
<li> Temporal Resolution : Hourly </li> 
<li> Frequency : 2x / day at 00 and 12 UTC </li> 
<li> Lead-time : 6 days (144 hrs) </li> 
<li> Current Version : </li> 
<li> Additional Information : *[DHPS](../products/DHPS/DHPS-3.1.0.md)* </li>
</li> 
</details>

<details>
<summary> Simulation Hydrodynamique Opérationnel (SHOP)</summary>
<li>  Purpose :  Hydrodynamic analyses and predictions </li> 
<li>  Domain : St. Lawrence River (and some of its larger tributaries?) </li> 
<li>  Spatial Resolution : ~200 m or less </li> 
<li>  Temporal Resolution : Hourly </li> 
<li>  Frequency : 2x / day at 00 and 12 UTC </li> 
<li>  Lead-time : 6 days (144 hrs) </li> 
<li>  Current Version : </li> 
<li>  Additional Information : </li> 
</details>


## **Data Access**

*Currently NSPRS data is only available through ECCC's internal Science Network.*

## **License**

The [End-User Licence for Environment and Climate Change Canada's Data Servers](../../license/license.md) specifies the conditions of use of this data.


## **Status**

**Current Status**: Experimental
<br>
*click [here](../Status_definitions/status.md) for descriptions of different operational statuses*
 
## **Additional Information**

** [Technical note](./Tech_note_dhps_v310_e_Final_20210915.pdf) **
<br>
**Specifications:** 
<br> 
** [Glossary](../../additional_information/glossary/glossary.md ) **
<br>
** [Change log](../Status_definitions/status.md) **