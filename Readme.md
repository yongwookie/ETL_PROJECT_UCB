ETL - Project Report

For our project we chose to compare restaurant reviews on yelp and zomato. For our yelp reviews we got the data in CSV format from kaggle. For the zomato data we went straight to the source and used API queries to get our data. Zomato also has an interface to obtain the data but we made API calls from our ipython notebook. 
For our yelp data we started our cleaning process by first getting rid of extra and useless columns. Then we checked for invalid data and duplicated data. After dropping the extra columns and rows with null and duplicate values we merged the two yelp datasets we had on their business ID. This gave us a cleaner data with the city name, coordinates, reviews, star ratings, etc.. 
Getting our zomato data was a difficult task because the zomato api has a different structure and it also has a lot of data. 
Our final database is called ETL database and it has the yelp and zomato data as collections

