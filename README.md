# PyBer Rides by City Type Analysis

## Overview
Previously, we completed a a data analysis for a ride-sharing company called PyBer.  We analyzed rideshare data by city size type (Rural, Suburban, Urban). We first created bubble scatter plots showing the relationship between the amount of fare and the number of rides and bubble size reflecting the number of drivers per city. We also performed a statistical analysis of the data, creating box and whisker plots to detect outliers in the data. Lastly, we created pie charts that show at a glance how the amount of total fares, number of rides, and number of drivers break out by city type. Now we will continue our analysis by creating a multiple-line graph showing a snapshot of the total fares by city type during the 4 month window of January, 2019 through April, 2019.

## Results

### Differences in ride-sharing data among different city types

Generally, the more urban the city type is, the larger the share of the fares. From our previous analysis, we also know that the more urban the area, the more rides and the more drivers. In our multi-line graph of fares over the four month period from January to April, 2019, a very clear pattern emerges which is consistent with the previous analysis. Urban cities have the highest share of fares, suburban cities the second most, and rural cities the smallest share of the fares. Below are the following: a snippet of the DataFrame of fares by city type,  the line graph, and the previous pie charts.

![DataFrame of graph data](https://github.com/mgsrichard/PyBer_Analysis/blob/main/analysis/DataFrame%20of%20fares%20by%20City%20Type.png)
![multi- line graph](https://github.com/mgsrichard/PyBer_Analysis/blob/main/analysis/Pyber_Fare_Summary.png)
![pie chart](https://github.com/mgsrichard/PyBer_Analysis/blob/main/analysis/Fig5.png)
![pie chart](https://github.com/mgsrichard/PyBer_Analysis/blob/main/analysis/Fig6.png)
![pie chart](https://github.com/mgsrichard/PyBer_Analysis/blob/main/analysis/Fig7.png)

The only caveat is that the highest average fares are in the more rural areas.  This is probably due to the fact that rural trips would likely be longer. The higher amount of fare, however, does not overcome the huge volume disparity between rural and urban cities.  It does, however, make rural cities a great place to expand the business. The bubble chart from our previous analysis demonstrates the high fares rural cities experience, but the low ride numbers and small bubbles again demonstrate the low percentage of the business that rural rides represent.

![Bubble chart](https://github.com/mgsrichard/PyBer_Analysis/blob/main/analysis/Fig1.png)

## Summary - Recommendations to Address Disparity Between Urban and Rural Business Share and Expand Rural Business

The dominance of urban cities in the data points to an obvious starting point for future business planning: generate more rides, recruit more drivers, and build the business in rural and suburban cities.  Rural populations and households are much more likely to be car owners than urban populations because they have much less access to affordable and reliable public transit.  This cuts two ways: there is a large pool of potential drivers out there, and secondly, the people who do not have access to a car or the abilty to drive can be very homebound (i.e. stuck and in need of a PyBer ride). I propose the following strategies to target small cities by considering the unique needs of rural areas.

 - **Target Small Colleges**:  Many small towns are college towns, and as such they have a sizable population of young adults with no cars. You could build partnerships with the administrations and pilot many programs, such as:
    - Offering parents of incoming and returning students the opportunity to create a pre-paid account for their student to use.  There are many times in a young student's life when they may find themselves in some awkward or potentially unsafe situation, and a pre-paid account like this would provide them with the ability to get a safe ride without having to consider what their parents would think about the situation they are in. 
    - Partnering with Student life to provide occasional outings to larger towns.  Drivers with a van or larger SUV could get several fares at once, making it worth their while, and students would get a small trip that they may have made anyway but in a safer way.
    - Working with those who serve international and out of state students to provide transport to and from the airport or train station to the college at the beginning and end of semesters and for other breaks

  - **Reach out to Churches**: Rural areas have many churches, and churches often have aging populations.  Older people are more likely to not be able to drive, or be reluctant to drive at night for events or other meetings like choir practice.  You could offer a subscription service for these people to buy rides to and from church.  In the best case, the drivers are members of the same congregation, so they would be arriving and leaving at the same times.  The church would have an interest in keeping these people in church for both social and relational reasons, but also because people who stop attending church will frequently stop giving also.

 - **Partner with Medical Providers and Hospitals**:  Aging patients in rural areas often have a hard time getting to medical appointments if they are no longer drivers.  Available transport options for them are often exorbitant.  Partner with these local providers, providing an option at the time the appointment is made to learn about the availability of PyBer's drivers.
 
What all of these ideas have in common is bringing in new people as riders and drivers. Once someone has had a good experience in either role it becomes a concrete option for them in the future.  Introducing people to the rideshare model opens the way for more expansion. 
 
