# Surfs up


## Overview:

The purpose of this project is to look at data from weather stations in Oahu, Hawaii for the months of December and June to determine if a surf and ice cream shop business is sustainable in both summer and winter months.  Using jupyter notebook, sqlalchemy, and pandas functions, summary statistics for June and December temperatures in degrees Farhenheit, found in the hawaii.sqlite database were calculated for comparison after placing the sqlite query data into pandas DataFrames. The hawaii.sqlite database conatained weather data for all months from the years 2010 to 2017. Weather data included the weather station id, precipitation(prcp), temperature observation(tobs), and date.


## Results:


### Key differences between June and December Temperatures


* December temps are more variable then June temps, with a standard deviation(std) value of about 3.75, compared to a std of 3.26 for June temps.
* December minimum temperature of 56 F is colder than the June minimum temperature of 64 F, a difference of 8 degrees F.  The percent quartile differences in temperature are less extreme, December being 3 to 4 degrees cooler than June temps for each percent quartile.
* The mean temperature in June is warmer, about 74.9 F compared with a mean of 71.0 F for December
* June maximum temperature of 85.0 F is warmer than the December maximum temperature of 83.0 F
* There are more June temperature observations, a total of 1,700, than December temperature observations, with a total of 1,517.


## Summary:


On average, June temps are close to 4 degrees F warmer than December temps.  However, mean temperatures in both December and June are over 70 degrees Farhenheit.  Both months also have maximum temperatures over 80 F, temperatures warm enough to eat icecream.  December minimum temperature can be about 8 degrees cooler than June minimum temperatures at 56 F.  Having information on the time of day the temperature was taken would give insight weather these minimum temperatures would decrease the success of the icecream and surf shop business.  If minimum temperatures occur when the icecream and surf shop are closed, they will not impact icecream sales.  The surf shop may want to change its hours depending on the season, closing earlier in December when night time temperatures are cooler.  Summary statistics on precipitation during the months of December and June could also inform the year-round success of the surf shop.  Rain may make surfing less likely and lead to less customers.    
