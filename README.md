# Clustering_Prediction_Urban_Air_Pollution_PM2.5

## Project Overview
This project covered Unsupervised and Supervised Learning methods. 

Under Unsupervised, Clustering was performed on the data - K-means Clustering and Hierarchical Clustering. 

Elbow method was used to determine the optimal number of clusters (K). Silhouette Score metric was applied to determine how accurate the number of K were determined using a plot.

An agglomerative Hierarchical clustering was applied on the data. Dendrogram was plotted to show visually how the number of clusters was reached at.

A new variable called Clusters was created and was used as one of the features in supervised learning.

Under Supervised learning, the main objective was to predict the mean concentration of pollutants in the air (PM2.5). The target variable was a numeric and continuous and so this was a regression problem.

Models such as Linear regression, Random Forest Regressor, XGBoost, LightGBM, Decision trees and Support Vector Regressor were fitted to the data.

It was determined the of all the models used, XGBoost had the highest accuracy.
