# Cryptocurrencies-
Crypto_currencies_ML_unsupervised
For this project. i used classification to group various cryptocurrencies.
This project accomplishes the following main tasks:

Data Preprocessing:

  . Data is prepared for dimension reduction with PCS and clustering using K-Means.
  
 Reducing Data Dimensions using PCA:
 
  . Completion of this project results in the 3 PAC components of the dataframe:
  
  ![Screen Shot 2022-12-12 at 11 19 03 AM](https://user-images.githubusercontent.com/55648656/207111003-484f38a4-657f-447c-8996-05bd8b7e8149.png)

  Clustering Cryptocurrencies Using K-Means:
  
    . An Elbow curve is created to find the best value for K.
    
    . Once the best value for K is defined , the K-Means algorithm is used to predict the K clusters for the cryptocurrencies data.
    
    ![Screen Shot 2022-12-12 at 11 26 25 AM](https://user-images.githubusercontent.com/55648656/207112553-1bc2a279-caeb-4432-b4bb-c7a18287fa15.png)
    
Visualizing Resuts :

. A 3D-Scatter plot is created using Plotly Express to plot the clusters.
. hvplot.table is used to craete a data table with all the current tradable cryptocurrencies.
. A scatter plot is created using hvplot.scatter, to represent the clustered data about cryptocurrencies having x ="TotalCoinsMined" and y="TotalCoinSupply" to cantrast the number of available coins versus the total number of mined coins.
