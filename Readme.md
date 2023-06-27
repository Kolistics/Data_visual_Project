Introduction

The data includes details on 183,412 trips taken in a bike-sharing program that serves the larger San Francisco Bay area. In addition to duration (secs), the data characteristics also contain Date-Time, Customer Type, Gender, and a few more variables.

DATAFRAME WRANGLING AND ANALYSIS

From the dataframe we were given the locations in terms of longitude and lattitude, which means we can get the distance between the start and stop stations.

* Using The Haversine FUnction to Calculate For the distance

* Since we know the distance and the time for the trips, then we can calculate the speed of the Journey.

                  speed = Distance / Time

structure of the dataset?

* This dataset has 183412 rows by 25 Columns and includes details on 183,412 trips taken in a bike-sharing program that serves the larger San Francisco Bay area. In addition to duration (secs), the data characteristics also contain DateTime, Customer Type, Gender, and a few more variables.

The main feature(s) of interest in the dataset?

* The main feature of interest in this dataset i think is the duration of the rides, checking to see if features like distance, member gender or Age has an influence on the time spent on a journey.

Features in the dataset I think will help support my investigation into my feature(s) of interest?

* distance, member's Age from Birth year

SUMMARY OF FINDINGS

In my research, I discovered that trips typically last 500 seconds on average and that Tuesdays and Thursdays are the busiest days. The fewest trips have occurred on weekends, while having higher durations than other weekdays. The higher trip records for the eighth and ninth hours of the morning and the seventeenth and eighteenth hours of the evening are something else I discovered to be fascinating. The bustle at the two times of the day may be responsible for this. Almost 90% of the rides were taken by subscribers, while more than 70% of all rides were taken by men.

The number of rides on any given day does not appear to be impacted by user type. Also, compared to subscribers, customer user type tends to spend more time traveling on any given day.

I discovered that non-subscribers spend far longer on their excursions than regular customers do, and women typically ride for longer than men do. Bicycles can only be shared on excursions by subscribers, and these journeys make up roughly 10% of all rides.

IMPORTANT TAKEAWAY FOR PRESENTATION

I exclude other factors from the display and concentrate on the duration and frequency of rides per day and user type. I begin by using Seaborn Countplot to plot and examine trip frequencies by day of the week, and user type.

Then I go over each of the categorical variables individually. I begin by using the length over days and user type boxplot graphs. The following section uses point plots to discuss the other two categorical variables, days and user type. To ensure that it is obvious that each quality variable differs between plots, I have taken care to utilize distinct color palettes for each of them.
