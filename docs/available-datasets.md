---
template: content-template.html
---
### Available Products 

<p> The Canadian Meteorological Centre(CMC) is a part of Environment and Climate Change Canada and is
 responsible for producing and disseminating a number of numerical weather and hydrological prediction products. A number of these products are summarized below. </p>

**What products are available?**
 
<details>
<summary>Hydrologic Prediction </summary>
<br>
<p> <i> Summary Table </i> </p>
</details>

<details>
<summary>Atmosphere </summary>
<br>
<p> <i> Summary Table </i> </p>
</details>

<details>
<summary> Other </summary>
<br>
<p> <i> Summary Table </i> </p>
</details>
 
 
### Product Summary Table

Category | Sub Category | Product | Highlights | Spatial Coverage | Spatial Resolution | Temporal Resolution | Data Access
------------ | -------------| ------------- | ------------ | ------------ | ------------ | ------------ | ------------
 Hydrologic Prediction |Comprehensive System | <a href="./../products/NSRPS/nsrps-3.1.0"> National Surface and River Prediction System (NSRPS) | Network of  independent modelling systems. Precipitation, evaporation, surface runoff, lateral subsurface flow and drainage. Includes: DHPS, EHPS, SHOP. (see flow chart) | Varies with system | Varies with system | Varies with system | Varies with system
 Hydrologic Prediction | Sub-System | <a href="./../products/DHPS/DHPS-3.1.0"> Deterministic Hydrologic Prediction System (DHPS), [Tech doc](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_dhps-310_20211130_e.pdf) | 1D streamflow, lake levels | 6 major Canadian river basins and large water bodies, expanding in 2023 (see map) | 1km | Frequency: 00 and 12Z, 6 day forecast, Hourly Output | Experimental, secured access. Coming to MSC Open Data, Spring 2023
 Hydrologic Prediction | Sub-System | Ensemble Hydrological Prediction System (EHPS), [Tech doc](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_ehps_e.pdf)  | 1D Rivers, 20 members | Great Lakes, St Lawrence, Nelson and Churchill, expanding in 2023 (see map) | 1km | Frequency (??), 16/32 day | Experimental, secured access. Coming to MSC Open Data, Spring 2023
 Hydrologic Prediction | Sub-System | Simulation Hydrodynamique OPérationnelle (SHOP), [Tech doc](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_shop_e.pdf)  | Water level and velocity. (many other variables??) One member |St. Lawrence | (??) | Frequency 6h, 48h forecast, 6h analysis | n/a
 Hydrologic Prediction | Land Surface | <a href="./../products/HRDLPS/HRDLPS-2.0"> High Resolution Deterministic Prediction System (HRDLPS), [Tech doc](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_shop_e.pdf) | Surface, near surface, input fields for hydro systems. Forecasts of soil moisture, snow, temp, humidity, wind  | Canada | 2.5km | Frequency: 00 and 12Z, Medium Range, 3-6 day (??)  | (??)
 Hydrologic Prediction | (??) | [Water Cycle Prediction System (WCPS)](https://eccc-msc.github.io/open-data/msc-data/nwp_wcps/readme_wcps_en/), [Tech doc](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_wcps_e.pdf)  | Atmosphere-ocean-ice, river flows | Great Lakes, St Lawrence, Gulf of St. Lawrence | 10km (atmosphere, land, soil). 1km (marine ice, rivers) | (??) | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 Hydrologic Prediction  | (??) | Regional Deterministic Prediction System – Coupled to  Gulf of St Lawrence (RDPS-CGSL), [Tech doc](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/lib/technote_rdps-cgsl_e.pdf) | 1D rivers, one member | map (??) | 1km | (??) | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 Hydrologic Prediction  | Land Surface | Canadian Land Data Assimilation System (CaLDAS) in NSRPS, [Fact Sheet](https://collaboration.cmc.ec.gc.ca/cmc/cmoi/product_guide/docs/fact_sheets/factsheet_caldas-nsrps-310_e.pdf), [Tech doc](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_caldas-nsrps_e.pdf) | Produces land surface analyses for numerical weather predictions. Includes snow pack. | [Canada and Northern US](https://eccc-msc.github.io/open-data/msc-data/nwp_caldas-nsrps/readme_caldas-nsrps-datamart_en/) | 2.5km  | 4x per day | [MSC Testing Data Repository](https://eccc-msc.github.io/open-data/msc-data/nwp_caldas-nsrps/readme_caldas-nsrps-datamart_en/)
  | | | | | | | 
  | | | | | | | 
 Atmosphere| Precipitation Analysis | Regional Deterministic Precipitation Analysis (RDPA) | Best estimate of the amount of precipitation. Preliminary estimate is available approximately 1h after the end of the accumulation period, and revised 6h after | Canada, US, Mexico | 10km, surface level | 4x per day.  6h intervals and once a day for the 24h interval |  [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 Atmosphere| Precipitation Analysis | High Resolution Deterministic Precipitation Analysis (CaPA-HRDPA) | Best estimate of 6 and 24 hour precipitation amounts | Most of Canada and part of US (see map) |10km | 12 analyses per day. Four analyses of 6 hour amounts per day, valid at synoptic hours (00, 06, 12 and 18 UTC) and two 24 hour analyses valid at 06 and 12 UTC | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere| Precipitation Analysis | High Resolution Ensemble Precipitation Analysis (CaPA-HREPA) | Ensemble version of CaPA-HRDPA, 25 members.  Optimal precipitation estimate over 6 and 24 hour accumulation periods  | Most of Canada and part of US (see map) | 2.5km | Two deterministic configurations of the analysis produce four 6-hour cumulative analyses valid at synoptic times (00, 06, 12, and 18 UTC) and two 24-hour analyses valid at 06 and 12 UTC | MSC testing data repository DD-Alpha
 Atmosphere| Precipitation Analysis | High Resolution Deterministic Precipitation Analysis watershed | Average watershed precipitation. Best estimate of 6 and 24hr precipitation amounts | Most of Canada and part of US (see map) | 2.5km | 10 analyses per day. Four analyses of 6 hour amounts per day, valid at synoptic hours (00, 06, 12 and 18 UTC) and one 24 hour analysis valid at 12 UTC | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart) 
  | | | | | | |  
  | | | | | | |  
 Atmosphere | Deterministic | Global Deterministic Prediction System (GDPS) | Temperature, precipitation, cloud cover, wind speed and direction, and humidity | Global | 15km, 33 vertical levels | 2x per day, 10 days into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere | Deterministic | Regional Deterministic Prediction System (RDPS) | Temperature, precipitation, cloud cover, wind speed and direction, and humidity | Canada and US | 10km, 33 vertical levels | 4x per day, 84 hrs into the future| [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)  
 Atmosphere | Deterministic | High Resolution Deterministic Prediction System (HRDPS) | Temperature, precipitation, cloud cover, wind speed and direction, humidity and others | Most of Canada | 2.5km, 31 vertical levels | 4x per day, 48 hrs into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/) 
 Atmosphere | Ensemble | Global Ensemble Prediction System (GEPS) | Probabilistic. Temperature, precipitation, cloud cover, wind speed and direction, humidity and others. Ensemble of 20 scenarios. | Global | .35 degree, 84 vertical levels | (??), 16 days into the future, 1x per week for forecast of 32 days into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere | Ensemble | North American Ensemble Forecast System (GEPS – NAEFS) | Combined ensemble forecasts, seamless across national boundaries | Canada, US, Mexico | (??) | 1 to 14 days into the future| [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/)
 Atmosphere | Ensemble | Regional Ensemble Prediction System (REPS) | Probabilistic predictions of temperature, precipitation, cloud cover, wind speed and direction, humidity and others. 20 ensemble members  |  Canada and US  | 15km and 10km, 24 vertical levels | 4x per day, 3 days into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere | Seasonal | Canadian Seasonal to Inter-annual Prediction System (CanSIPS) | Probabilistic predictions of temperature, precipitation, wind speed and direction and others | Global | 2.5 and 1.0 degrees and for a few selected vertical levels. | Monthly.  Predictions up to 12 months into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 | | | | | |
 | | | | | | 
