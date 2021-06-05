# Module 18 Challenge - Cryptocurrencies

## Overview of the Analysis

Analyze a Cryptocurrencies dataset using Unsupervised Machine Learning classification and regresssion to identfy any groups and trends for potential investment.

## Activities

Cleaned the dataset to remove inactive cryptocurrencies (those not being traded), null data, unmined cryptocurrencies and those without an algorithm. Standardized the data using StandardScaler; used PCA to reduce dimensions to three components; plotted an Elbow curve to find best value for K-Means; used four predicted clusters to create a 3D-Scatter plot; used MinMaxScaler to fit & transform data and created hvplot.scatter plot to show the four classes with Total Coin Supply and Total Coins Mined.

## Results

The scatter plot shows cryptocurrencies in four clusters and a couple of outliers. These clusters can be used for further analysis using other Machine Learning models.

