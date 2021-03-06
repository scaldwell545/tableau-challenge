# CitiBike Tableau Dashboard

### View on Tableau Public
https://public.tableau.com/app/profile/sam.caldwell6712/viz/CitiBike-Analysis_16323488813960/CitiBikeAnalysis

### Analysis

1. How does CitiBike trip data change over the dataset?
	- What are the peak hours in which bikes are used during summer and winter months?
	- Which bikes are used the most? And in which months?

2. How do demographics affect trip duration?
	- How does trip duration change between factors such as:
		-age?
		-gender?
		-subscriber vs. one-time customer?

The first slide of my Tableau story attemps to illustrate some phenomena regarding the first question.

The plot placing CitiBike ID vs Cummulative Ride Duration (Days) illustrates that some bikes recieve far more ride
time than others. Over the course of 2020, a handful of bikes recieved almost 40 cummulative days of ride time, while 
the vast majority of bikes recieved less than a day. The minority of bikes with over 10 days of ride time would, 
therefore, almost definitely require more maintenance than others over the course of the year.

The next two plots depict the most popular ride times grouped by summer and winter months. Summer months correspond with 
April, May, June, July, August, and September while winter months correspond with January, February, March, October, 
November, and December. A noticable trend is that the number of rides at 8 am in the winter months is significantly higher
than in the summer- the only such point with that property. It might be surmised that more people would rely on CitiBike
for their morning commute in the winter as more people would resort to vehicles during cold whether- causing congestion
and delays. However, since this  dataset occurs during the COVID-19 pandemic, this might be attributed to the stay-at-home
order put in place during the summer months of 2020. This would mean more people would be working from home and therefore less
people would ride CitiBike for their morning commute.

The second slide of my Tableau story deals with phenomena regarding demographics.

The bar plot placing gender vs. average trip durtion indicated that the data is heavily skewed as the median ride time per gender is
significantly smaller than the average. This isn't too much of a surprise as one would assume that most people utilizing the bike 
service use it out of convinence over short distances rather than a primary method of transportation across the entire city. 
This may be supported by the sub-trend in one-time customers vs. service subscribers- the median and average values for these 
demographics are small yet much closer to each other, indicating that this is a trend over most subscribers and not among a select 
few skewing the data. The plot placing year of birth vs cummulative ride time suggests that most of the riders are between 27 and 37
years of age. These age groups, however, do not use the service over longer distances compared to some others- younger riders generally 
have an average trip duration that is two times higher than most other age groups in the dataset.

Next, the third slide of my Tableau Story is the map portion of the assignment. I chose to attemp the interactive map that depicts 
each station's popularity over time (month). Zip code, city, and street overlays are placed on the map as well for handy reference.
Each point on the map is a particular CitiBike station, where the relative size and color depict the number of rides involving the 
station (either departure or arrival station). Also for reference I included a truncated timeline for the local government's emergnecy
response to the COVID-19 pandemic such as closures and opening sequences. The map indicates that there are some stations that receive a 
consistently high number of interactions, such as the Grove Street and Newport Parkway stations. The map also clearly depicts the affects 
of city closures during the pandemic on the CitiBike service as volumes of rides per station plummet during the city lockdowns. Similarly, 
winter months clearly have a lower volume of rides (also demonstrated in the winter ride count per hour graph on the first slide.)

