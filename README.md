# tableau-citi-bike
# Tableau Dashboard
Link: [https://public.tableau.com/views/Module18-CitiBike_17152263523050/Story1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link](https://public.tableau.com/shared/JZTZSG6XM?:display_count=n&:origin=viz_share_link)

## Analysis


![Screenshot 2024-06-03 at 1 23 30 PM](https://github.com/ndchian/tableau-citi-bike/assets/153045237/29adb41d-46d0-4060-9869-d60c842fdfa0)

The map was configured so that the size of the station markers corresponds with number of rides that originated from that station. 

![Screenshot 2024-06-03 at 1 25 42 PM](https://github.com/ndchian/tableau-citi-bike/assets/153045237/839da3df-28f1-4c71-bab8-adcf083d36f5)

To be able to drill in a little deeper, the second dashboard offers a look at the top 10 most popular starting and end stations for bike rides. The screenshot shows the information for starting stations and as you explore the dashboard, you will notice that the top 10 ending stations are the same. There is a slight variation in the top 10 order, but this indicates many riders choose to begin their biking expeditions in relatively the same place they choose to end them. As you hover over any of the station markers, you are able to see the number of rides that start or end at that station, depending on which infographic you are interacting with.

<img width="994" alt="Screenshot 2024-05-08 at 11 52 06 PM" src="https://github.com/ndchian/tableau-citi-bike/assets/153045237/20025ca4-935a-4ecd-a1f4-f05e8f6804b5">

Next, we examine rental trends by time of day and rental duration. During the typical work week, Monday through Friday, there are higher concentrations of rentals during the typical rush hour periods 7AM - 9AM and 4PM - 7PM. This makes sense as people try to avoid traffic by using other methods of public transportation (i.e. bus or subway) and given the infrastructure of living in New York City, it's not always plausible to drive. On weekends, the higher rental periods are fairly evenly distributed from approximately 11AM - 6PM. Regardless of weekday, the hours of 2AM - 4AM seem to be the least busy, though even at 3AM there are still over 3,000 rentals that start at that hour. The hours are in military time, so please be mindful of that as you make observations. 

<img width="981" alt="Screenshot 2024-05-08 at 11 52 17 PM" src="https://github.com/ndchian/tableau-citi-bike/assets/153045237/ff1e5f8a-7e3d-40e4-a8e6-4e53e2356f7c">

When we look at the typical rental duration, renting and returning within the same hour is the most popular time frame of rental by far, followed by rentals that last into the next hour. Evening 1 hour rentals that start at either 5PM or 6PM are the most popular. This supports the theory that the bulk of weekday riders rent during the rush hour periods and rent for the duration that it takes to get home, rather than going for long leisurely rides.

<img width="971" alt="Screenshot 2024-05-08 at 11 52 27 PM" src="https://github.com/ndchian/tableau-citi-bike/assets/153045237/3facbb5b-4d72-4a3e-9f53-7e7a377eb1ee">

As we review membership numbers for the summer, membership sharply increases with the onset of summer, the week after Memorial Day. It remains fairly consistent and increasing as summer continues before dropping off as we approach Labor Day, typically marking the end of summer. The one week that is a significant decline is the week of the 4th of July, which coincides with many folks taking vacations and likely leaving the city.

<img width="558" alt="Screenshot 2024-05-08 at 11 52 39 PM" src="https://github.com/ndchian/tableau-citi-bike/assets/153045237/22d3d16f-b239-4f6e-8b58-9ed6520fd9ff">

When looking at member vs casual rider bike type preferences, there is a clear winner of the classic bike regardless of month. Electric bike numbers actually decline as time progresses through the summer. 

### Data Sources
The months of June, July, and August 2023 were pulled from this data page: https://s3.amazonaws.com/tripdata/index.html. They were joined in a union to be able to analyze bike rental activity as the summer progressed.
