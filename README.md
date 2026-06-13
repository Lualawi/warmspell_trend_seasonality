This repository contains Python code files used to perform analysis for the results presented in Mareshet Admasu et al. 2026, An Assessment of Northern Hemisphere Warm Spell Trends Across Seasons: Spring Warm Spells Increasing Faster Than Projected. The codes include:
- cmip_regrid.sh: utilizes Climate Data Operators (CDO) to regrid CMIP6, ERA5 and Berkeley Earth datasets to a common grid size.
- functions.py: contains functions used to compute several analyses, including computing warm spell metrics, trends, and other pre-processing steps like slicing temporal and spatial extents. 
- compute_warmspells.ipynb: computes warm spell metrics on each dataset and saves for analysis.
- seasonal_trends.ipynb: computes seasonal trends in warm spell days, mean temperature, and 10-day temperature variability.
- doy_trends: computes trends for each day-of-year in warm spells and mean temperature.
- clusters_berkeley.ipynb: identifies clusters based on Berkeley warm spell trends across day-of-year and maps the equivalent temperature trends and 10-day temperature variability across day-of-year.
- clusters_era.ipynb: same as "clusters_berkeley.ipynb" but based on ERA5 warm spell trends across day-of-year.
- clusters_cmip6.ipynb: same as "clusters_berkeley.ipynb" but based on CMIP6 model mean warm spell trends across day-of-year.
- result_plots.ipynb: generates final figures included in the article.
