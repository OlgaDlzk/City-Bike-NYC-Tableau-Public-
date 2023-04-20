# City-Bike-NYC-Tableau-Public

<h3> 
Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

![1200px-Citi_Bike_logo svg](https://user-images.githubusercontent.com/74025870/233479551-5d84aec1-e6f0-4692-9b13-da57a8645494.png)


<h4>
However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so the job is to build a set of data reports to provide the answers.

<h3>Data Gathering</h3>
Data was aquired on the project officila website: https://citibikenyc.com/system-data. We analyzed data for the last 15 months from January, 2022 to March, 2023. 

<h3>Data Transforming</h3>
There are 15 datasets in total, one for each month. Sample size for analysis contain randomly selected 25% of each datase.

<h3>Our analysis contained:</h3>

1. Riders type of participation (member/casual) through the 2022/2023 years, broke down to all the quartes. We looked closely to Q1 2022 vs Q1 2023 to determine the changed made within the last year. We see a significant increase in members utilization of the service 862,165 vs 1,266,461 (~68% increase). We also determioed that the busiest quarter in 2022 was the 3d quarter with a 29,29% of rides. 

![Dashboard Memberships by Years and Quarters](https://user-images.githubusercontent.com/74025870/233500220-26f4991f-bae1-412d-a5c1-1933d76978a1.png)

2. Classic bikes are used the most by members and casual riders. The top-10 start and end stations remain the same with a few differences in order for each category. 

![Dashboard user type and top 10s](https://user-images.githubusercontent.com/74025870/233482230-746ff977-22bc-450d-87a1-3f61467a60ae.png)

3. Organizing the top-10 byt the members usage to determine which stations with >25,000 rides are the most popular among members. 

![Dashboard top 10 by member count](https://user-images.githubusercontent.com/74025870/233482594-c0f12b1a-fc00-42d1-a5ba-915a1a2e0813.png)

4. Interactive Maps. Choose a month/year period to see the usage (the darker color indicates higher station utilization) of each station. The map has zip codes as well. As we suspected the busiest stations are located within the following zip codes: 10001, 10011, 10010, 10003, 10002, 10012, 100282, 100242.

![Dashboard Maps with pages for month_year](https://user-images.githubusercontent.com/74025870/233483520-fb56c715-f486-4638-b8a1-1f29a111afae.png)

5. Quarter usage of a rideable type as well as weekly service engagement through the selected time period. We observe that classic bike usage peaks in the 3d quarter, specificaly in August, however, electric bike peaks somewhere in the end of June-beginning of July. 
We also observe days with more than 30,000 rides mainly through the summer till the beginning of November. 

![Dashboard Engagement by months and days (1)](https://user-images.githubusercontent.com/74025870/233500142-8b741387-380f-428b-bfb0-84e3ecedfced.png)

6. Weekly Change of service participation. The interesting thing uncovered on this particular slide is the fact that the peak participation in August is attributed to increase of usage during the weekdays (Tuesday, Wednesday, Thursday, Friday) and not on the weekends. 

![by weekday with difference](https://user-images.githubusercontent.com/74025870/233499909-57fd179a-3b19-43d1-bc26-30df9e7b2ae4.png)






