# Cryptocurrencies
## Overview
Use cryptopcurrency data to practice preprocessing and reducing data for use in a unsupervised machine learning model. Create a model that groups tradable cryptocurrencies into 4 classes.
1) Unusable data was removed from the dataset:
*  Currencies not currently trading
*  The trading indicator column
*  Rows containing null values

2) Text data converted to numerical data using get_dummies method
3) Data scaled to reduce false importance amplification
4) Top three important features pulled out using PCA method
5) KMeans model with 4 clusters created from important data features
6) Scatter plot of 4 clusters created from scaled total coins mined and current supply of each currency.
