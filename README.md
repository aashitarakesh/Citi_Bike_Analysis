# Citi Bike Analysis :  2018 - 2020 (March - September)

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. The data from 2018 to 2020 (May - September) is analyzed  to examine the usage and profiles of customers and also determine impact of COVID-19 on the program if any.

Data Source: [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.
Tableau StoryBoard: [Link] (https://public.tableau.com/views/Citi_Bike_16217459942760/CitiBikeAnalysis2018-2020?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)




## Data Cleaning 

Before doing any visualizations, I  used Python and the Pandas library to clean the data. In a Jupyter Notebook, I concatenated monthly data files into one, and then trip duration was converted from seconds to minutes. Next, gender column was converted from numerical value to string and then exported the new merged csv to Tableau.


## Analysis


**Ridership has decreased during the initial onset of COVID in March 2020. However as the restrictions are lifted people are riding their bikes for longer times. This could be because it is now a preferred mode of transportation replacing the subway or a ride-share vehicle.

**The most popular start times are at 8 AM and 6 PM similar to the office rush hours.People are utilizing bikes to commute to and from work. The spike around 6 PM could also be attributed to students finishing classes and headed back.

**Ridership participation is higher in men across all three years. Covid caused a decline in ridership ,however women ridership has increased consistently over the years. Users who have the longest trip duration, when focusing on just age; were riders above 70 years.

**In terms of the distance and duration, most young users rode citi bikes for short distance, while the older people rode for longer distance and duration.Users rode for longer periods during  covid Males ride way more citi bikes than females and unknown gender.

**Grove St Path remains the most popular Starting and Ending Station by number of rides and most subscribers, brining in most revenue.The average  reported user age is between 37-40 years.
