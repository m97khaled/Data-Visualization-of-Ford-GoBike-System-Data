# Ford goBike Dataset Exploration
## by Mohamed Eldemerdash


## Dataset

> The dataset I chose is the Ford goBike dataset.

* Ford GoBike is a public bicycle sharing system. In 2013 the bike sharing service was introduced to the Bay Area in San Fransisco. Currently, the company is looking forward to provide more than 7000 bikes in the bay region.

> This dataset hold 183412 records of Ford GoBike data and consisted of 16 variables.
> Those variables are:

Trip duration info:

* duration(in seconds)
* start_time and end_time (Start and end timing of a trip)

Station info:

* start_station_id and end_station_id
* start_station_name and end_station_name
* start_station_latitude and start_station_longitude
* end_station_latitude, end_station_longitude

Bike and user info:
* bike_id
* user_type
* bike_share_for_all_trip<br>


## Summary of Findings


> After thoroughly investigating the variables we we can conclude that subscribers are using the Ford goBike more than casual customers. However, they do cycle for shorter fixed durations. We also found that there are patterns in subscribers' behavior on weekdays due to work where it peaks during rush hours at 07:00 and 19:00. Finally, we also deducted that casual customers vary and some of them also do commute to work.

List of important insights:
* Most trips are observed to take around 60 minutes at most
* The mean value for trip durations in minutes is about 8.5 minutes.
* Peak biking hours are around 08:00 and 17:00 which is the rush hour.
* Most bikers cycle in the time range between 07:00 till around 19:00
* Most subscribers cycle on weekdays to work which is suggested by the drop in the count on weekends. 
* Customers' count is consistent through out the week, which indicate that they cycle as a habit or for fun on their free time.
* Male bikers are more than threefolds female bikers.
* About 90.6% of all bikers are subscibers and enjoy more benefits since they are regular users.
* Both subscribers and customers maintain a similar pattern.
* Subscribers commute to work, therefore they are more active on weekdays than customers and drop on weekends.

## Key Insights for Presentation

The presentation follows a chronological order and a storytelling manner. It discusses the main questions asked in the exploratory data analysis. Some of these questions were: 
* How does each user type vary with trip duration in days and hours.
* Average trip duration in minutes

## Resources

Udacity Advanced Data Analysis track

Stackoverflow

towards data science
