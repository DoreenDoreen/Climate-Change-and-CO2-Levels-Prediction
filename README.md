# Climate-Change-and-CO2-Levels-Prediction
Time Series Analysis Project

# Project Overview
1. Data Upload
2. Data Preprocessing
3. Exploratory Data Analysis & Feature Engineering
4. Model Forecasting & Evaluation

# Visualization
<img width="1585" height="913" alt="image" src="https://github.com/user-attachments/assets/0fdee1a5-4729-45ab-a2bc-53580310a12e" />

# Check Stationary via ADF test 
ADF Statistic: -8.648489
p-value: 0.000000
Critical Values:
	1%: -3.442
	5%: -2.866
	10%: -2.569

# Generate ACF and PACF plots
ACF
<img width="641" height="462" alt="image" src="https://github.com/user-attachments/assets/072e48e1-70cf-4cb5-bb52-4954bc1db729" />

PACF
<img width="641" height="462" alt="image" src="https://github.com/user-attachments/assets/32bcec77-1ba9-4505-a266-39d2b57a885b" />


# Fit data into ARIMA model

==============================================================================
                 coef    std err          z      P>|z|      [0.025      0.975]
------------------------------------------------------------------------------
ar.L1          0.5679      0.047     11.970      0.000       0.475       0.661
ma.L1          0.3382      0.051      6.647      0.000       0.238       0.438
sigma2         0.7479      0.052     14.466      0.000       0.647       0.849
==============================================================================

<img width="1387" height="1074" alt="image" src="https://github.com/user-attachments/assets/974521b7-2b02-477c-a4d9-8ce24d07a078" />


# Model Forecasting via Real Data
<img width="647" height="461" alt="image" src="https://github.com/user-attachments/assets/348d92d4-a72c-4b88-a78f-a2059f227f2e" />

# Model Forecasting via Predictive Data 
<img width="960" height="720" alt="image" src="https://github.com/user-attachments/assets/f3ec2968-0206-4782-822d-7766f416ee73" />


