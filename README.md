# Analysis and Visualisations of Ford GoBike System in 2018


## Dataset

The data consist of approximately 1,85M bike rides from FY2018. The attributes include the trip start/end time, start/end station, duration in seconds as well as additional information such as user type, gender, and birth date. 155K data points were removed from the analysis due to inconsistencies in the birth date, which in some cases was dated prior 1900. The data can be found [here](https://s3.amazonaws.com/fordgobike-data/index.html)


## Summary of Findings

In the exploration, I found that there are two types of clients using the system: subscribers who are mainly daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and, occasionally around the lunch time, and customers, usually tourists or occasional riders who use the system mainly on weekends to explore the Bay Area. The bike share system was used more often around summertime (May-October) with a clear drop from January to March, most probably due to the weather condition. Moreover, I have checked if there are some differences in trends for genders. In most cases the trend for males/females was the same, except of the fact that females tend to have slightly longer trips and surprisingly, for casual users there are quite a lot of females using the system between January and March in comparison to males (the ratio is much smaller than for the rest of the year).


## Key Insights for Presentation

* Types of users using Ford GoBike service which includes, subscribers(88%) and customers(12%). Subscribers seem to be using the service for daily commute whereas casual customers are using for exploring the area mainly during the weekend
* Hourly usage during a usual weekday, The heatmap depicts a clear distinction between usage patterns showing the Subscriber usage mainly during the morning and evening hours whereas customer usage is much more evenly spread out throughout the day.
* The histogram shows a much more shorter travel time for subscribers on an average whereas the customer usage might be over a long distance in some instances, showing subscribers opting for BikeGo service for short distances which is a good thing.

## Resources

* https://www.programiz.com/python-programming/datetime

*https://seaborn.pydata.org/index.html

*https://python-graph-gallery.com/all-charts/
