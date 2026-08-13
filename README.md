# extremeWaterLeverForecastingHwy37

This is the repository for the paper, "Forecasting Coastal Water Level Extremes from Past Observations with Explainable AI".

Primary Author: Avery Wood

Secondary Authors: Maike Sonnewald, John largier

 # Guide

 The hwy37_EDA notebook consists of all of the exploratory data analysis I did for the project. Many plots were adjusted in the file and previous versions typically weren't saved. The most recent plots shown in the file are the ones used in my paper. This file also contains the models for the MLP and LSTM and their resultant SHAP values and ensembles. This file also consists of EDA for the other sites Rowland Bridge and Novato Creek which were not used in my paper.

 The Petaluma_River_Models notebook contains all of the models, including the Coastal Ocean's linear regression, that were used in my Master's project in a more organized format. This file is compartmentalized and you should be able to run each model section independent of each other. For the combined bias section at the end you do need to run every model individually. No model parameter saving was implemented for a quick start as all of these models did not take too long to run. 
