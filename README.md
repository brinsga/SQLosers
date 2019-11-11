# SQLosers

<b>IBM Social Good Datathon </b>

As a part of this datathon, we worked on building a system that helps individuals to visualize a heatmap and find neighborhoods in the San Francisco Bay Area based on their estimated rent burden in different neighborhoods.

High rent prices are a huge concern in the San Francisco Bay Area. Even high skilled workers are finding it difficult to afford the rent prices. Our system takes as input a user's income and zip code and calculates the user's rent burden and provides a heatmap of the neighbourhoods in bay area showing which places will offer a lesser rent burden and which places will offer a higher rent burden. 

In addition to providing heatmaps for the current situation. We used Zillow's research dataset to get the house rent prices of 
various neighborhoods in the last 4 years and used a time series analysis based <b>ML model Auto ARIMA(Auto Regressive Integrated Moving Averages)</b> to calculate the rent prices in the upcoming years to show users what is their predicted rent burden in the 
upcoming years. 


This could help:
1) People to analyse the rent burden situation and find affordable options and plan for thr future.
2) Policy makers can analyze the rent burden situation for an average income household in the Bay Area and use it to as 
a tool to set up rent control and introduce new policies. 


Next steps:

1) Include more features to the machine learning model like rent control data, eviction data and also increase the granualarity of data from zipcodes to address based.
