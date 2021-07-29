# UCB-Crytocurrency_Unsupervised_ML-A18

Cryptocurrencies analysis using unsupervised machine learning

## Overview 

The aim of this project is to examine the cryptocurrency data using unpservised machine learning models. 

### Steps 

1. Data Cleaning - cleaned, encoded and scaled more approperiately for the algorithms. 

2. Used Principle Component Analysis (PCA) to decrease the dimension of the dataframe for downstream analysis 

3. Applied K-means algorithms to generate an elbow curve plot which allows us to decide the best k value and the best number of clusters for this data. 

![Elbow Curve Plot](Images/Cypto_PCA_elbow_curve.png)

4. Visualisation of the data. 

      - Generated a 3D scatter plot using PCA data 

      ![3D Plot](Images/3D_scatter.png)

      - Transferred data for "Total Coin Supply" & "Total Coins Mined" for generating a 2D scatter plot 

      ![Scaled 2D plot](Images/hv_plot.png)


