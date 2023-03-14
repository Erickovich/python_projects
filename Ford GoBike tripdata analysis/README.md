# Exploration of the Ford go-bike trips dataset
## by Eric Makuochukwu Udeh


## Dataset
The Ford GoBike system dataset contains records of individual rides made by users of the GoBike system in San Francisco in the month of february 2019. The datasets contained 183,412 (pre data cleaning) records. The dataset contains several variables such as the duration of each ride, the starting and ending points (stations) including their latitudes and longitudes, start and end timet of each trip, user type, gender and age of the user as well as the day of the week in which the ride occured. These informations can be analyzed to gain insights into patterns of usage and user behavior.

#### Cleaning Process.

Before begining exploration, it was important to generate two more variables that were not originally present in the data. The 'day of the week' variable and 'age' variable were generated from the ride's start date and member birth date columns respectively. 
While in the exploration phase of the analysis, a series of data quality issues were ofserved and taken care of. Some of these issue are:
- Erronous datatypes of some of the variables,
- ages that seemed beyound posible limits, 
- some missing values, 
- as well as columns that are irrelevant to this analysis.

## Summary of Findings
Upon analysis of the given dataset, the following findings were genereated:
The GoBike data shows that the majority of riders are between the ages of 18 and 40, with far more male riders than female and other genders. Most rides are less than 10,000 seconds, but some can be up to 86,000 seconds. Thursdays see the most rides, while weekends are less frequent. There are almost nine times as many subscribers as there are customers, and both groups have members mainly aged between 20 and 40. 
futhermore, there is no clear correlation between the ages of riders and duration spent on a ride, although, male riders accounted for the majority of the cumulative time spent on rides.

## Key Insights for Presentation
Further exploration of data indicates that the gender of riders does not impact the duration of rides, and the greater cumulative duration of rides by male riders is due to their higher numbers in the dataset. While it is unclear whether a particular user type spends more time on rides, as the charts didn't show any such pattern, it is evident that a lot more subscribers spend less than 300 seconds on a ride. Additionally, the older age groups mainly consist of subscribers.