# EDA_on_Dengai
#### Introduction
Dengue fever is a mosquito-borne viral disease that causes flu-like symptoms and, in severe cases,it can lead to potentially life-threatening complications. Predicting the number of dengue cases is crucial for public health planning and resource allocation to effectively combat the disease.

The dataset provides various features related to weather conditions, precipitation measurements, and vegetation indices, which can serve as potential indicators of dengue transmission. These features include temperature, precipitation, humidity, and satellite-based vegetation indices.

In this task, we aim to predict the total number of cases for each (city, year, weekofyear) combination in the test set. The dataset consists of two cities: San Juan and Iquitos. The test data covers a period of 5 years for San Juan and 3 years for Iquitos. The data for both cities have been combined and a city column has been added to indicate the source, with "sj" representing San Juan and "iq" representing Iquitos.

It's important to note that the test set is a pure future hold-out, which means that it contains data that is sequential and does not overlap with any of the training data. This ensures that the predictions are made for unseen time periods.
