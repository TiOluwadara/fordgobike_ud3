# (Ford GoBike System Data)
## by (Oluwadara Akano)


## Dataset

> Ford GoBike System dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data set was downloaded on the Udacity website through this link [here](https://video.udacitydata.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv). The dataset contains 16 columns (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip) and 183412 rows. The dataset has some quality issues which included wrong data types, missing values. The datatypes were changed, missing values were dropped, some extra columns were also extracted from the original data to help with exploration (age, duration_min, start_weekday, end_weekday, start_hour, end_hour). The final cleaned dataset have 29 columns and 174952

## Skills
> - Data Wrangling
> - Exploratory Data Analysis
> - Data Visualisation
> - Communication and presentation of findings

## Summary of Findings

>For the exploration, I got these observations 
There are two types of users, customers and subscribers, subscribers constitute a large percentage 
Thre types of genders, males, females, others, males are more represented because they love riding more
Most people started and ended their trips on thursdays, and we have less people riding on saturdays and sundays (weekend)
It seems the most start stations are still the most used end stations, Market St at 10th St is the 2nd higest end station relative to the first position in start station while San Francisco Caltrain Station 2  (Townsend St at 4th St) is the first end station here relative to its 2nd start station position 
About 90% of the users do not share their trips, out of 10 people, only 1 would share
Most users have ages ranging from 30 - 40 years, with about 29 people above 100 and the oldest person is 144 years
The averate duration for a bike ride was about 11 minutes
The average duration a customer spends on a bike trip is about twice the duration a subscriber would spend. Customers spend more time while riding compared to subscribers
Males spend less time on average, probably because they are generally physically stronger than females. 
Customers are only composed of two gender types, males and females
The number of subscribers ridng on saturdays and sundays are reduced while it is increased during the week. It might be because they have to ride to work during the week. Most subscribers prefer early morning (8am) and evening rides(5pm) which also relates with when work starts and ends.
The people that did not share the trip on weekends reduced probably because they were all rushing to do something else on a weekend and because less number of subscribers ride on weekends
The only people that shared their trips were all subscribers, although a larger percentage of them, didnt share. It might be that ther is no share feature for customers, and that being a subscriber increases your chance of sharing your trip
On weekends, customers spend more time on their trips, maybe customers just love riding for fun and keep going on weekends
It seems people like spending more time on riding in the middle of the night compared to during the day
Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.


## Key Insights for Presentation

>For the presentation, I would focus on the subscribers and customers, why thier behaviour in riding is different. I would also focus on the age group and difference in gender groups
The types of users we have are subscribers and customers. Subscribers prefer riding during the week, at the beginning and end of work hours because they are the working class people and they ride their bikes to thier workplaces. Also, the preferred start stations constitute the end stations, which supports the insight that the users are routine riders that use the stations everyday to go to thier work places. Customers prefer ridng on weekends probably because they just ride for fun and don't use it routinely, they also spend more time on their rides because they are probably not paying or they want to use all they can get on free versions before going ahead to subscribe.
Only subscribers share their trips, it is possible that there is no sharing feature for customers i.e. no sharing feature on the free version until you subscribe. Although, most subscribers still don't share because they are the working class and probably do not have time to share and would prefer to do something else with their time. Users spend more time riding in the midnight (early hours of the day) compared to the other hours of the day.

>It is also noted that the average age range of riders are 30-40, because this is middle age where the energy to dispense for riding is available. The older age group might be the leisure riders. Males spend less time on their rides because they are more physically fit in comparison to females.
