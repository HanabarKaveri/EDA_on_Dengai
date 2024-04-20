# EDA_on_Dengai
### Introduction
Dengue fever is a mosquito-borne viral disease that causes flu-like symptoms and, in severe cases,it can lead to potentially life-threatening complications. Predicting the number of dengue cases is crucial for public health planning and resource allocation to effectively combat the disease.

The dataset provides various features related to weather conditions, precipitation measurements, and vegetation indices, which can serve as potential indicators of dengue transmission. These features include temperature, precipitation, humidity, and satellite-based vegetation indices.

In this task, we aim to predict the total number of cases for each (city, year, weekofyear) combination in the test set. The dataset consists of two cities: San Juan and Iquitos. The test data covers a period of 5 years for San Juan and 3 years for Iquitos. The data for both cities have been combined and a city column has been added to indicate the source, with "sj" representing San Juan and "iq" representing Iquitos.

It's important to note that the test set is a pure future hold-out, which means that it contains data that is sequential and does not overlap with any of the training data. This ensures that the predictions are made for unseen time periods.

### The features in this dataset
#### 1.city – City abbreviations: sj for San Juan and iq for Iquitos
#### 2.year - Year  
#### 3.weekofyear - week of the year
#### 4.week_start_date – Date given in yyyy-mm-dd format
#### 5.station_max_temp_c – Maximum temperature
#### 6.station_min_temp_c – Minimum temperature
#### 7.station_avg_temp_c – Average temperature
#### 8.station_precip_mm – Total precipitation
#### 9.station_diur_temp_rng_c – Diurnal temperature range
#### 10.precipitation_amt_mm – Total precipitation
#### 11.reanalysis_sat_precip_amt_mm – Total precipitation
#### 12.reanalysis_dew_point_temp_k – Mean dew point temperature
#### 13.reanalysis_air_temp_k – Mean air temperature
#### 14.reanalysis_relative_humidity_percent – Mean relative humidity
#### 15.reanalysis_specific_humidity_g_per_kg – Mean specific humidity
#### 16.reanalysis_precip_amt_kg_per_m2 – Total precipitation
#### 17.reanalysis_max_air_temp_k – Maximum air temperature
#### 18.reanalysis_min_air_temp_k – Minimum air temperature
#### 19.reanalysis_avg_temp_k – Average air temperature
#### 20.reanalysis_tdtr_k – Diurnal temperature range
#### 21.ndvi_se – Pixel southeast of city centroid
#### 22.ndvi_sw – Pixel southwest of city centroid
#### 23.ndvi_ne – Pixel northeast of city centroid
#### 24.ndvi_nw – Pixel northwest of city centroid
