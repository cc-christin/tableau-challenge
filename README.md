# tableau-challenge
[tableau public](https://public.tableau.com/app/profile/christin.sok3221/viz/tableau-challenge_16533661101650/Story_1)

## ETL
* Data for the full year of 2020 were downloaded from [NYC Citi Bike Data](https://www.citibikenyc.com/system-data). 
* All CSVs were combined into one CSV, [bike_full_2022](https://github.com/cc-christin/tableau-challenge/blob/main/Resources/bike_full_2020.csv). 

## Data Analysis/Phenomena
#### Understanding Bike Rides/Trip Duration Data
* The timeframe selected was the full year of 2020, where there was a total of 1,846 unique citi bikes (bikeIDS) and a total of 323,351 bike rides taken. 100,982 rides were taken by single-ride-customers and 222,369 rides taken by subscribers. The breakdown of customers to subscribers for 2020 would be 31 % to 69 %. The average subscriber has an average trip duration of 830 seconds, while the average customer has an average trip duration of 3,269 seconds. Customers in 2020 took 10,408 distict trips while subscribers took 5,789 distict trips. 

[total count by bikeID](https://github.com/cc-christin/tableau-challenge/blob/main/Images/001.png)

[user_type](https://github.com/cc-christin/tableau-challenge/blob/main/Images/002.png)

#### Understanding Most Used Starting and Ending Stations and Visualizing (MAPs)
* The top five starting stations measured by bike use are Grove St PATH (22,004), Newport Pkwy (19,042), Liberty Light Rail (16,286), Hamilton Park (14,155), and Sip Ave (13,202). The bottom five starting stations are Dey St (1,560), Union St (1,559), Jackson Square (1,445), Leonard Gordon Park (1,093) and JCBS Deport (1).
* The most popular starting station, Grove St PATH accounts for 6.8 % of all bike use in 2022.  
* The top five ending station measured by bike use are Grove St PATH (25,167), Newport Pkwy (19,197), Liberty Light Rail (16,534), Hamilton Park (14,348), and Marin Light Rail (12,977). 
* The top four starting and ending stations are the same while the ending stations have over 40 stations registering only 1 bike use ending.  
* Maps of starting and ending stations were made to determine which of the stations had the longest trip duration in comparison to the frequency of use by bikeID.
* Union St has the longest average trip duration (4,782) seconds in comparison to it's usage frequency of (1,559) by count of bikeID. 
* Most popular starting and ending station, Grove St PATH, only has an average trip duration of 937 seconds. One can assume that there are more frequent shorter trips occuring at Grove St PATH. 
* Grove St PATH has usertype breakdown of 3,913 customers to 18,091 subscribers as a starting station and 4,899 customers to 20,268 subscribers as an ending station.
 
The location of the top five starting and ending stations might have contribute to their frequent use as they are generally located in the downtown area with the exception of Sip Ave. The frequent but short trip duration might such as the case in Grove St PATH might be why these stations are forming a natural hub for both starting and ending destinations.   
Subscribers account for 69 % while customers make up the remaining 31 %  of all citi bike useage in 2020. Grove St PATH has a usertype breakdown of (18,091) 82 %  subscribers and (3,913) 17 % customers out of a total of (22,004) as a starting station, slightly higher than the overall average. 
