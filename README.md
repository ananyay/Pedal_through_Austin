## Pedaling through Austin Project

![png](README_IMAGES/bikeshare.png)

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

1. Is there any variation in the bike utilization over 5 years?

* Bike usages have increased consistenly throughout the years. However in the year 2018, the demand has exploded with the new U.T student free 18 month memberships.

![png](README_IMAGES/Rides_per_Year.png)


2. What are the high demand hubs and times that Austin B-Cycle needs to meet?

* March and October are the top two months with the most bike rentals.
 ![png](README_IMAGES/Rides_per_Month.png)

* 2:00pm to 5:00 pm are the busiest hours on any day of the week.
![png](README_IMAGES/Busy_Hour.png)

* During Friday and weekends the bike usage increases between 12:00pm to 5:00pm . On weekdays there is a  spike in bike usage  during the hours 8:00am , 12:00pm and 5:00pm
![png](README_IMAGES/Hours-day.png)

* There is more usage of bikes on weekends compared to weekdays. Saturday has the highest bicycle rentals.
![png](README_IMAGES/Busy_Week.png)


3. What have been the different categorical membership types  and what is the utilization of the service by type of membership?

*  Membership types keeps on changing every year because some memberships are social media promotions (like U.T. students and faculty) and few are deleted. For our analysis we have categorized the data by walk up, day, weekend, week, month, year, 3 year, and U.T. student memberships respectively. We found that the most popular membership type is walk up among all the categories.
![png](README_IMAGES/Pop_Membership.png)

4.  How long is a bike trip on an average?

* Bike trips are usually on an average of 28 minutes. The longest average trip duration is of 41 minutes for the walk ups membership type.
![png](README_IMAGES/avg_duration_mem_type.png)


5. Is there a correlation between annual events and rides?

* Events like SXSW and ACL affects ridership. March and October have the highest number of bike rentals due to these festivals. However SXSW is more popular than ACL for bike rides because of its Downtown location.
![png](README_IMAGES/SXSW-ACL.png)

6. What effect did the Uber Ban have on the Austin Bike rides?

* Total bike rides during Uber Ban were 206052. This number was higher than the yearly average bike rides value (165211).
![png](README_IMAGES/Uberban.png)


### Conclusions: 

* We found that bike usage increases consistently throughout the years and that March and October are the top two months with the most bike rentals. This is due to SXSW and ACL festivals.
* There is more usage of bikes on weekends compared to weekdays.
* Saturday has the most bicycle rentals and 2:00pm to 5:00 pm are the busiest hours on any day of the week. 
* The top station is 21st and Speedway.
* The most popular membership type is “walk up” with the longest average trip duration of 41 minutes.
* The 18 month U.T. pilot program for free student bike rentals started in 2018, and is very popular.
* Total bike rides during Uber Ban were higher except for 2018, which was affected by the U.T. students free bike rentals.
