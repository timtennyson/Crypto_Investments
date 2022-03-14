# Crypto Investments

This application clusters cryptocurrencies by their performance over different time periods

## Technologies
[Python3.7](https://www.python.org/)

[Jupyter Lab](https://jupyter.org/)

[Pandas](https://pandas.pydata.org)

[Pathlib](https://docs.python.org/3/library/pathlib.html) 

[hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html)



## Installation guide
In order to run this application you'll need to install Python3.7 in conjunction with jupyter lab along with the libraries linked above. You'll also need to install the libraries listed above. 

## Part 1)-- 

### 1) Find the best value for K Using the Original Data
Using the elbow method, we find the best value for k.
We plot a line chart to visually identify the optimal value (the "kink" in the line) 

### 2) Cluster Cryptocurrencies with K-means Using the Original Data
Initialize the K-means model to cluster the cryptocurrencies.
Create a scatter plot to show the clusters.
### 3)Optimize Clusters with Principal Component Analysis
Here we set a PCA model instance with n_components=3. We then create a new dataframe using the simplified data, and retrieve the explained variance for each component.
The total explained variance is the sum of the 3 component variance values.


### 4)-- Find the Best Value for k Using the PCA Data
Same as above, but this time with the PCA Data. In this instance the optimal value for "k" is the same (4).

### 5) Cluster Cryptocurrencies with K-means Using the PCA Data
Same as above, but using the PCA data.
We then do a comparison plot of the optimal value for 'k' using both the PCA and the original data


## Conclusions

PCA allows for better visualization of the clusters.

## Contributors

Tim Tennyson 
<ttennyson.xyz@gmail.com>

License: Open source, free distribution/reproduction
