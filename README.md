# Ford GoBike Data Exploration
## by Victoria Bloomingdale


## Dataset

I chose the Ford GoBike data set provided by the Udacity project page. The data set includes information for the month of February, 2019, about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

The data type had to be changed for several variables before analysis. Changes were made for the following:
1. 'start_time' and 'end_time', from string to datetime
2. 'start_station_id', 'end_station_id', and 'bike_id', from float to string
3. 'user_type' and 'gender_member', from string to category
4. 'member_birth_year', from float to int


## Summary of Findings

I was most interested in looking for particular user groups that either use the program more frequently and/or show longer trip durations.  
1. I decided to focus on the types of users and gender. Subsribers and male users used the bikes the most. 
2. Most users were between the ages of 20 and 45. 
3. The bikes were used most frequently between 7 and 9am, as well as, 4 and 7pm. This coincided with commute hours. 
4. When looking at the days of the week, the bikes were mostly used for the week days. Again, this coincided with a regular work week. 
5. Most trips lasted between 3 to 18 minutes.
6. When looking at age range and duration, again, most users were between the ages of 20 and 45.
7. Combining trip duration with gender and user types, males and subscribers tended to take shorter trips than other groups.
After exploring the data, I decided to focus on the relationships between fruequency of use, trip duration, and user types. 


## Key Insights for Presentation

1. Higher user numbers did not translate to longer trips.
2. The bikes were mostly used for work commute, where users wanted to travel to and from work quickly. Longer trips tended to happen on the weekends across all user groups. 