Other Products | | | | | |  
 Other | Reanalysis | Regional Deterministic Reanalysis System (RDRS) | 40+ year reanalysis | | | |[CaSPAr](https://github.com/julemai/CaSPAr/wiki/Available-products)
 Other | Station Database | Canadian historical Snow Water Equivalent dataset (CanSWE) | Database of snow observations | Canada (see map) | Observation stations | Updated annually |  [Publication and Data](https://zenodo.org/record/4734372#.Y8WxHJjMKUk)
 Other | Station Data | Adjusted and Homogenized Canadian Climate Data (AHCCD) | Adjusted and homogenized air temperature, rainfall, snowfall, total precipitation, wind speed and atmospheric pressure (see more info) | Canada | Between 330 and 630 locations | Annual, seasonal, monthly, daily and hourly dependent on variable of interest (see more info) 1900-01-01 to 2012-12-31 | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 | | | | | |  


 
 <p> 
<b> Click  <a href="../about" > here </a> to learn more about CMC and the NHS Practitioners guide. </b>
</p>

<section>
	<div class="posts">
		<article>
			<a href="#" class="image"><img src="images/pic01.jpg" alt="" /></a>
			<h3>Forecast Data</h3>
			<div class="row">
				<div class="col-12 col-12-small">
				<ul class = "alt">
					<li> <a href="./../products/DHPS/DHPS-3.1.0"> Deterministic Hydrologic Prediction System (DHPS) </a></li>
					<li> <a href="./../products/HRDLPS/HRDLPS-2.0"> High Resolution Deterministic Prediction System (HRDLPS) </a></li>
				</ul>
				<br>
		</article>
		<article>
			<a href="#" class="image"><img src="images/pic01.jpg" alt="" /></a>
			<h3>Analysis and Re-analysis Data</h3>
			<div class="row">
				<div class="col-12 col-12-small">
				<ul class = "alt">
					<li> <a href="./../products/HREPA/HREPA-1.3.0"> High-Resolution (2.5 km) Ensemble Precipitation Analysis (HREPA) </a></li>
					<li> <a href="./../products/DHPS/DHPS-3.1.0"> Deterministic Hydrologic Prediction System (DHPS) </a></li>
				</ul>
				<br>
		</article>
		<article>
			<a href="#" class="image"><img src="images/pic01.jpg" alt="" /></a>
			<h3>Systems </h3>
			<div class="row">
				<div class="col-12 col-12-small">
				<ul class = "alt">
					<li> <a href="./../products/NSRPS/nsrps-3.1.0"> National Surface and River Prediction System (NSRPS) </a></li>
					<li> <a href="./../products/CAPA/CAPA-Systems"> Canadian Precipitation Analysis System (CaPA) </a></li>
				</ul>
				<br>
		</article>
</section>
