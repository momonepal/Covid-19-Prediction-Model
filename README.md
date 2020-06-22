# Covid-19 Prediction Model

I have trained a model for the prediction of Covid-19 cases using Gompertz function through the use of API to extrct my data. 
We plan to observe how the trend is changing over time, the timeline for the curve to flatten and see the predicted number of cases. 

The data comes from coronavirus-tracker API (https://coronavirus-tracker-api.herokuapp.com/) 

Going furthur we can easily create a prediction model for any other country. We can simply enter the country's name in the function : maketable(country("country's name")) to extract the data we need for that country from the API and convert it into the dataframe of required format with days column. 

