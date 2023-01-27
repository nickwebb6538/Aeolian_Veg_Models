# Aeolian_Veg_Models
This repository contains data collected at the Jornada Experimental Range (JER) National Wind Erosion Research Network (NWERN) site and used in the Aeolian Vegetation Models project.

# Authors

Robert R. K. Wojcikiewicz12*, Nicholas P. Webb2, Brandon L. Edwards2, Justin W. Van Zee2, Ericha M. Courtright2, Brad F. Cooper2

1 Plant and Environmental Sciences Department, New Mexico State University, Las Cruces, NM 88003, USA

2 USDA-ARS Jornada Experimental Range, Las Cruces, NM 88003, USA

# Created

2015-2021

# Purpose

This repository contains data used by Wojcikiewicz et al. for the manuscript " Aeolian sediment transport responses to vegetation cover change: Effects of sampling error on model uncertainty" submitted for publication in Journal of Geophysical Research Earth Surface.

# Data

Measurements were collected during the period September 2015 to June 2021 at the National Wind Erosion Research Network site on the Jornada Experimental Range in south-central New Mexico, USA. The study site was described by Webb et al. (2016).

Meteorological data were measured with a centrally-located 10 m meteorological tower equipped with cup anemometers at 0.5 m, 1.0 m, 1.5 m, 2.5 m, and 5.0 m above ground level (AGL) , and one RM Young 3002 cup anemometer with a wind vane mounted at 10 m AGL to measure the vertical wind speed profile. A Campbell Scientific EE181 model air temperature/relative humidity probe was mounted at 4.0 m AGL and temperature sensors (model 107-L) were mounted at 2.0 m and 10 m AGL. A tipping bucket rain gauge (TE525) was mounted at 1.5 m AGL approximately 4 m to the northwest of the central tower. The southern 3 m tower was equipped with an RM Young 3002 cup anemometer and wind vane mounted at 3.0 m. Data were sampled at 1 Hz and were logged every 1 min on Campbell Scientific CR1000 data loggers.

Horizontal sediment mass flux was measured using 27 Modified Wilson and Cooke (MWAC) sediment samplers with inlet 2.34 x 10-4 m2 (Webb et al., 2019). The 27 freely rotating masts, each with four MWAC samplers (0.1, 0.25, 0.5 and 0.85 m above ground level) were located across the site using a stratified random sample design. A regular 3 x 3 grid provided strata and three MWAC masts with samplers were randomly located in each grid cell.

Transect data were collected on three parallel 100 m transects spaced 60 degrees apart (from 0 degrees) with the transects passing through the center of the site at the meteorological tower. Methods of Herrick et al. (2018) were used to measure vegetation height, the size distribution of canopy gaps >=5 cm (unvegetated spaces between plant canopies), and foliar cover of vegetation by species and soil surface properties.

# Data files include:

1.	JER2015.zip; JER2016.zip; JER2017.zip; JER2018.zip; JER2019.zip; JER2020.zip; JER2021.zip - These files contain raw meteorological data for each year through XXXX 2021.
2.	JER_CoreIndicators_2015_2021.csv - This file contains indicators of vegetation foliar cover by plant functional group calculated from vegetation transect data collected for each measurement event.
3.	JER_HorizontalFlux_2015_2021.csv - This file contains vertically-integrated horizontal sediment mass fluxes calculated from Modified Wilson and Cooke (MWAC) data for each collection period (2015-2021).

The following lists provide field definitions for the meteorological, core indicators, and horizontal sediment mass flux data.

# JER2015.zip – JER2021.zip

