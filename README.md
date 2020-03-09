# Hanoi Population density and wards clustering

## 1.	Description of the problem and Discussion of the background

Hanoi, the capital of Vietnam, is my hometown. The city was founded in 1010 by monarch Ly Thai To. Since founded, it has remained the most important political and cultural center of Vietnam. Today, Hanoi covers an area of 3,328.9 square kilometers with an estimated population of 8.1 million as of 2019. The city is divided into 12 urban districts, 1 district-level town and 17 rural districts. Nearly half of the city population is living in the urban districts which are further divided into 168 wards. 

Most of the economic and social activities are taking place in the urban area of the city. In the recent years, more and more restaurant and store chains have chosen Hanoi as their next destination. Famous chains include Starbucks, McDonald’s, KFC, Lotte, Jollibee, Highlands coffee and CGV … Usually when investors come, there are two important questions that they want to seek answers to: 
-	Where to open the first restaurant/shop?
-	Where will be the next locations after the first successful one?

Population density by district might be a good answer to the first question while location similarity in terms of popular venues can help answer the second one. In this capstone project, I will try to collect, analyze and visualize public data found on the internet using maps, charts and clustering technique as well as utilizing Foursquare API to help the investors make right decision. 

## 2.	Description of the data 

The following data will be used in this project: 
-	The third level administrative map of Vietnam that we can use to get coordinates of all the districts and wards in Hanoi. This will be used for creating population density map: https://gadm.org/download_country_v3.html
![Shapefile](https://github.com/neik83/Coursera_Capstone/blob/master/Spatialdat.png)
-	This site provides list of all districts and wards within districts in Vietnam from that we can extract the sub-list for Hanoi: https://www.gso.gov.vn/dmhc2015/
![Administrative Units](https://github.com/neik83/Coursera_Capstone/blob/master/AdmUnits.png)
-	Area and population of each district will be collected from this site:  
http://thongkehanoi.gov.vn/a/nien-giam-thong-ke-2018-1579246334/
![Area and Population](https://github.com/neik83/Coursera_Capstone/blob/master/Stats.png)
-	Last but not least, Foursquare API will be used to get most common venues for clustering the wards in the urban area of Hanoi.
