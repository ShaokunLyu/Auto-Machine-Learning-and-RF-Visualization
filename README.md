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
