---
template: content-template.html
---

### Product Summary Table

Category | Product | Highlights | Spatial Coverage | Spatial Resolution | Temporal Resolution | Data Access
------------ | ------------- | ------------ | ------------ | ------------ | ------------ | ------------
 Hydrologic Prediction | <a href="./../products/NSRPS/nsrps-3.1.0"> National Surface and River Prediction System (NSRPS) | Network of  independent modelling systems. Precipitation, evaporation, surface runoff, lateral subsurface flow and drainage. Component models include: HREPA, CaLDAS-Sat, HRDLPS, DHPS/EHPS, SHOP (see below). | Varies with system | Varies with system | Varies with system | Varies with system
 Hydrologic Prediction | <a href="./../products/DHPS/DHPS-3.1.0"> Deterministic Hydrologic Prediction System (DHPS), [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_dhps-310_20211130_e.pdf) | 1D streamflow, lake levels. Component of NSRPS | 6 major Canadian river basins and large water bodies, expanding in 2023 | 1km | Frequency: 00 and 12Z, 6 day forecast, Hourly Output | Experimental, secured access. Coming to MSC Open Data, Spring 2023
 Hydrologic Prediction | Ensemble Hydrological Prediction System (EHPS), [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_ehps_e.pdf)  | 1D Rivers, 20 members. Component of NSRPS. | Great Lakes, St Lawrence, Nelson and Churchill, expanding in 2023 | 1km | Once per day (16 day forecast), Thursdays (32 day forecast) | Experimental, secured access. Coming to MSC Open Data, Spring 2023
 Hydrologic Prediction | Simulation Hydrodynamique OPérationnelle (SHOP), [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_shop_e.pdf)  | Water level and velocity. One member. Component of NSRPS. |St. Lawrence | <200m | Frequency 6h, 48h forecast, 6h analysis, 3 minute time step | Experimental, secured access. Coming soon to MSC Datamart and GeoMet
 Hydrologic Prediction | <a href="./../products/HRDLPS/HRDLPS-2.0"> High Resolution Deterministic Prediction System (HRDLPS) | Surface, near surface, input fields for hydro systems. Forecasts of soil moisture, snow, temp, humidity, wind. Component of NSRPS.  | Canada | 2.5km | Frequency: 00 and 12Z, Medium Range, 6 day forecast  | [Datamart Alpha (Testing Repository)](https://dd.alpha.weather.gc.ca/model_hrdlps/)
 Hydrologic Prediction | High Resolution Ensemble Prediction System (HRELPS) | Ensemble version of HRDLPS. Produces 21 hourly forecast members during each run. Component of NSRPS.  | Canada | 2.5km | Frequency: Once per day for forecasts with lead times of up to 16 days. Once per week on Thursdays for 32 day forecast. | In progress
 Hydrologic Prediction | [Water Cycle Prediction System (WCPS)](https://eccc-msc.github.io/open-data/msc-data/nwp_wcps/readme_wcps_en/), [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_wcps_e.pdf)  | Atmosphere-ocean-ice, river flows | Great Lakes, St Lawrence, Gulf of St. Lawrence | 10km (atmosphere, land, soil). 1km (marine ice, rivers) |  Hourly from 00Z to 84Z, 4 times a day | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 Hydrologic Prediction  | Regional Deterministic Prediction System – Coupled to  Gulf of St Lawrence (RDPS-CGSL), [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/lib/technote_rdps-cgsl_e.pdf) | 1D rivers, one member | Gulf of St. Lawrence | 1km | Four times a day for 00z, 06z, 12z and 18z initialization times for a forecast horizon of 48 hours | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 Hydrologic Prediction  | Canadian Land Data Assimilation System (CaLDAS) [Fact Sheet](https://collaboration.cmc.ec.gc.ca/cmc/cmoi/product_guide/docs/fact_sheets/factsheet_caldas-nsrps-310_e.pdf), [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_caldas-nsrps_e.pdf) | Produces land surface analyses for numerical weather predictions. Includes snow pack. Component of NSRPS. | [Canada and Northern US](https://eccc-msc.github.io/open-data/msc-data/nwp_caldas-nsrps/readme_caldas-nsrps-datamart_en/) | 2.5km  | Four times per day | [MSC Testing Data Repository](https://eccc-msc.github.io/open-data/msc-data/nwp_caldas-nsrps/readme_caldas-nsrps-datamart_en/)
  | | | | | | 
  | | | | | | 
 Atmosphere| Canadian Regional Deterministic Precipitation Analysis (CaPA-RDPA) [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/cmoi/product_guide/docs/lib/technote_capa_rdpa_e.pdf)| Best estimate of the amount of precipitation. Preliminary estimate is available approximately 1h after the end of the accumulation period, and revised 6h after. <a href="./../products/CAPA/domain-images/CaPA_flavours_NG.pdf"> CaPA diagram | Canada, US, Mexico | 10km, surface level | Four times per day.  6h intervals and once a day for the 24h interval |  [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 Atmosphere| High Resolution Deterministic Precipitation Analysis (CaPA-HRDPA) [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/cmoi/product_guide/docs/lib/technote_capa_hrdpa_e.pdf) | Best estimate of 6 and 24 hour precipitation amounts. <a href="./../products/CAPA/domain-images/CaPA_flavours_NG.pdf"> CaPA diagram  | Most of Canada and part of US |2.5km | Four 6-hour precipitation accumulation analyses valid at synoptic hours (00, 06, 12 and 18Z) and two 24-hour analyses valid at 06 and 12Z. A preliminary analysis is produced 1 hour after the time of validity and a final analysis is generated 7 hours later, for a total of 12 analyses per day | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere| High Resolution Ensemble Precipitation Analysis (CaPA-HREPA) [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/cmoi/product_guide/docs/lib/technote_capa_hrepa_e.pdf) | Ensemble version of CaPA-HRDPA, 25 members.  Optimal precipitation estimate over 6 and 24 hour accumulation periods. Component of NSRPS. <a href="./../products/CAPA/domain-images/CaPA_flavours_NG.pdf"> CaPA diagram  | Most of Canada and part of US | 2.5km | Two deterministic configurations of the analysis produce four 6-hour cumulative analyses valid at synoptic times (00, 06, 12, and 18 UTC) and two 24-hour analyses valid at 06 and 12 UTC | [MSC Testing Data Repository](https://dd.alpha.weather.gc.ca/model_hrepa/)
 Atmosphere| High Resolution Deterministic Precipitation Analysis (CaPA-HRDPA) watershed [More Info](https://eccc-msc.github.io/open-data/msc-data/nwp_hrdpa-watershed/readme_hrdpa-watershed_en/)| Average watershed precipitation by combining [network basin polygons](https://open.canada.ca/data/en/dataset/0c121878-ac23-46f5-95df-eb9960753375) with the HRDPA. Best estimate of 6 and 24hr precipitation amounts | Most of Canada and part of US | 2.5km | Four 6-hour precipitation accumulation analyses valid at synoptic hours (00, 06, 12 and 18Z) and two 24-hour analyses valid at 06 and 12Z. A preliminary analysis is produced 1 hour after the time of validity and a final analysis is generated 7 hours later, for a total of 12 analyses per day | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart) 
  | | | | | |  
  | | | | | |  
 Atmosphere | Global Deterministic Prediction System (GDPS) [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_gdps_e.pdf) | Temperature, precipitation, cloud cover, wind speed and direction, and humidity | Global | 15km, 33 vertical levels | Two times per day, 10 days into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere | Regional Deterministic Prediction System (RDPS) [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_rdps_e.pdf) | Temperature, precipitation, cloud cover, wind speed and direction, and humidity | Canada and US | 10km, 33 vertical levels | Four times per day, 84 hrs into the future| [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)  
 Atmosphere | High Resolution Deterministic Prediction System (HRDPS)[Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_hrdps_e.pdf) | Temperature, precipitation, cloud cover, wind speed and direction, humidity and others | Most of Canada | 2.5km, 31 vertical levels | Four times per day, 48 hrs into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/) 
 Atmosphere | Global Ensemble Prediction System (GEPS)[Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_geps_e.pdf) | Probabilistic. Temperature, precipitation, cloud cover, wind speed and direction, humidity and others. Ensemble of 20 scenarios. | Global | .35 degree, 84 vertical levels | (??), 16 days into the future, once per week for forecast of 32 days into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere | North American Ensemble Forecast System (NAEFS) [More info](https://eccc-msc.github.io/open-data/msc-data/nwp_naefs/readme_naefs_en/) | Combined ensemble forecasts, seamless across national boundaries | Canada, US, Mexico | (??) | 1 to 14 days into the future| [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/)
 Atmosphere | Regional Ensemble Prediction System (REPS) [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_reps_e.pdf) | Probabilistic predictions of temperature, precipitation, cloud cover, wind speed and direction, humidity and others. 20 ensemble members  |  Canada and US  | 15km and 10km, 24 vertical levels | Four times per day, 3 days into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart), Archived Info: [CaSPAr](https://caspar-data.ca/)
 Atmosphere | Canadian Seasonal to Inter-annual Prediction System (CanSIPS) [Tech note](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/tech_notes/technote_cansips_e.pdf) | Probabilistic predictions of temperature, precipitation, wind speed and direction and others | Global | 2.5 and 1.0 degrees and for a few selected vertical levels. | Monthly.  Predictions up to 12 months into the future | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 | | | | |
 | | | | | 
Other Products | | | | |  
 Other | Regional Deterministic Reanalysis System (RDRS), [Publication](https://hess.copernicus.org/articles/25/4917/2021/hess-25-4917-2021.pdf) | 40+ year reanalysis | | | |[CaSPAr](https://github.com/julemai/CaSPAr/wiki/Available-products)
 Other | Canadian historical Snow Water Equivalent dataset (CanSWE) [More info](https://essd.copernicus.org/articles/13/4603/2021/) | Database of snow observations | Canada | Observation stations | Updated annually |  [Publication and Data](https://zenodo.org/record/4734372#.Y8WxHJjMKUk)
 Other | Adjusted and Homogenized Canadian Climate Data (AHCCD) [More info](https://open.canada.ca/data/en/dataset/9c4ebc00-3ea4-4fe0-8bf2-66cfe1cddd1d) | Adjusted and homogenized air temperature, rainfall, snowfall, total precipitation, wind speed and atmospheric pressure | Canada | Between 330 and 630 locations | Annual, seasonal, monthly, daily and hourly dependent on variable of interest, 1900-01-01 to 2012-12-31 | [MSC Open Data](https://eccc-msc.github.io/open-data/msc-data/readme_en/) (GeoMet and Datamart)
 Other | Historical Flood Events dataset (HFE) [More info](https://open.canada.ca/data/en/dataset/fe83a604-aa5a-4e46-903c-685f8b0cc33c) | Inventory of past flooding | Canada | low spatial resolution | start/end date: 1696-2021 | [Open Data Canada](https://open.canada.ca/data/en/dataset/fe83a604-aa5a-4e46-903c-685f8b0cc33c)
 | | | | |  


 
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
