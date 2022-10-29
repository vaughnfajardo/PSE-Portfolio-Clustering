# StockPortfolioKMeans

# About
StockPortfolioKMeans aims to create a diversified stock portfolio from the Philippine Stocks Exchange using K-Means Clustering. 

# Methodology
The data was first cleaned and processed. Unnecessary features were removed. Data types were fixed. The mean and variance of the daily price of different companies across a timetable of 7 years was first gathered. After this, the elbow method was used to calculate the sum squared error for various cluster. Plotting the number of clusters on the x-axis and the SSE on the y-axis, it was decided that 4 clusters would be enough with the decrease in error rate. After this, the dataset with clusters of 4 was fitted by the K-Means model. After removing some outliers, the process of fitting the model was done once again.

# Conclusion
Overall, it was found that stock diversifacation in the PSE generally tends to differ according to the stocks' liquidity and type (preferred, low-cap, mid-cap, high-cap, blue chip).
