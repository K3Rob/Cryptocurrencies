# Cryptocurrencies

## Purpose 
Create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. Process the data for use in machine learning models. Then use unsupervised learning process the data to group the cryptocurrencies.

## Results 
532 tradable cryptocurrencies were sorted into 3 groups in an interactive [3d scatterplot](https://github.com/K3Rob/Cryptocurrencies-/blob/main/Cryptocurrency/Images/pxscatter_3d.PNG). Using the predicted K clusters a simple [2d scatterplot](https://github.com/K3Rob/Cryptocurrencies-/blob/main/Cryptocurrency/Images/hvplot_scatter.PNG) was created comparing the "TotalCoinSupply" and "TotalCoinsMined" after running both columns through a MinMaxScalar(). Both plots allow you to hover over the data and look at the points with the coin names included when the program is run.
