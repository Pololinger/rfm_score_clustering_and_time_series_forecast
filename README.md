# Superstore dataset 

In this project, I’m exploring the Superstore dataset and use the data on orders and customers to create recency, frequency, and monetary (RFM) score for each customer. I use the silhouette score to determine the K for K-Means and cluster based on the RFM score as well as features from the original dataset. 

In the second part of the project, I’m using Facebook’s Prophet for Time Series Analysis to forecast the number of orders. In the first part I’m using cross-validation for each customer segment to get a sense of how robust the forecasts are. In the second part, I’m making a forecast across all segments. 

The data is taken from Kaggle - https://www.kaggle.com/jr2ngb/superstore-data
Provided you do ‘pip install kaggle’, there is command in each juypter notebook to retrieve the dataset via the Kaggle API. 
