## Bike sharing

## Overview of the statistical analysis:

The purpose of the analysis is look at NYC Citibike data and analyze it for trends on who is riding, when rides happen, and how long bike rides are to help make an informed business plan for starting a similar bike sharing program in Des Moines.

### Results:
[link to dashboard](https://public.tableau.com/shared/KSNH2ZY9F?:display_count=n&:origin=viz_share_link "link to dashboard")
#### WHO:
Gender Usage

![image](https://github.com/trosie3/bikesharing/blob/main/images/whogender.png)

Duration and Age correlation - suggests younger rides ride longer
![image](https://github.com/trosie3/bikesharing/blob/main/images/whoagetripduration.png)

#### WHEN:
Length of time bikes are out overall, and by gender
![image](https://github.com/trosie3/bikesharing/blob/main/images/lenghtrips.png)
![image](https://github.com/trosie3/bikesharing/blob/main/images/lenghttripsgender.png)

Trips per Hour each weekday overall, by gender, and by gender/usertype
![image](https://github.com/trosie3/bikesharing/blob/main/images/whenweekday.png)
![image](https://github.com/trosie3/bikesharing/blob/main/images/whenweekdaygender.png)
![image](https://github.com/trosie3/bikesharing/blob/main/images/whenweekdaygenderuser.png)

Overall Month of August Peak Hours Bikes out
![image](https://github.com/trosie3/bikesharing/blob/main/images/whenpeakhours.png)

#### WHERE/HOW:
Station Usage using End Station - suggests an area of high usage possibly correlated to population density in that area, increased tourism, etc.
![image](https://github.com/trosie3/bikesharing/blob/main/images/stationusage.png)
Key numbers - needed for gaging stations, bikes to suggest in a new city

![image](https://github.com/trosie3/bikesharing/blob/main/images/otherdata.png)

## Summary:
Who is riding? 
- More males, than females are riding. More annual subscribers, likely locals, than short-term subscribers, likely encompasses tourists. This means in a new city it may make sense to target locals over tourist first to get a steady customer base at the start of the bike sharing program. Data also suggests younger riders take longer trips in general, so it might also be wise to target a younger demographic at the beginning so you also aim create a customer base that takes longer bike trips on top of a more steady customer base.

How long bikes are checked out for all riders and genders, and what does the mean for bike sharing stations?
- Based on the data and the above images, most trips are under 30minutes, with the highest number of trips being around 5minutes. Even when broken down by gender this appears to hold true. This suggests that stations need to be close enough for short trips (given so many around 5min) but also enough stations to allow for a distance covered on bike from another station of 30minutes.
- Using the map of stations and looking at the amount of trips end at each station, you can get an idea of where ride density and thus station density needs to be the strongest. Finding a similar area in Des Moines to NYC would indicate a good place to start placing stations based on more rides of the overall total in NYC happneing in a specific part of the city. Looking at the total rides, total stations and total number of bikes in NYC may also help to plan with how many bikes are needed and which stations need more bikes.

How many trips are taken by the hour for each day of the week, for all riders and genders?
- Trips during the weekday appear to peak at 8am, and from 5-6pm. Trips during the weekend seem more abundant mid-day closest to 'lunch' between 11-1pm.
- Overall peak hours for the month support that. They also show the least number of rides are happening between 3-4am which suggests a good time to handle any maintenance so all bikes can be ready for the next day.

What days of the week a user might be more likely to check out a bike, by type of user and gender?
- Based on the data and the above images, for annual subscriber males/females Thursday and Friday appear to be the days with more rides occurring, followed by Monday and Tuesday, with Wednesday and the weekends the slowest days.
- Based on the data and the above images, for short-term subscribers Saturday/Sunday appear to be the days with the most rides, also it appears that Wednesday for this groups is the slowest day.
- This might suggest with both having fewer trips on Wednesday for all groups a good day for maintenance on bikes outside of the 3-4am hour.

### Limitations & Suggestions:
Heatmaps requested were probably not the best way to show case the data, perhaps changing the color scales would have made them clearer given they were the desired format. Also, only limited to one month and one year which makes it difficult to truly identify trends. Another limitation is not having the city population and population density by area within the city, there is likely a correlation on more rides occuring in more densily populated area, which would then be a key indicator on where to start placing stations in another town.

Suggestions for other charts:
If had more time these charts may help to make a more informed business decision:
- A chart using data on gender and user type to see if there is a difference for annual subscribers and short-term subscribers in gender. This may help in determining the marketing strategy to target tourists, as tourists are more likely to sign up for short-term over an annual subscription.
- Pull in more data from the Citibike website on other years, and/or data from other summer months in the 2019 to see how the overall summer looks. This extra data can better identify possible trends in peak times, peak days, gender etc. For example: creating a chart for trip duration by each summer month, or comparing August from 2020 to 2019 to 2018, may show a different trend in length of rides than the one from above shows on its own. 
