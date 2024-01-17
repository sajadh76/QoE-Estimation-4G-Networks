# QoE-estimation-4G-Networks

## Overview
This project aims to estimate the user satisfiction in 4G networks, relatively to the usage of YouTube Service. The this project takes as input Crowdsourcing Data (i.e., data measured directly at users terminals) and will output the
corresponding users satisfaction class.

## Dataset
You can find some data samples available in two .csv files.

## Features
In the following you can find a list of the features used to estimate user satisfaction:

- Max_RSRQ
- Cumulative_YoutubeSess_LTE_DL_Volume
- Service_Availability_Ratio_LTE
- Max_SNR
- Cumulative_YoutubeSess_LTE_DL_Time
- Youtube_Time_Percentage_LTE
- Cumulative_Lim_Service_Time_LTE
- Total_Service_Time_LTE
- Cumulative_Full_Service_Time_LTE
- Preferred_Network_Type
- Cumulative_No_Service_Time_LTE
- Avg_Youtube_Time_LTE
- Avg_Youtube_Volume_LTE


## Algorithms
The following algorithms have been used in this project:
- Bayesian optimization
- Grid search
- XGBoost
- Random Forest
- Decision Tree
