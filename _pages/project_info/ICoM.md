---
layout: archive
title: Integrated Coastal Modeling (ICoM)
permalink: /project_info/ICoM/
author_profile: true
---

{% include base_path %}

Extreme water levels resulting from a combination of storm-tide flooding and riverine flooding, also known as compound flooding (CF), are among the most critical hazards to coastal communities. Most notably, the estuarine and deltaic regions worldwide are at higher risk than others, where the flood characteristics change based on the storm tide and river flow interaction. In the low-lying areas, CF caused by the co-occurrence of extreme precipitation, river flooding, storm surge, and extreme sea level rise, are expected to increase under future climate change. Understanding how the sensitivity of CF may respond to a changing climate through joint considerations of SLR and tropical cyclone environment is essential for flood mitigation and risk reduction, especially in converging estuaries.  

Key summaries from the ongoing work:

1. We implemented one-way coupling of a physics-based hydrologic model [DHSVM](https://www.pnnl.gov/projects/distributed-hydrology-soil-vegetation-model) with the 3D ocean model [FVCOM](http://fvcom.smast.umassd.edu/fvcom/) to evaluate the importance of higher resolution representation of the storm properties and high spatial details of the river and creek discharge to capture the compound flood characteristics.

2. We used the [Risk Analysis Framework for Tropical Cyclones (RAFT)](https://climatemodeling.science.energy.gov/presentations/risk-analysis-framework-tropical-cyclones-raft) to construct a series of synthetic storms with perturbed SLR and environmental conditions of a Hurricane Irene-like event using reanalysis data and climate model output.

3. We will apply the RAFT-generated synthetic storms characterized by varying storm conditions to drive process-based terrestrial-coastal models (DHSVM-FVCOM) to assess how the projected storm conditions and SLR interact with the hydrological and hydrodynamic processes in their control of CF characteristics.

Ultimately, the study will highlight the importance of process-based understanding of CF via sensitivity analysis, which can aid local planning and adaptation under a changing climate.

### Conference abstracts and presentations:

1. Deb, M., Yang, Z., Wang, T., Sun, N., Judi, D. R. and Wigmosta, M. S. (2022) “Compound flood modeling in a shallow convergent estuary: An integrated approach using FVCOM and DHSVM”, Abstract accepted, [Ocean Sciences Meeting 2022](https://osm2022.secure-platform.com/a), Honolulu, HI, Feb 27 - Mar 4.

2. Deb, M., Yang, Z., Wang, T., Sun, N., Balaguru, K., Xu, W., Judi, D. R. and Wigmosta, M.S. (2021) “Sensitivity of compound flooding potential to idealized large-scale tropical cyclone environments”, [AGU Fall Meeting 2021](https://www.agu.org/Fall-Meeting), New Orleans, Louisiana, Dec 13 - 17.

3. Zang X., Judi, D. R., Li, X., Rakowski, C. L., Sun, N., Yang, Z., Wigmosta, M. S., Wang, T. and Deb, M. (2021) “The effect of DEM resolution and accuracy on urban flooding simulation: a case study in the Philadelphia metropolitan region”, [AGU Fall Meeting 2021](https://www.agu.org/Fall-Meeting), New Orleans, Louisiana, Dec 13 - 17.

### Web links of the public datasets used for model development and validation in this study

1. [ETOPO1 Global Relief Model](https://www.ngdc.noaa.gov/mgg/global/)
2. [NOAA Coastal Relief Model](https://www.ngdc.noaa.gov/mgg/coastal/crm.html)
3. [Continuously Updated Digital Elevation Model (CUDEM)](https://coast.noaa.gov/htdata/raster2/elevation/NCEI_ninth_Topobathy_2014_8483/)
4. [NOAA Continually Updated Shoreline Product (CUSP)](https://shoreline.noaa.gov/data/datasheets/cusp.html)
5. [GOFS 3.1: 41-layer HYCOM + NCODA Global 1/12° Reanalysis](https://www.hycom.org/data/glbv0pt08/expt-53ptx)
6. [OSU TPXO Tide Models](https://www.tpxo.net/home)
7. [NCEP Climate Forecast System Version 2 (CFSv2)](https://rda.ucar.edu/datasets/ds094.0/)
8. [ERA5-ECMWF reanalysis](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5)
9. [NOAA Tides and Currents](https://tidesandcurrents.noaa.gov/)
10. [USGS River Discharge](https://waterdata.usgs.gov/nwis)
11. [Livneh CONUS near-surface gridded meteorological data](https://psl.noaa.gov/data/gridded/data.livneh.html)

### Pre and Post-Processing softwares/tools used in the analysis

1. [MATLAB](https://www.mathworks.com/products/matlab.html)
2. [ArcGIS](https://www.esri.com/en-us/arcgis/about-arcgis/overview)
3. [SMS 13.1](https://www.aquaveo.com/software/sms-surface-water-modeling-system-introduction)
