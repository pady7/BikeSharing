# BikeSharing

### _Created a story and multiple dashboards to analyze and visualize citi bikes data using Tableau and Python_

## Overview
---
This project consisted on creating a pitch for a citi bike (bikesharing) business proposal for angel investors looking to seed fund. The goal was to look at citi bike data in New York City on the month of august to look how this bikesharing business operates in its prime during summer. After analyzing the data and cleaning it up a bit, I then created visualizations to display the trends and opportunities it would have in other cities.

### Software

* Python
* Pandas Library
* Tableau Public

### Results
[Tablaeu Story](https://public.tableau.com/app/profile/padmanaban.nagaraj/viz/TablaueAssignmentStory/Story1?publish=yes)

This presentation was based on New York City but could be applied, with the necessary attention, to other cities in the World.

![Upload1](https://user-images.githubusercontent.com/93692327/156870726-a0429b74-ef46-436b-bdfc-863ec848946a.png)

During august, the most profitable month of the year, the most popular hours in which people used the bikes were 5 and 6 pm during the afternoon and 8 am during the morning. This uncovers the trend that people usually use it to mobilize to and from their jobs as the peak hours are before and after work time.

![upload2](https://user-images.githubusercontent.com/93692327/156870752-fe94573f-c54a-4cff-a157-e34259dc858a.png)

Moreover, this heatmap supports this theory as it displays how the most heated and popular times are 8am and 5-6 pm during workdays. It provides additional information such as that thursday is the most popular day of the week, and that saturday and sundays' afternoons are also very popular for bikesharing.

![upload3](https://user-images.githubusercontent.com/93692327/156870768-86e84024-4fd7-4186-a607-78245a425dd5.png)

As it can be seen in the User Trips Dashboard, almost 80% of the users are subscribers, meanwhile the others are just customers who sometimes use the bikes. This means that user retention is pretty high and wherever the bikesharing business is created we should strive to give incentives for customers to become subscribers. More specifically, male subscribers are the most popular users followed by female subscribers. There are also many customers who happen to avoid the gender selection, so they appear as unknown gender. We should try to engage more customers as a whole.

![upload4](https://user-images.githubusercontent.com/93692327/156870796-2e752b68-bd3d-48cd-9de0-8d7982c0a8b6.png)

In this worksheet, we can see the trip duration by gender. As it can be seen, all genders usually use the bikes for 5 minutes approximately. After 5 minutes, the trip durations start to slope down. Almost nobody uses the bikes after 45 minutes, where the slope starts to decline by a lot.

![upload5](https://user-images.githubusercontent.com/93692327/156870899-acfe4567-1240-4463-801d-86d2762d1880.png)

Here we can see the gender breakdown, which shows that the majority of customers are male with approximately 65% market share, then women with 25%, and finally unknown gender with 10%. They all happen to have the same heatmap which shows how they have the same behavior on using bikes at the same times (8am and 5-6pm for the most part).

![upload6](https://user-images.githubusercontent.com/93692327/156870924-b0e5b9e8-08e5-41e5-800a-ef8e30cefe53.png)

## Summary
---
To further analyze the citi bike business proposition, we created one more visualization in which we observed rides by age. To calculate age I created a Tableau calculated field in which I used the date of birth to get the age. As it can be seen, users have to be 18 years old in order to be able to use the bikes. Also, there is a outlier at 52 years old for 'unknown' gender with over 200,000 rides, which we would have to further investigate because it might be affecting our findings.

![upload7](https://user-images.githubusercontent.com/93692327/156870962-517bb210-0d80-4d69-bbfb-45949cf705a8.png)
