# PyBer_Analysis
For this challenge, I was responsible for creating a weekly PyBer ride fare analysis using Jupyter Notebook and Matplotlib to transform data from two data files and prepare a multiple-line chart showing these results to provide insights about the pattern between the types of city and the fare details. The initial part of the challenge was to generate a dataframe that detailed the city types and their total rides, drivers, fares, and averages of these. Once completed, I generated the line chart to visualize the relationship between the city type and the weekly total fares.
## Results
From the dataframe below, we can see that there is a pattern between how many drivers there are in a city type and the total number of rides for that type, which directly affects the total number of drivers, total fare, and the averages of each. We can see that in a rural city the number of drivers, rides, and fares are the lowest of the three but the average fares per ride and per driver increases. This is most likely due to the limited availability of drivers in a rural city compared to a much larger amount of drivers in an urban city where the fare averages decrease significantly. It could be infered that due to the longer distances of traveling from a rural city, these fare averages increase but more data would be needed to confirm this hypothesis. 

![PyBer_data_df](https://user-images.githubusercontent.com/88118759/135777988-8b0fcc48-6e6f-435b-a80d-02f0e80aac6a.PNG)

From the multiple-line chart, we can see how all three graphs follow a similar trend through the months graphed, with the exception of march where no trend can really be reported. One noticeable difference is that for suburban cities there is a steep decline in fares at the end of February, but also a larger increase in fares in April as opposed to the other two charts.
![PyBer_fare_summary](https://user-images.githubusercontent.com/88118759/135778148-302e969b-a2cc-47b1-b4d2-98db73484e61.png)

## Summary
Based on the results of the analysis, there are three recommendations I would make to the CEO to help address the disparities seen:
- There are clear trends between the total drivers and the total fares and rides where the less drivers there is the less rides are taken, which means less profits in the rural areas with limited drivers. It is advisable to provide more drivers to these areas to increase the total rides, which in turn will also lower the averages fares per ride and driver.
- I would recommend looking into what causes the weekly fare decline at the end of February and try to mitigate that situation.
- Continuing from the second recommendation, it would also be advisable to investigate the increase in fares during the month of April in suburban areas to try and provide resources to replicate that trend.
