# Ford GoBike System Dateset

## Dataset <hr>
- This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Francisco and San Jose. Once expansion is complete, Ford GoBike will grow to 7,000 bikes across San Francisco, the East Bay and San Jose.

## Data Wrangling process
- fixed features with incorrect dtypes like start_time, end_time, user_type and etc.
- create new columns like of month, hour, days etc
- add new column as 'member_age' from calculating 'member_birth_age'
- drop nan values from 'member_age' and 'member_gender'
- drop all members of 'member_age'>81
- cast 'start_time_days' and 'start_time_month' to category types

## Summary Insights
User type for the analysis revealed different behavior usage between customers and subscribers. The information proposes that customers are casual riders such as tourists, or students on a school vacation or holiday. This is precise when calculating in that Customer usage increases on the weekends. In contrast, the data suggests Subscribers are daily commuters or full time students who use the system during weekdays, better weather, and mostly for shorter distances. They mainly rent bikes before and after a typical work or school day (8-9am and 5-6pm).

User Type

subscribers are:

- more likey to take short trips
- more likey to take short duration trips

customers are:

- more likey to take long length trips
- more likey to take long duration trips

As from previous and now Subscribers ride much shorter/quicker excursions contrasted customers on each day of the week . Both user types had an obvious increase of trip duration on Saturdays and Sundays (or weekends), especially casual customers. Subscriber use was more effective than clients by and large and kept up an entirely reliable normal span Monday through Friday.

## Key Insights

- From the plot Subscribers that are aged in group between 26-35 years old are the most common age group to use the bike sharing system. The 26-35 years old also tends lead the spike which occurs across all age groups in October As these age are the working age. Subscribers who fall in the 36-45 year old age group are the next most common age group to use the bike sharing system, and follow a similar trend at the 26-35 year olds.

- Glancing back at plots, jumping for other sexual orientation at a more established is an astonishment. Furthermore, for supporters the outing length is higher than client for more established age is a shock
