# Cryptocurrencies

## Overview 
___
The purpose of this project is to use an unsupervised machine learning algorithm to analyze a dataset of cryptocurrencies. Visualizations displaying groupings of cryptocurrencies and a table of traded showcasing the cryptocurrencies classified by groups is also provided. 

## Resources
___
* Datasource: [csv](https://github.com/asanchez116/Cryptocurrencies/raw/main/Resources/crypto_data.csv)
* Software: Python 3.7.7

## Results
___

Preprocessing and cleaning of the dataset yielded n=532 cruptocurrencies: 
1. Removed cryptocurrencies that were not being traded
2. Kept all currencies that have a working algorithm
3. Removed unnecessary columns 
4. Removed missing values 
5. Removed rows where no coins were mined 
6. Standardized data 

Principal Component Analysis (PCA) was used to reduce the traded cryptocurrencies to three principal components 


## Clustering Cryptocurrencies with K-Means

![scree plot](https://raw.githubusercontent.com/asanchez116/Cryptocurrencies/main/Resources/bokeh_plot.png)

The scree plot above suggests 4 is be an ideal number of clusters to group the cryptocurrencies using K-Means. 

3-D Scatter plot 
![3d scatter plot](https://raw.githubusercontent.com/asanchez116/Cryptocurrencies/main/Resources/newplot.png)

The 3-D scatter plot above was obtained using the PCA algorithm to reduce the cryptocyrrencies dimensions to three principal components. 

### Tradable Cryptocurrencies Table 
![table](https://raw.githubusercontent.com/asanchez116/Cryptocurrencies/main/Resources/table.png)

The table above includes the predicted clusters and cryptocurrency features. 

Most of the cryptocurrencies are part of class # 1 (n=289) followed by class #0 (n=238)
