# Dissertation Proposal Title: AI/ML Models to Forecast Residual Chlorine Concentrations in a Water Treatment Plant in the State of Florida, USA
# By: Angelica Cortes Ortiz 
# Committee: Dr. Lawrence Fulton (Chair), Dr. Yuksel Karahan (SME), & Dr. Aeron Zentner (Academic Reader)
# University: National University, School of Technology and Engineering
# Degree: Data Science 

This repository contains the workflow that supports my dissertation research topic which aims to develop AI/ML time series forecasting models to predict residual 
chlorine concentrations utilizing data from the Alexander Orr Water Treatment Plant located in Miami-Dade County, Miami, FL, USA. 

The dataset consists of 26,328 rows of residual chlorine concentration (mg/L), turbidity (NTU), and flowrate (mgd) data operationally collected at the Alexander Orr 
Water treatment plant from 17 November 2022 to 17 November 2025. 

The first portion of the research focuses on Exploratory Data Analysis to understand the data patterns as well as identify and correct anomalies. Then, 
univariate and multi-variable time series forecasting baseline and AI/ML models were developed to predict residual chlorine concentrations. Additionally, an early
warning system was developed using classic ML models to forecast residual chlorine concentrations that surpass a specified threshold. 

# Baseline models: 
Exponential Smoothing
<BR>
ARIMA
<BR>
SARIMA
<BR>
SARIMAX

# Deep learning models: 
ANN
<BR>
LSTM
<BR>
TFT

# Classic ML models: 
Logistic Regression 
<BR>
SVM 
<BR>

# License and Data Use

<BR> <BR>

The original source code in this repository is available under the MIT License. See the `LICENSE` file for details.

The three water treatment datasets used in this research are not included in this public repository and are not covered by the MIT License. The Sergio Cuevas and Los Filtros datasets were externally provided for this research and may not be redistributed without authorization from their respective data providers. The Alexander Orr operational dataset is also excluded from public distribution.

See `DATA_AVAILABILITY.md` for additional information.
kNN
<BR>
DT
<BR>
RF
