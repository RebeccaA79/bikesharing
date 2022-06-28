# Bike Sharing Analysis

## OVERVIEW
### Purpose:  The purpose of the following analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can see for themselves that a bike-sharing program in Des Moines is a solid business proposal.  Among others, we have prepared visualizations that 1) Show the length of time that bikes are checked out for all riders and genders, 2) Show the number of bike trips for all riders and genders for each hour of each day of the week, and 3) Show the number of bike trips for each type of user and gender for each day of the week.


## RESOURCES
  - Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
  - Software:  Tableau, Python 3.7.6, Jupyter NB, Pandas Library


## RESULTS
#### The results of the analysis have been incorporated into a [story on Tableau Public](https://public.tableau.com/profile/john.ramonetti#!/vizhome/NYC_CitiBike_Visualizations/FinalPresentation?publish=yes)


 - Based on Checkout Times for Users line chart, the majority of rides are less than one hour with peak usage around 5 minutes.

- Checkout Times by Gender follows a similar pattern in trip length to the Checkout Times by Users with most trips lasting under 20 minutes. Males do hold a much larger proportion of rides in comparison to females and unknown.

- The Trips by Weekday per Hour heat map shows that bike usage is heaviest on weekdays during commuting times (Between 7am and 8am and between 5pm and 6pm). On weekends, the bike usage is heavier during the day with Saturday being the busiest day. Peak usage appears to be between late morning and early afternoon.

- The Trips by Gender (per Weekday and hour) heat map shows a similar pattern as the heat map above, regardless of gender. As shown in the 2nd line chart above, males do hold the largest share of rides.

 - The 'User Trips by Gender by Weekday' heatmap shows most subscribers are male and hold most of the weekday activity.  The customers' gender is often unknown and usage on the weekend is more evenly split between subscribers and customers.

 - The Average Trip Duration by Age shows that in general, the younger the person the longer the bike ride.

 - The gender breakdown pie chart shows that males hold the most usage of bike rides. This information could be useful in exploring further and how to increase marketshare among women.


## SUMMARY
### The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. We've seen the patterns of useage by time and by gender.  Utilization rates can now be predicted based on time of day and location.  Weekday useage is heavily concentrated around the morning and afternoon commute.  Weekend useage is more evenly spread through the day.  We would recommend further analysis for a few points.  Firstly, while we've seen that the vast majority of trips are 30 min or less, we should perform further analysis to compare weekend trip durations to weekday trip durations.  We should also look further into the patterns of useage for the bicycles that see the heaviest use, perhaps preparing maps showing all of the starting/ending routes/locations for the heaviest use bikes.  We should also prepare a visualization to determine if there are specific locations that are completely unused.

