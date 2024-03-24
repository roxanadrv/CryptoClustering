# CryptoClustering

This repository contains a machine learning project that explores cryptocurrency data to identify potential clusters using K-Means clustering. It includes dimensionality reduction with Principal Component Analysis (PCA) and an analysis of the cluster distribution.

## Project Overview
The goal of this project is to apply unsupervised learning techniques to cryptocurrency data in order to discover underlying patterns. K-Means clustering is used to segment cryptocurrencies based on their performance across several metrics, and PCA is employed to reduce the dimensionality of the data while maintaining most of the variance.

## Features and Data Description
The data consists of several metrics such as price change percentage over various timeframes, which can be found in data/crypto_market_data.csv.

## Installation and Usage
Before running the analysis, ensure you have Python installed and the required packages: pandas numpy matplotlib.pyplot hvplot.pandas sklearn.cluster sklearn.decomposition sklearn.preprocessing holoviews holoviews

## Results
The analysis reveals that cryptocurrencies can be grouped into clusters based on their market performance. The optimal number of clusters, determined by the Elbow Method, is visualized in the jupyter notebook file.