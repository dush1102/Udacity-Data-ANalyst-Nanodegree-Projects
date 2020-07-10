# Customers' behavior analysis of [Ford GoBike System](https://www.fordgobike.com/)

<span>Dushyant Bhatia</span>
<br>July 2020

## Dataset

The dataset chosen for analysis is suggested by Udacity. The data consist of approximately 24M bike rides datapoints from 2018-2019. Few major attributes used for the analysis are: member_gender, member_birth_year, duration in seconds and user type, start station name and start time of the ride (in day, month, year). Link for the data: [here](https://s3.amazonaws.com/fordgobike-data/index.html), with feature documentation available [here](https://www.fordgobike.com/system-data).

## Summary of Findings

### Summary and Key Insights

* Duration of majority of the rides lie between 200 - 700 seconds range (4-11 minutes)
* Significant increase in the number of rides in the first 3 months of year 2019 as compared to 2018
* Overall average of rides is greater in months from May to Oct, this might be because of pleasant weather
* For weekdays, number of rides has a bimodal distribution among hours, with hours at 8 A.M. and 5 P.M.
* For weekends, number of rides are normally distributed among hours with peak hour around 2 P.M.
* `Subsribers` generally have shorter rides than `customers` with median of duration around 500 secs
* `Customers` have median of ride duration around 800 secs
* Customers have `never` shared a ride
* Subscribers have a constant number of shared rides on weekdays, a little drop on weekends


## Files Included

* ford_bike_exploration.ipynb: In this file all the exploration is done on the data to be followed by explanation
* ford_bike_slide_deck.ipynb: In this file the explanatory analysis is performed on the dataset
* ford_bike_slide_deck.slides.html: In this file the slides are created out of the explanatory analysis
* ford_bike_exploration.html: The exploration Jupyter notebook is converted to html
* output_toggle.tpl: to toggle between the code and plot in the slide file
