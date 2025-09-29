# Auto-Machine-Learning-and-RF-Visualization
This repository provides the full code implementation for analyzing the environment–disease nexus using Auto Machine Learning (AutoML). It includes scripts for data preprocessing, dimensionality reduction (PCA), global Random Forest modeling, and local (geographically weighted) Random Forest analysis.

## The workflow consists of five main steps:

## AUTO_ML.ipynb
Run AutoML to automatically select the best-performing pipeline for modeling the relationship between environmental predictors and chronic diseases.

## PCAsRandomForest.ipynb
Using the optimal pipeline from AutoML, perform Principal Component Analysis (PCA) to reduce multicollinearity and train a global Random Forest model.
The resulting feature importance is visualized spatially to reveal key environmental drivers.

## Local_RF_Performance.ipynb
Extend the global model into a local Random Forest (Geographically Weighted RF) framework to capture spatial heterogeneity and map local R² performance across census tracts.

## SHAP_Visualization.ipynb
Apply SHAP (SHapley Additive exPlanations) to interpret model outputs and explain how each environmental feature contributes to the prediction of disease incidence.

## ALE_plot.ipynb
Use Accumulated Local Effects (ALE) plots to assess the nonlinear effects and thresholds of the most influential predictors identified by SHAP and RF importance.


## Google Earth Engine Data Collection and Processing
https://code.earthengine.google.com/f6a155c4015019174ceedd834f750328

https://code.earthengine.google.com/6bfd44f79b39adc5f2801ea2ce8e1507

https://code.earthengine.google.com/32ba427e5c465381b3b5925034554742

https://code.earthengine.google.com/4cacc4341b80e5345043513c463706e3

https://code.earthengine.google.com/ac3c090a07e857f3f240c9f904106628

https://code.earthengine.google.com/d67b10bd8c29c1a9a9f3613819bdfec1

https://code.earthengine.google.com/55ff437700901ddfb20f223907bb2448

https://code.earthengine.google.com/473336db74f424a5b7545af87b315317

https://code.earthengine.google.com/9aade756494b1f15ef89971ace9832f0
