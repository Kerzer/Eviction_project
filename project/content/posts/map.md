+++
title = "Evictions in New York City "
weight =2
tags =[
"Content",
"Main story",
]
+++

Being thrown out of your apartment is a drastic is life impacting event. A lot of factors leads in to
being evictied from your home, but what affects whether or not you are evicted? <br>

The goal of this website is to explore what  attributes are common when are evictions happend,
and exploring where in New York City evictions most commonly occur. This will be done by
breaking New York City into smaller sections, and in coorperating other elements such as
complaints about landlords to see if there is a correaltion.



## New York City 
To gain an overview of the servity of evictions in New York City the first thing taken into consideration is
the amount of evictions for the last few years. By looking at the graph below the main trend is that evictions
are becoming more uncommon in New York City.

![eviction_by_year]({{< baseurl >}}/eviction_by_year.png)
<sub><sup>If it is hard to read try opening it by right clicking or [open here](https://kerzer.github.io//eviction_by_year.png)</sup></sub>

**Måske lav det her om til en kurve**

Looking at the eviction count for the year 2020 it is drasticly lower than the previous years. The main reason for this is that 
evctions [were stopped by the goverment](https://ny.curbed.com/2020/3/16/21180842/coronavirus-new-york-state-eviction-moratorium)
because of [Covid-19](https://www.worldometers.info/coronavirus/country/us/) which struck New York City early on in the pandemic.
Because of the need to stop the spread, [isolation orders](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-provider-quarantine-precautions.pdf)
was issued by the state to avoid the spread running rampant. This led to a reduction in the number of evictions.

## Comparison of Boroughs and Council Districts
In order to gain a better understanding of what attributes correalate to being evicted the dataset is split up into smaller segements.
Two main appoarches are used here with splitting the dataset into 5 larger groups called [boroughs](https://en.wikipedia.org/wiki/Boroughs_of_New_York_City)
or into 51 smaller segements called [Council Districts](https://en.wikipedia.org/wiki/New_York_City_Council). <br>

The main thing achived by this split is the ability to compare each borough or council district to another.
Since New York is very different depending on where in the city you are the distinct attributes in both
council districts and boroughs are quite different and gives way to a lot of interesting analysis on the
data set.

![boroughs_NYC]({{< baseurl >}}/boroughs_NYC.png)
<sub><sup>[Source: Wikipedia](https://en.wikipedia.org/wiki/Boroughs_of_New_York_City)</sup></sub>

Looking at this table it is very clear that there are sharp contrasts depending on what attributes are inspected.
By looking at The Bronx and Mahatten are similar in population number, but vastly different in GDP and
population density.

### Map of evictions
The strongest benefit of these splits is however also the ability to create a visualization that shows
where in New York city the evictions take place. By also using a demograpic dataset further information can
also be gauged from each district.

{{< load-plotly >}}
{{< plotly json="/map.json" height="750px">}}
<sub><sup>hover to highlight - open a different tab to keep this map up as it is refered to throughout the page.</sup></sub>

By comparing what council districts have high eviction count with the boroughs it is clear that they are the most common in The Bronx and Brooklyn area. <br>

It is also noticeable that it is alot more important to look at the council district than at which borough a part of the city is in as the volatility is quite large
between council districts in some of the boroughs. The boroughs are however still good to visualize general segments of the city and are maintained and used throughout
for ease of understanding.

![EV]({{< baseurl >}}/evictions.png)
<sub><sup>If it is hard to read try opening it by right clicking or [open here](https://kerzer.github.io//evictions.png)</sup></sub>

As it is now clear where the evictions happend in New York City it becomes important to explore **why** they happen.

### Demographics
As New York City contains a large variety of people coming for all over the world, would be interesting to see whether evictions are
more common within certain elements of the population. In the map it was also shown the majority national background in each district.


#### Manhatten and The Bronx
An comprisons can be made between Manhatten and The Bronx with compareable population sizes.
However by comparing the number of [evictions](https://kerzer.github.io//evictions.png) they are at opposite 
ends of number of evictions. Here the demograpic differences are taken into account to see where these two boroughs differ from each other.

![Stats_GT]({{< baseurl >}}/stats_GT.png)
<sub><sup>[open here](https://kerzer.github.io//stats_GT.png)</sup></sub>

To mention a few world renowned attractions and institutions found on Manhatten [Wall Street](https://www.google.com/maps/place/Wall+St,+New+York,+NY,+USA/@40.720791,-73.9996339,14.25z/data=!4m5!3m4!1s0x89c25a165bedccab:0x2cb2ddf003b5ae01!8m2!3d40.7060361!4d-74.0088256),
[Times Square](https://www.google.com/maps/place/Times+Square/@40.7574645,-73.9869094,16.5z/data=!4m5!3m4!1s0x89c25855c6480299:0x55194ec5a1ae072e!8m2!3d40.7579747!4d-73.9855426),
and [Boardway](https://www.broadway.com/) are the three first of a [long list](https://www.nyctourist.com/nyc-most-popular-attractions-map) of places in Manhatten which is commonly known even
to most people in Denmark. Manhatten is clearly **the** place to be, which also explains why eviction rates are low,
as this is a place of high barrier of entry and people are less like to enter without already being part of a more
wealthy segement of the society. 




The largest section of people in Manhatten is white people while The Bronx is mainly
Hespanic origin. This paints the picture that it is mostly an immigrants and poor section that lives in bronx

#### The Bronx


#### Staten Island

The interesting addtion of Staten Island to New York seem like an outlier. The density and wealth is the lowest for any
of the boroughs in New York City, however the number of evictions is still very low. The geograpical location of Staten
Island plays in here, with the distance to what is considered New York downtown. 

![Renters]({{< baseurl >}}/Renters.png)
<sub><sup>[open here](https://kerzer.github.io//Renters.png)</sup></sub>

Staten Island eviction count is apporaching a
more how a rural community experiences evictions, where the turnover of homes is lower. The willingness to remove homeowners is then lower as
it is harder to replace them than in the other boroughs which relates to a different ecosystem. This is also supported by
lookinig at how many renters are present in Staten Island compared to all other boroughs.

### Complaints In Council districts



## Conclusion




