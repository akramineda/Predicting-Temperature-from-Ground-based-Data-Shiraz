# Predicting-Temperature-from-Ground-based-Data-in-Shiraz
With the spirit of reproducible research, this repository contains codes required to produce the results in the manuscript:

> N. Akrami, K. Ziarati, S. Dev, Predicting Temperature from Ground-basedSynoptic Data in Shiraz City, Iran


## Code Organization
All codes are written in python3.

### Dependencies
The following libraries should be installed before the execution of the codes.

- numpy: `pip install numpy`
- pandas: `pip install pandas`
- matplotlib: `pip install matplotlib`
- statsmodels: `pip install statsmodels`
- scikit-image 0.17.2: `pip install scikit-image`


### Data
The ground-based meteorological data collected from Shiraz station is obtained from the [Iran Meteorological Organization](https://www.irimo.ir). We are releasing the processed data that we used in this work. You may find the processed data in data folder in repository.

### Scripts
- shz_temp_forecast.ipynb: Run this script to make the prediction results via TES and benchmarking methods mentioned in paper. 

- SARIMA_Shz.ipynb: Run this script to generate the SARIMA model and its output.
