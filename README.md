# PyBer Analysis

## __Overview__

This analysis summarize ride-sharing data into a DataFrame using Pandas and Python and creates a multi-line graph that shows the total weekly fares for the each city type; “Rural”, “Suburban” and “Urban” of “PyBer” system using Matplotlib with Pandas.

## __Results__

Considering following figure, there are following observations:
 
 
 ![PyBer_Summary](https://user-images.githubusercontent.com/107717882/179452955-9e50d0a1-3934-4ea0-b0b1-0a3fc77de360.png)


* Comparing total rides among each city type, we can say that number of total rides from rural cities is 13 times and 5 times lower than urban and suburban cities       respectively.

* Looking at the data of total drivers per each city type, it is obvious that urban cities have much more drivers compared to rural cities and suburban cities; 30       times more than rural cities and 5 times more than suburban cities. Suburban cities have approximately 7 times more drivers than rural cities. 

* Now consider the total fares for each city type. Urban cities have more total fare as they have more rides and drivers compare to rural and suburban. Total fare of     rural   cities is 10 times and 5 times lower than urban and suburban cities respectively. Suburban cities earn almost half of the urban cities in terms of total       fare.

* Urban cities have more rides, more drivers so they have lower fares compared to rural and suburban, approximately 2.5% lower and 5% lower than suburban and rural       cities respectively. This can’t be considered as noticeable difference. 

* Now look at the average fare per driver numbers, urban drivers get considerably lower amount compared to rural driver, almost 35% lower and approximately 4% lower     than suburban cities. Rural drivers rule on average fare per driver. 

* After all contrast and compare, there are factors that affect the summary data. Populations, events, restaurants, commercial buildings, working cultures etc. are       factors that affect the rides, drivers and fares data. Urban cities have more customers hence they have more rides and drivers but that keeps fares lower. On the       other hand, rural cities don’t have much rides and drives so fare is more here. Suburban cities have moderate numbers in terms of rides, drivers, total fares,         average fare per driver and average fare per ride. 

* Now consider following graph showing weekly total fares by city types for the period between January 2019 to April 2019, 13 weeks. 


![Pyber_fare_summary](https://user-images.githubusercontent.com/107717882/179454062-41b20313-99f4-4b04-ac18-dd019425173c.png)


* Total fare of rural cities stays between 50 to 500 during this range of time. Suburban line shows fare is between 700 to 1500. Urban line is on top, between 1600-     2500. These three lines are making parallel plotting means, they are showing constant data within some range without any drastic increase or decrease. In other         words, we can say that PyBer maintain steady rates for rides during this time period for each city type.

## __Summary__

Three business recommendations:

1.	According to statistics of data, increasing drivers in rural areas will increase rides, as rides will increase average fare will decrease. Lower fares will attract     more customers. Also, more people will have work opportunities. 
2.	To control average fare in each city type, Pyber should implement minimum and maximum rate policy. 
3.	There should be a system or live feed that shows number of customers waiting in each zone/area versus available drivers in urban cities, so drivers can decide from     where to get ride. By this way the rate can be maintain and each driver can get sufficient amount of fare per ride. 
