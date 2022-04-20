# Bikesharing Tableau Analysis

## Overview  
This project uses Tableau to create visualizations and provide an analysis of Amazon Web Services' [NYC Citi Bike data](https://s3.amazonaws.com/tripdata/index.html) from August 2019.

## Results
Please find the link to my Tableau dashboard [here](https://public.tableau.com/app/profile/madeleine4973) (click on "Module 14 Challenge"). The separate charts are also displayed below. 
* [Checkout Times for Users](https://public.tableau.com/authoring/Module14Challenge_16326839417930/CheckoutTimesforUsers#1)   
This chart shows the length of every bike trip that lasted up to 2 hours for riders in August 2019. The screenshot shows that the most common trip length in August 2019 was a 5 minute trip, with 146,752 trips lasting 5 minutes.
![image](https://user-images.githubusercontent.com/86338416/134822950-c23fc12b-7ae0-4b44-b3c3-8387aabfbc2a.png)

* [Checkout Times by Gender](https://public.tableau.com/authoring/Module14Challenge_16326839417930/CheckoutTimesforUsers2#1)   
This chart shows the length of every bike trip that lasted up to 2 hours, filtered by gender.  
![image](https://user-images.githubusercontent.com/86338416/134823292-af572902-7d2e-4e66-a7fe-dc157dafc445.png)  


* [Trips by Weekday for Each Hour](https://public.tableau.com/authoring/Module14Challenge_16326839417930/TripsbyWeekdayforEachHour#1)  
This heatmap shows the number of bike trips by hour for each day of the week. The darker the color, the greater the number of trips for that day/hour.
![image](https://user-images.githubusercontent.com/86338416/134823314-56c90b06-b589-4865-876f-d97890eacf67.png)


* [Trips by Gender (Weekday per Hour)](https://public.tableau.com/authoring/Module14Challenge_16326839417930/TripsbyGenderWeekdayperHour#1)  
This heatmap filters the number of bike trips by gender, shown by the hour and separated by each day of the week.  
![image](https://user-images.githubusercontent.com/86338416/134823326-ca6ceb58-56d6-4ed4-957c-f582fe22292c.png)  


* [User Trips by Gender by Weekday](https://public.tableau.com/authoring/Module14Challenge_16326839417930/UserTripsbyGenderbyWeekday#1)  
This heatmap differentiates between subscribers and customers (non-subscribers), gender, and usage by weekday. Male subscribers have the highest number of trips on Thursdays. 
![image](https://user-images.githubusercontent.com/86338416/134823343-3330bcd0-a746-4c37-ac2e-24d10501dc72.png)  


### Additional Visualizations
* [Gender Breakdown](https://public.tableau.com/authoring/Module14Challenge_16326839417930/GenderBreakdown#1)  
This pie chart shows the user breakdown by gender.  
![image](https://user-images.githubusercontent.com/86338416/134823353-72e942dd-ad4a-4faa-ae0f-af8df874c92f.png)

* [Top Starting Locations](https://public.tableau.com/authoring/Module14Challenge_16326839417930/TopStartingLocations#1)  
This chart shows the top starting locations in NYC (the bigger/darker the bubble, the greater the number of trips started at that location).  
![image](https://user-images.githubusercontent.com/86338416/134823395-5e03b3c3-e4e3-4e30-8869-0c2b8e9cff90.png)  

* [Top Ending Locations](https://public.tableau.com/authoring/Module14Challenge_16326839417930/TopEndingLocations#1)  
This chart shows the top ending locations in NYC (the bigger/darker the bubble, the greater the number of trips ended at that location).  
![image](https://user-images.githubusercontent.com/86338416/134823416-49d1f346-7232-4259-96bf-d9d20c972358.png)  


## Summary  
These visualizations show that there are many more male riders than female riders. More than half of the riders are male. The most common bike trip length is 5 minutes, meaning that most riders use the bikes for a fairly brief amount of time. During weekdays (Mon-Fri), the bikes are most commonly used before and after regular work hours, around 8am and 5-6pm, respectively. During the weekends, the bikes are more commonly used throughout the entire day (9am - 7pm). These patterns suggest that these bikes may be used for commuting transportation during the week and for more non-work activities during the weekend. The same heatmaps which are then separated by gender also show similar bike usage patterns by the day/hour. There are more subscribers than non-subscribers (customers), suggesting that there is a larger audience that consistently uses the bikes. The most popular starting and ending locations seem to be located in the more populated areas of New York City. It also appears that Thrusday is the day with the most trips.

Two additional suggested visualizations for future analysis would be to create a similar map as the "Top Starting Locations" visualization, but to add a color filter to differentiate between starting locations on weekdays versus weekends. The same could then also be done for "Top Ending Locations." If you toggle the day filter, you can see that the most rides occur on Thursdays and crowd out the relative represenation of the other days' data in the visual (see screenshots below). The next question may be to ask: why is Thursday bikeriding so popular?

Example of the "Top Starting Locations" visual filtered by day, with and without Thursday.  
* Excluding Thursday:   
![image](https://user-images.githubusercontent.com/86338416/134824050-dbaaf789-690a-4fea-84dd-c12396821438.png)  

* Including Thursday:  
![image](https://user-images.githubusercontent.com/86338416/134824081-bd5e1ac6-52a7-4192-9e4d-6479288661dd.png)  

* Top Starting Locations -- Weekday Edition:  
![image](https://user-images.githubusercontent.com/86338416/134824152-d09cfd29-f266-48e1-bfa0-cf7de1fc6ffa.png)

* Top Starting Locations -- Weekend Edition:  
![image](https://user-images.githubusercontent.com/86338416/134824136-5fc5bef1-dc47-4149-a922-a4ed5a6aa52e.png)  


## Resources
* UC Berkeley Extension Data Analytics Bootcamp
* Amazon Web Services' [NYC Citi Bike data](https://s3.amazonaws.com/tripdata/index.html)




