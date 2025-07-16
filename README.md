This repository contains the analysis and modeling scripts for my Master’s thesis.

The project investigates brain-behavior relationships using neuroimaging and behavioral data from the ABCD Study.

# XGBoosting the Signal; A Machine Learning Approach for Informant-Sensitive Predictions of OCD Symptoms in Children Based on Brain Morphology

Data used in this thesis is sourced from the ABCD Data Release 5.1 (Haist & Jernigan, 2023).

Note: Access to raw data requires proper credentials through the NIMH Data Archive (NDA).

## Goals

Preprocess behavioral and MRI data for a subset of youth with OCD and healthy controls

Train and evaluate machine learning models (XGBoost) to predict clinical symptoms

Compare parent and youth reported symptom profiles (CBCL, BPM)

Calibrate predictions and assess generalization to unseen data

## Methods

Data manipulation: dplyr, tidyr

Modeling: xgboost, caret, ROSE, MLmetrics, Metrics,pROC

Visualization: ggplot2, viridis, plotly, htmlwidgets, patchwork, GGally, ggcorrplot

Tables: knitr, gt 

Reporting: Quarto (.qmd) notebooks

## Disclaimer

This was my first full coding project, and the code reflects a learning process.

Scripts may be repetitive or messy in places. I've prioritized functionality over elegance while trying to improve along the way.
