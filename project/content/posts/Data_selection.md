+++
title= "Data selection"
tags = [
    "Extra",
]
weight = 10
+++

Everything inside of the extra posts can also be found inside our [notebook](https://github.com/Kerzer/Eviction_project/blob/main/project/Final_Project.ipynb)

The main inspiration for this project came from the work concerning [crime in San Francisco](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry),
which was done in relation to [course 02806](https://kurser.dtu.dk/course/02806) about analysis and visualization of data. 
Based of the two initial projects done in the course one of the main features that stuck out was the use of [geojson](https://en.wikipedia.org/wiki/GeoJSON)
and [plotly](https://plotly.com/) to add overlays to maps. These tools allowed us to make strong visualizations which allows the user to explore
and understand the data at thier own pace.

Initially the search for data was based on something that had impact on people within cities,
along with being something that was possbile to find in a public data base. The
 [Eviction dataset](https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4)
fitted those criteria, along with the fact it is rather suble why you would be evicted, which could be explored
further with data analysis.


At a closer expection of the data set the following observations were made.
From 2017 to the present, there is a changing amount of evictions in New York. 
Over 19,000 tenants of apartments experienced an eviction from their homes in 2018. In particular,
during the period of COVID-19 in 2020, of the 50,106 evictions in New York since March 15th,
17,293 were filed in Bronx County, 13,553 were filed in Kings County, 9,428 were filed in New York County,
8,901 were filed in Queens County, and 931 were filed in Richmond County.

![boroughs_NYC]({{< baseurl >}}/boroughs_NYC.png)
[Source: Wikipedia](https://en.wikipedia.org/wiki/Boroughs_of_New_York_City)


As shown in the figure above, we can see that different borough has different GDP,
population, land area and density. 
Are these indices related to evictions that happened in different boroughs? 
Does other information such as latitude and longitude have a relationship with evictions?
What are the deeper causes of the phenomenon of eviction surge? These fascinating questions
are worthy of our in-depth exploration.

1. [**Data selection**](https://kerzer.github.io/posts/data_selection/)
2. [Genre](https://kerzer.github.io/posts/genre/)
3. [Discussion](https://kerzer.github.io/posts/discussion/)
4. [Work Distribution](https://kerzer.github.io/posts/work_dist/)