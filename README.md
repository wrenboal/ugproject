# Classification of Tempering Quality of Chocolate Using Artificial Neural Network and Near-infrared Spectroscopy
An undergraduate food science final-year project, using Artificial Neural Network (ANN) and Near-infrared spectral data to classify 3 samples of chocolate according to their tempering quality

## Overview
In this project, 3 chocolate samples were prepared, at 3 distinct tempering conditions. Near-infrared spectral data (125 wavelengths/variables) were collected at several points on each chocolate, on the day of sample preparation and during storage. Each measurement was treated as a single observation. The spectral data were pre-processed, Principal Component Analysis (PCA) was performed for exploratory data analysis and a simple ANN classification model was built to classify each observation according to the tempering condition of the sample it was from.

A few modeling approaches were explored during development. The version presented here reflects a simplified pipeline intended to illustrate the overall methodology, rather than to showcase optimal performance.

## How to navigate the repository
**PCA exploratory data analysis:**
- Documented in [PCA_exploration.ipynb](./PCA_exploration.ipynb)
- Dataset: [Data for PCA.xlsx](./Data%20for%20PCA.xlsx)
- Example plots: [PCA_Score_Plots_Alldays.png](./PCA_Score_Plots_Alldays.png) and [PCA_Score_Plots_Day0.png](./PCA_Score_Plots_Day0.png)

**ANN model development:**
- Documented in [model.ipynb](./model.ipynb)
- The dataset for modeling is in [Data for modelling.xlsx](./Data%20for%20modelling.xlsx)
- Relevant plots are included within the notebook.

## Acknowledgements
This project benefitted from foundational codes provided by a research collaborator and AI tools. However, I took the lead in editting, planning strategies, reorganising and documenting throughout data exploration and model development optimisation.
