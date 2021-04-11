# Communicate Data Findings

## Ford-GoBike-Data-Exploration-and-Visualization
#### by: Raffael Schlender

## Data
The data analysis is based on a real dataset from the Ford GoBike trip data of users in San Francisco Bay Area. The main focus is to wrangle and explore a `201902-fordgobike-tripdata` datafile by using Python visualization libraries, starting from plots of single variables and building up to plots of multiple variables. 
The original dataset contains more than 183k rows and 16 columns. The attributes included the start and end time of the trips, as well as additional measurements such as user type, gender, and birth year. During the data wrangling and cleaning process more than 13k rows were removed, because of illogical data points and outliers.

#### Data Cleaning

The most important data cleaning steps included:

> - Convert / correct data types
> - Remove data where bike time duration > 60 minutes
> - Create new variables like day of week, hour of day or member age
> - Delete illogical data

## Key Findings
#### Bike Time Duration
As a first attribute the bike duration time was investigated. The distribution of biking durations is skewed. The range of data points are between 1 minute to 1400+ minutes. The average is around 12 minutes and the median at around 9 minutes. For useful visualizations some data transformation was needed.
#### Bike Ride Trends
>- On Thursday between 5:00 and 6:00 PM the most bike rides are started, compared to the whole week and other hours.
>- Over the whole day, more male biker starts their trip than female riders with data peaks at 8:00 to 9:00 AM and 17:00 to 18:00 PM.
>- Over the whole day, more Subscriber (Member) starts their bike rides with data peaks at 8:00 to 9:00 AM and 17:00 to 18:00 PM.
>- Thursday has the most male and female bikers compared to other days. It also has the most Subscriber bikers compared to other days.
>- The weekend has the lowest frequency of bike rides in term of gender and user type compared to the rest of the week.
>- Most of the bikers are younger than 40 years across the whole week.
>- On the weekend the bike trips are on average longer compared to the trips on other days.

## Slide Deck
>- The bike duration time is visualized without and with a log scale for better insights and interpretations. 
>- Insights about the age of bikers are shared.
>- Biking days and time are analyzed and visualized.
>- Gender and user type of bikers are shared.
