# (Ford GoBike system Dataset)
## by (Amulya Kandukuri)


## Dataset

>The dataset includes information about bike trips covering San Francisco area. 
>This dataset includes information about various trips like duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, bike_share_for_all_trip. 
>This dataset mainly focus on rides in February 2019. 
>For my data wrangling process, i have created new variables from the existing variables. for example, i created start_hour, day_of_week, time_day from the start_time and end_time variables.
>I have dropped some columns like start_station_id, end_station_id, start_station_latitude, start_station_longitude, end_station_latitude, end_station_longitude as they are irrelevant to exploration. I have also dropped rows that contains missing values.

## Summary of Findings

1. Most bike rides were taken by subscribers when compared to customers.
2. Most trips were taken during 8am and 5pm in a weekday.
3. Most bike trips on weekends were taken during 1pm.
4. The most long duration trips were taken by customers.
5. Customers have more number of long trips rather than subscribers.


## Key Insights for Presentation

1. On Saturday and sunday, long duration trips were taken when compared to remaining weekdays.
2. The longest duration trips were in less number when compared to short duration trips.
3. Mostly customers taken trips on weekends and subscribers on weekdays.
