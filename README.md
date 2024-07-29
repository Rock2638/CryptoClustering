# CryptoClustering


**In this challenge, I use my knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.**

### Before Beginning
 A new repository called  `CryptoClustering`is created, cloned and pushed to GitHub.
    
### Files
The Starter Code folder is downloaded.  The Starter Code folder contains a Resources sub folder and the`Crypto_Clustering_starter_code.ipynb`file. Inside the Resources sub folder, there is a csv file called "crypto_market_data.csv". 
 - The  `Crypto_Clustering_starter_code.ipynb`  file is renamed as  `Crypto_Clustering.ipynb`.
 - The  `crypto_market_data.csv`  is loaded into a DataFrame.
 
 - The summary statistics and a plot of the data are obtained to see what the data looks like before proceeding.
 
#### Prepare the Data

 -   The  `StandardScaler()`  module from  `scikit-learn`  is used to normalize the data from the CSV file.
    
 -   A DataFrame with the scaled data and the "coin_id" index from the original DataFrame as the index for the new DataFrame is created.
________________________________________________________________
#### Plots and Visualisation    
        
 - The Best Value for k Using the Original Scaled DataFrame is found.

 - The elbow method is used to find the best value for k. 

 - The Cryptocurrencies are clustered with K-means Using the Original Scaled Data

 - The Clusters are optimised with Principal Component Analysis.

 - The elbow method is used on the PCA data and the best value for  `k`  is found.

 - The Cryptocurrencies are clustered with K-means using the PCA Data

#### Visualise and Compare the Results 

-   A composite plot is created by using hvPlot and the plus sign (`+`) operator to compare the elbow curve that you created from the original data with the one that you created from the PCA data.  Another composite plot using the multiply sign (`*`) operator shows the two plots overlayed as well.
    
-   A composite plot is created by using hvPlot and the plus (`+`) operator to compare the cryptocurrency clusters that resulted from using the original data with those that resulted from the PCA data. 
    
