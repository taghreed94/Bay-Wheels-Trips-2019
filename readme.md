# Bay Wheels Trips in 2019
## by Taghreed Fayez



## Dataset

We will investigate Bay Wheels trips for year 2019, Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. The data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

The Data of trips in 2019 downloaded from [Bay Wheels trip history data](https://www.lyft.com/bikes/bay-wheels/system-data), There are 12 csv files (one for each month).

After Joining the files and do a little wrangling, The final Dataset has 2506983 rows and 13 columns. The main numerical feature is the Duration of trips.

We will Try to answer questions like:
- When are most trips taken in terms of day of the week, or month of the year?
- How long does in average trip take?
- Does the above differ if a user is a subscriber or customer?



## Summary of Findings

- Most trips' duration range between 3 - 30 minutes, with some outliers over 300 minutes.
- About 80% of users are Subscribers & 20% of users are Customers, but Customers have longer trips in average compared to Subscribers.
- Excluding Outliers, Subscribers tend to have shorter Trips about 10 minutes in average, While Customers have longer trips about 13 minutes in average.
- In Weekend (Sat & Sun) the count of trips is the least compared with other weekdays for Subscribers, No much difference for Customers.
- But the trips duration is longer in average about 28 min for customer & about 13 min for subscriber In Weekend.

## Key Insights for Presentation

> About 80% of users are Subscribers & 20% of users are Customers, But Customers tend to have longer trips in average compared to Subscribers.