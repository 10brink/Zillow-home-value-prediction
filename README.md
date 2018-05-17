# Zillow-home-value-prediction
using a scraper to get addresses from recently sold homes on zillow, putting those into the zillow API to get attributes, then building a model to predict home values based on those attributes

the scraper and api function were slightly modified from code I found on github. 

Zillow doesn't like people scraping their website so it might not work again after the first few times.

Run the scraper function (you can modify the url to get the city you want), it will export a csv file. 



you will need your own zillow ID to access the API. 


once you have the addresses from zillow (in the csv from the scraper)

you can put them into the ipython notebook to create a model for your city. 

point the api in the notebook to the csv that was created. 


Currently it only takes sq footage, number of bathrooms and bedrooms and year built as features. 
