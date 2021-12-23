# Cryptocurrencies
## Overview 
The purpose of this project is to create a report to analyze the cryptocurrencies available on the trading market and to create a classification system to group them for investment using clustering algorithm.

## Result
Using Principal Component Analysis (PCA) algorithm, the dimensions of the X DataFrame (Features) to three principal components. Using K-means algorithm, an elbow curve was created using hvPlot to find the best value for K from the above created dataframe using PCA. The K-means algorithm was run to predict the K clusters for the cryptocurrencies’ data. Finally, using Plotly Express and hvplot, 3D scatter plot was plotted *(Fig 1)*.

![3dplot](https://github.com/chinzjay/Cryptocurrencies/blob/main/3dplot.PNG)
|:--:|
|Fig 1. 3D scatter plot using the Plotly Express scatter_3d() function to plot the three clusters.|

The distinct groups that correspond to the three principal components were visualized and a table with all the currently tradable cryptocurrencies was created *(Fig 2)*.

![cryptocurrency_table](https://github.com/chinzjay/Cryptocurrencies/blob/main/cryptocurrency_table.PNG)
|:--:|
|Fig 2. Table with tradable cryptocurrencies using the hvplot.table() function|

## Summary
Performing PCA on the dataset reduced the number of dimensions by transforming a large set of variables (98) into smaller ones (3) that contains most of the information in the original large set. 
