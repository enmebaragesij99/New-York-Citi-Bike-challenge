# New-York-Citi-Bike-challenge

This is my Module 18-New York Citi Bike challenge, which consists of one CSV file and a Tableau Public workbook. The CSV file is the dataset used to create all the visualizations 
in the Tableau Public workbook.

## Contents

- 201501-citibike-tripdata(CSV file)

-  (link to Tableau Public Workbook)

## About

The dataset I used was solely from the month of January 2015 of the New York Citi Bike data to give a snap shot of trends in the most frequented bike stations(start and end), an insight in 
the most popular type of users and average trip durations based on the type of user and the location of the bike station.


## Analysis

### Top 10 most frequented start and end stations (DB-Top 10 end and start stations)

The most frequented start and end stations for users were practically identical, therefore, demonstrating no significant difference between where the user would start or end their trip. 
First and foremost, the top 10 most frequented bike stations were all situated within Manhattan neighbourhoods. This data leads me to beleive that
these frequented bike stations identified possibly could be one of the larger ones in New York Cirty and also situated in a very busy area of New York
where their are a lot of attractions wheter its for work or recreation, furthermore, the streets around those bike stations could be very bike friendly.

### User types(DB-Types of users)

The most significant difference between citi bike users was that majority of users were Subscribers(Annual members,98%) and the remainder were customers(24-hour pass or 3-day pass user,2%).
The next most noticeable difference between users was that majority of them were male(~79.8%)obviously followed by females (~18.2%) and there was also a very small portion 
of users who did not specify their gender at all (~2%).Finally,in regards to the age of the users the age bracket with the most amount of users was between the ages of 26-35(95,712), 
gradually declining with age;36-45(73,948),46-55(57,351),56-65(26,471).Followed by the 16-25 (21,550) which could be due to a possible age restriction on the New York Citi Bike program,
which could have impacted the age group in terms of users. Age group outliers were also incured due to possible users falsifying their age(e.g. age group of 106-115 recorded 106 users).

In conclusion, it seems typical users were males between the ages of 26-35 who would rather commit to the program over a long period of time, rather than a one off. The main factor that could be 
driving these users is regular physical exercise through the program.

### User types and average trip duration(DB-avg trip duration vs user types and STORY-avg. trip duration)

In terms of the user type; customer or subscriber, customers had a significantly longer average trip duration (~1,589 seconds) compared to subscribers(~636 seconds).This could be due to the customers 
who are less frequent users travelling longer distances due to unforseen circumstances and subscribers who are more frequent users travelling shorter distances, such as routine daily trips from home to work.
Based on gender their is relatively no difference between avergae trip duration between males (~623 seconds) and females (~692 seconds). The Unknown gender on the other hand had the longest average trip 
duration by far(~1,577 seconds) in comparison and the possible reason here seems to be that the users are one off users not regestering their gender and travelling longer distances. 
Finally, in regards to age group the age group with the longest average trip duration is 96-105(1430 seconds), which is obvioulsy a signiifcant outlier based on age, therefore,should be disregarded 
in conjunction with average trip duration.

In short, users who less frequenlty use the bike citi program have longer average trip durations which could be due to a multitude of reasons, whether its
a tourist riding a bike around to see the city and its attractions or its someone who needs to get somewhere when all other avenues fail. Furthermore,
the more frequent users have the lower average trip duration which could possibly be due to them using it for more routine shorter trips.


### Top 10 stations with the longest average trip duration(STORY-avg. trip duration)

The conclusion can be made that most of the top 10 stations with the longest average trip duration are situated outside of manhattan (239, 259, 271, 353, 499), which makes a lot of sense
seeing as users would be either travelling to other neighbourhoods farther away from their own  or to manhattan itself which is the heart and soul of New York City and has everything like
a one stop shop.








