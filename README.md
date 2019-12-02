# RICHTER PREDICTOR

## Background

![1-Logo](Images/1-Logo.png)

Richter predictor is a team project utilizing machine learning tools and Tableau to visualize and explore recorded earthquakes in the US using USGS earthquake data. The recent phenomena of earthquake swarms in the central US are a focus of this study. ML is used to show that this disturbing trend would have been unpredictable given 60 years of national data. 

Additional ML models are applied in an effort to predict earthquakes. 

### Folders & Files:



presentation.pdf - Final powerpoint saved in pdf to show slides as they appeared during the presentation.
presentation.ppt - Final powerpoint, may appear different from originally intended. Please refer to pdf version.

Images - Unrelated to project itself

Resources
* chris_work - directory contains Tableau machine learning work conducted by Chris and visualization results after training on the entire nation's dataset
* exploratory_datasets - directory contains various csv files used in preliminary exploration. These raw datasets are derived from the same handful of datasets also found within this directory. Many attempts to create feasible datasets for study required different subsets and merges until a final suitable csv was created (see Earthquake-Wells-National.csv).
* kendall_work - directory contains 2 Jupyter workbooks that apply various machine learning models in Python. These were supplemental tests run by Kendall to support and expand on Tableau findings.
* OK_ClassII_2011_2015_Volumes_Sums2 - directory contains data of Oklahoma fracking wells and their outputs from 2011-2015. This data was combined with earthquake data found in exploratory_datasets directory and together produced the final dataset (see Earthquake-Wells-National.csv)
* Earthquake-Wells-National.csv - CSV file combines earthquake data of Oklahoma with fracking well data in the same state. The data is used to create visualizations of Oklahoma's fracking activities alongside measured earthquake activity by location and time periods. See link below for tableau story using this dataset.

Further visualization can be found at: https://public.tableau.com/profile/max.o.neill#!/vizhome/EarthQuakesandWells/Story1
