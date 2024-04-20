# EDA_on_Dengai
### Introduction
Dengue fever is a mosquito-borne viral disease that causes flu-like symptoms and, in severe cases,it can lead to potentially life-threatening complications. Predicting the number of dengue cases is crucial for public health planning and resource allocation to effectively combat the disease.

The dataset provides various features related to weather conditions, precipitation measurements, and vegetation indices, which can serve as potential indicators of dengue transmission. These features include temperature, precipitation, humidity, and satellite-based vegetation indices.

In this task, we aim to predict the total number of cases for each (city, year, weekofyear) combination in the test set. The dataset consists of two cities: San Juan and Iquitos. The test data covers a period of 5 years for San Juan and 3 years for Iquitos. The data for both cities have been combined and a city column has been added to indicate the source, with "sj" representing San Juan and "iq" representing Iquitos.

It's important to note that the test set is a pure future hold-out, which means that it contains data that is sequential and does not overlap with any of the training data. This ensures that the predictions are made for unseen time periods.

### The features in this dataset
city – City abbreviations: sj for San Juan and iq for Iquitos
week_start_date – Date given in yyyy-mm-dd format
station_max_temp_c – Maximum temperature
station_min_temp_c – Minimum temperature
station_avg_temp_c – Average temperature
station_precip_mm – Total precipitation
station_diur_temp_rng_c – Diurnal temperature range
precipitation_amt_mm – Total precipitation
reanalysis_sat_precip_amt_mm – Total precipitation
reanalysis_dew_point_temp_k – Mean dew point temperature
reanalysis_air_temp_k – Mean air temperature
reanalysis_relative_humidity_percent – Mean relative humidity
reanalysis_specific_humidity_g_per_kg – Mean specific humidity
reanalysis_precip_amt_kg_per_m2 – Total precipitation
reanalysis_max_air_temp_k – Maximum air temperature
reanalysis_min_air_temp_k – Minimum air temperature
reanalysis_avg_temp_k – Average air temperature
reanalysis_tdtr_k – Diurnal temperature range
ndvi_se – Pixel southeast of city centroid
ndvi_sw – Pixel southwest of city centroid
ndvi_ne – Pixel northeast of city centroid
ndvi_nw – Pixel northwest of city centroid
