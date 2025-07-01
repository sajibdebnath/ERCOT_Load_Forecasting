# ERCOT_Load_Forecasting
"Extreme Weather Grid Load Forecasting using Weather-Informed LSTM and Transformer Machine Learning Models" Submitted in the 57th North American Power Symposium (NAPS) 2025, will be hosted by the University of Connecticut

Authors: Sajib Debnath et al.
===========================================================================================
Conference link: https://uconnuecs.cventevents.com/event/NAPS25/summary
===========================================================================================

Weather data source: https://mesonet.agron.iastate.edu/request/download.phtml?network=TX_ASOS# 

Weather Data (NOAA): Three weather stations (BKS, JDD, and TME) distributed in different regions of Texas, USA are chosen to capture the variations of weather across Texas. The hourly data of air temperature, relative humidity, wind speed, feel-like temperature, and precipitation, spanning from 2018 to 2024 are considered in this study. The missing data points are linearly interpolated to have corresponding values for the electricity demand data. 

---------------------------------------------------------------------------------------------------------

ERCOT data source: https://www.ercot.com/gridinfo/load/load_hist

Load Data (ERCOT): The grid load data, from 2018 to 2024, are taken from ERCOT website. The dataset has a measure of electricity demand in megawatts for ERCOT in an hourly manner between 2018 and 2024. The demand data actually capture the total demand for electricity for the entire ERCOT region, representing the aggregated consumption of residential, commercial, and industrial electricity users within the ERCOT region. 
