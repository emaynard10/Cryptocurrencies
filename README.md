# Cyptocurrencies
Using unsupervised machine learning to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

#### Tools: Jupyter Notebook, Pandas, Kmeans, PCAs, hvplot, plotly

## Purpose of Analysis
The purpose of the analysis is to use unsupervised machine learning to cluster data. The project began by preprocessing the data with Pandas. This includes cleaning the data and using get_dummies() to convert to numerical values. Then scaling the data with StandardScaler from the sklearn library. Then the Principal Component Analysis algorithm is applied to reduce the number of features to 3. The K means algorithm is then applied using the elbow curve to get the best value for K. Joining the cleaned dataset with the PCA data yields a new dataframe with information on crytopcurrencies and their clusters or 'class'. The data is visualized with a 3D scatter plot to see the different clusters. Finally, the total coins and total mined coins columns are scaled and fit to be plotted on a scatter plot. 

## Summary 
The cryptocurrencies are successfully clustered into groups and the following visualizations show the cryptocurrencies that are on the trading market. 
The first cleaned dataframe looks like this before the get_dummies method is applied:

![Screen Shot 2022-08-11 at 2 22 16 PM](https://user-images.githubusercontent.com/99676466/184235283-96e8e3ce-534a-4fb6-a79a-4a910f6bedec.png)

Then the PCA algorithm calculated the reduced number of dimensions as shown in this dataframe:

![Screen Shot 2022-08-11 at 2 25 49 PM](https://user-images.githubusercontent.com/99676466/184235988-894ab38f-7170-4a31-ace1-28f851b3feaf.png)

#### Visualizations
First, the elbow curve helps determine that the best K value for using kmeans is 4. 

![Screen Shot 2022-08-11 at 12 51 10 PM](https://user-images.githubusercontent.com/99676466/184233327-cf3a5be7-e7e5-4e4d-843b-64c0e19fa541.png)

Then the 3D scatter shows the cryptocurrencies grouped into clusters with the class 2 Bitorent cluster looking like an outlier. 
![Screen Shot 2022-08-11 at 12 53 29 PM](https://user-images.githubusercontent.com/99676466/184233369-5de44b8e-e3c4-4cfd-b68a-5c1854590746.png)

And finally, the scatter plot plots the total coins mined vs the total coin supply with the classes shown as different colors.

![Screen Shot 2022-08-11 at 12 54 21 PM](https://user-images.githubusercontent.com/99676466/184233401-a78ea25c-4406-428c-961d-3f0c71ec4b6a.png)

### Contact

[Email](emaynard10@gmail.com)

[LinkedIn](https://www.linkedin.com/in/emily-a-maynard/)

