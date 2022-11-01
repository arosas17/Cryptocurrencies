# Cryptocurrencies

## Overview

An investment bank wants to put together a portfolio of new cryptocurrency investments. To assist in creating this portfolio, an unsupervised learning model is used since the desired output is unclear. These results are shown in a 3D scatter plot and a regular scatter plot to give a visual representation of the data.

## Results

![Elbow_Curve.png](/Images/Elbow_Curve.png)

This data had to be preprocessed prior to making the data into three principal components through the PCA technique which was used to create an elbow curve to find the best value for K. The best value of K was determined to be 4.

![3D_ScatterPlot.png](/Images/3D_ScatterPlot.png)

Based on the best value of K in the elbow curve and the three principal components, a 3D scatter plot was created. This 3D scatter plot shows four classes grouped together. This information shows that class 2 is an outlier where it is a single plot on the plot farther away from the other classes (this outlier is identified as BitTorrent).

![ScatterPlot.png](/Images/ScatterPlot.png)

The last plot created is a scatter plot with the TotalCoinSupply on the y-axis and the TotalCoinsMined on the x-axis after performing the `MinMaxScaler` technique in the data. This data, like the 3D scatter plot, is color coordinated by class. Seemingly, there is not many points for class 2, where there are only two visible dots. Other notable observations are the two outliers that occur in this plot. Most of the data ends up towards the bottom-left where the cryptocurrencies suggest getting low TotalCoinSupply and TotalCoinsMined. One is TurtleCoin which is a cryptocurrency in class 1 that has a fairly low TotalCoinsMined but large TotalCoinSupply. The other one is BitTorrent, noted from the 3D scatter plot, that has both a high TotalCoinsMined and TotalCoinSupply.


## Summary