•	TIMESTAMP - Month/Day/Year (MM/DD/YYYY) and time (HH:MM) of observation.
•	RECORD - Unique record number for each data point.
•	Switch - Switch 12V status (boolean) for triggering a collection.
•	AvgTemp_10M_DegC - Average temperature (Deg C) at 10 meters from base of tower.
•	AvgTemp_4M_DegC - Average temperature (Deg C) at 4 meters from base of tower.
•	AvgTemp_2M_DegC - Average temperature (Deg C) at 2 meters from base of tower.
•	AvgRH_4m_perc - Average relative humidity (percentage) at 4 meters from base of tower.
•	Total_Rain_mm - Total rain (milimeters) at 1.5 meters above ground.
•	WindDir_deg - Wind direction (degrees) at 10 meters from base of tower.
•	MaxWS6_10M_m_s - Maximum wind speed (meters/second) at 10 meters from base of tower.
•	MaxWS5_5M_m_s - Maximum wind speed (meters/second) at 5 meters from base of tower.
•	MaxWS4_2.5M_m_s - Maximum wind speed (meters/second) at 2.5 meters from base of tower.
•	MaxWS3_1.5M_m_s - Maximum wind speed (meters/second) at 1.5 meters from base of tower.
•	MaxWS2_1M_m_s - Maximum wind speed (meters/second) at 1 meter from base of tower.
•	MaxWS1_0.5M_m_s - Maximum wind speed (meters/second) at 0.5 meter from base of tower.
•	StdDevWS2_1M_m_s - Wind speed (meters/second) standard deviation at 1 meter from base of tower.
•	AvgWS6_10M_m_s - Average wind speed (meters/second) at 10 meters from base of tower.
•	AvgWS5_5M_m_s - Average wind speed (meters/second) at 5 meters from base of tower.
•	AvgWS4_2.5M_m_s - Average wind speed (meters/second) at 2.5 meters from base of tower.
•	AvgWS3_1.5M_m_s - Average wind speed (meters/second) at 1.5 meters from base of tower.
•	AvgWS2_1M_m_s - Average wind speed (meters/second) at 1 meter from base of tower.
•	AvgWS1_0.5M_m_s - Average wind speed (meters/second) at 0.5 meter from base of tower.
•	Sensit_Tot - Total number of particle counts within a logging interval (1 min) 5 cm above soil surface.
•	SenSec - Number of seconds within a logging interval (1 min) that particles were counted.


# JER_CoreIndicators_2015_2021.csv



# JER_HorizontalFlux_2015_2021.csv

•	Site - Study site name (general locality).
•	Monitoring Plot - Identification of plot at which data were collected.
•	Stack Location - Identification of MWAC mast (stack) location within plot.
•	MWAC Height (opt) - Height (cm) above ground level at which inlet of MWAC sampler can was installed.
•	MWAC Location - Descriptor of where on the MWAC mast a sampler (can) was installed.
•	Box Type (Rotating or Static) - Differentiates whether the MWAC mast could freely rotate into the wind or if the mast was fixed to sample from a set azimuth.
•	MWAC Internal Diameter - Internal diameter of MWAC sampler inlet (inches).
•	Inlet Area (cm2) - Area of MWAC sampler inlet (cm2).
•	Processing method (Wet/Dry) - Identification of whether a dry (sample tapped out of MWAC can into weigh boat) or wet (sample rinsed out of MWAC can into pre-weighed beaker then oven dried) sediment retrieval method was used.
•	Drying Oven temp (c) - Temperature of oven at which samples were dried prior to weighing.
•	Date Collected - Day, month and year on which the samples were collected in the field.
•	No. days exposure - Number of days for which the MWAC samplers were in the field collecting sediment.
•	Can No. - Identification number assigned to MWAC sampler can.
•	Empty Boat wt. (g) - Weight of weigh boat (grams) without sediment sample (i.e., prior to weighing sample).
•	Boat + sed. Oven dry wt. (g) - Weight of weight boat containing sediment sample (grams).
•	Bulk Soil Sediment wt. (g) - Sediment sample weight (grams).
•	Sediment archived (y/n) - Record of whether the physical sediment sample was stored or discarded.
•	Collection Notes - Notes describing sample pertinent to data quality and interpretation.
•	Sample Discarded (any non-blank means) - Record of whether the physical sediment sample was discarded.

# References

Herrick, J.E., Van Zee, J.W., McCord, S.E., Courtright, E.M., Karl, J.W., & Burkett, L.M. (2018), Monitoring Manual for Grassland, Shrubland, and Savanna Ecosystems, Volume 1: Core Methods, Second EditionRep., USDA-ARS Jornada Experimental Range, Las Cruces, New Mexico.

Webb, N. P., Herrick, J. E., Van Zee, J. W., Courtright, E. M., Hugenholtz, C. H., Zobeck, T. M., et al. (2016), The National Wind Erosion Research Network: Building a standardized long‐term data resource for aeolian research, modeling and land management. Aeolian Research, (22), 23–36.

Webb, N., Chappell, A., Edwards, B., McCord, S., Zee, J., Cooper, B., Courtright, E., Duniway, M., Sharratt, B., Tedela, N., Toledo, D. (2019), Reducing Sampling Uncertainty in Aeolian Research to Improve Change Detection. Journal of Geophysical Research: Earth Surface, (124).  doi: 10.1029/2019JF005042, 2019.

