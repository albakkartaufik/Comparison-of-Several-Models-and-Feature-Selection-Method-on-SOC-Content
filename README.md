# Comparison of Several Models and Feature Selection Method on SOC Content Prediction using Enviromental Covariate
This Project compared which models and feature selection combination is best to use on SOC content prediction using Environmental Covariate.

Models that has been used on this are:

Random Forest Regressor (RFR); Support Vector Regressor (SVR); and KNN-Regressor (KNN-R).

Feature Selection Method that has been used on this are:

Correlation-Based Feature Selection using Pearson Correlation (CFS); Mutual Information (MI); and Recursive Feature Elimination using Linear Regression.

The datasets are acquired by extracting index from satellite imagery that retrieved from Sentinel-2A and Landsat8/OLI, also CHIRPS datasets are being used to acquired precipitation data. Shoutout to @ilmirmdh for contributing on acquisition data process, i've attached the credit down below.

There are 9 Models + Feature Selection Combination that has been compared based on models performance on train and test datasets by using R2 and sMAPE metric.

The goal is to see which combination of Models and Feature Selection that works best on SOC Content Prediction.

## Big Respect to: 
@ilmirmdh
https://github.com/ilmirmdh

## Email for more information:
albakkartaufik@gmail.com

## References:
Datta, D., Paul, M., Murshed, M., Teng, S. W., & Schmidtke, L. (2022). Soil Moisture, Organic Carbon, and Nitrogen Content Prediction with Hyperspectral Data Using Regression Models. Sensors (Basel, Switzerland), 22(20). https://doi.org/10.3390/s22207998

Effrosynidis, D., & Arampatzis, A. (2021). An evaluation of feature selection methods for environmental data. Ecological Informatics, 61. https://doi.org/10.1016/j.ecoinf.2021.101224
