## Pedal through Austin Project

![Austin B-Cycle](README_IMAGES/bikeshare.jpg)

### Team Members:

Tinku Supakar, Ananya Yetigadda, Jo Anne Thanner & Gabriela Cantu 

### Introduction: 

>“Austin B-cycle is public bike share system that rolled in to Austin in December 2013. The system is owned by the City of Austin and operated by the local 501c3 non-profit Bike Share of Austin. Austin B-cycle immediately broke national records for check outs during SXSW—making it one of the most successful bike-sharing programs in the country. Currently there are 76 B-cycle stations around downtown Austin”- Austin B-Cycle 

### Project Description:

We are independently analyzing the bike sharing data from the Austin B-Cycle company within a 5 year span (2013-Present). The analysis seeks to draw trends related to the demand of the service.
 
* The first part of the analysis will look at the demand by station, membership, year, month, and hour.
* The second part will rank stations and membership.
* The last part will look at the unique and temporary Austin population peeks such as SXSW and ACL for all 5 years, and Uber Ban for (May 9, 2016 - May 29, 2017).
 
### Purpose: 

This analysis suggests a more efficient allocation of resources in order to meet peak demand times and locations. The implications of this analysis could also help the program determine the low demand times to schedule maintenance and restocking.

### Scope: 

* We only have the data for the Austin B-Cycle company.
* Data is only from December, 2013 through July, 2018.

### Data Set: 

* [Austin B-Cycle bicycle sharing program API](https://data.austintexas.gov/resource/cwi3-ckqi.json)

### Research Questions : 

1. Is there any variation in the bike utilization over 5 years?

2. What are the high demand hubs and times that Austin B-Cycle needs to meet?

3. What have been the different categorical membership types  and what is the utilization of the service by type of membership?

4. Is there a correlation between annual events and rides?

5. How long is a trip on an average and where do the trips usually start from? 

### Actions and Tasks: 

* Obtaining all the data from Austin B-Cycle Company
* Data Cleaning and Exploration
* Chart Plotting
* Writing Analysis

### Research Findings :
1. Is there any variation in bike utilization over 5 years?

* Bike utilization increased from 2013 to 2015 and then it reached a plateau. However, in the current year, 2018, demand has exploded since the offering of the free 18 month memberships to U.T. students. 

![Rides per Year](Images/Rides_per_Year.png)

2. What are the high demand hubs and times that Austin B-Cycle needs to meet?

* March and October are the top two months with the most bike rentals. 

![Rides per Month](Images/Rides_per_Month.png)

* 2:00pm to 5:00 pm are the busiest hours on any day of the week. 

![Busy Hours](Images/Busy_Hour.png)

* We noticed weekends are in high demand compared to weekdays, but Saturday has highest volume and can be determined as it is the most popular day of week.

![Busy Weekdays](Images/Busy_Week.png)

* We have included a heatmap by week day and hour that combines the previous findings. We can clearly see from this graphic that the weekends in the afternoon are the most popular times to ride with Austin B-Cycle. This may be the result of the visitor influx that comes to Austin during the weekends.

![Demand Heatmap](Images/Hours-day.png)

3. What have been the different categorical membership types and what is the utilization of the service by type of membership?

* Membership types keep changing every year because some memberships are social media promotions (like U.T. students and faculty) and subsequently they are phased out. For our analysis we have categorized the data by walk up, day, weekend, week, month, year, 3 year, and U.T. student memberships respectively. We found that the most popular membership type is walk up among all the categories. 

![Membership Types](Images/mem_type.png)

4. What are the unique and temporary situations that have affected the bike rides?

Events like SXSW and ACL affects ridership. March and October have the highest number of bike rentals due to these festivals. However SXSW is more popular than ACL for bike rides because of its Downtown location. 

![SXSW and ACL](Images/SXSW-ACL.png)

Total bike rides during Uber Ban were 206052. This number was higher than the yearly average bike rides value (165211). 

![Uber Ban](Images/Uberban.png)

Total bike rides during Uber Ban were higher except for 2018, which was affected by the U.T. free membership.

5. How long is a trip on an average and where do the trips usually start from? 

* The following graph displays the station count and takes the top six more popular stations. The most popular stations are located within or in very close proximity to the university.

![Popular Stations](Images/Pop_Station.png)

* Bike trips are usually on an average of 28 minutes. However, if we look at the data by membership type, the longest average trip duration is of 41 minutes for the walk up membership.

![Average Duaration Membership Type](Images/avg_duration_mem_type.png)


### Conclusions: 

* We found that bike usage increases consistently throughout the years and that March and October are the top two months with the most bike rentals. This is due to SXSW and ACL festivals.
* There is more usage of bikes on weekends compared to weekdays.
* Saturday has the most bicycle rentals and 2:00pm to 5:00 pm are the busiest hours on any day of the week. 
* The top station is 21st and Speedway.
* The most popular membership type is “walk up” with the longest average trip duration of 41 minutes.
* The 18 month U.T. pilot program for free student bike rentals started in 2018, and is very popular.
* Total bike rides during Uber Ban were higher except for 2018, which was affected by the U.T. students free bike rentals.

### Slideshow: 

* [Presentation View](https://docs.google.com/presentation/d/1fIk0yN7bH_pLIRUxPTkyxm9zOThLRluyKVivEPbjPdc/present?slide=id.p)

* [Google Slides](https://docs.google.com/presentation/d/1fIk0yN7bH_pLIRUxPTkyxm9zOThLRluyKVivEPbjPdc/edit?usp=sharing)
