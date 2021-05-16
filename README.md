# Surfs up


## Overview:

The purpose of this project is to look at data from weather stations in Oahu, Hawaii for the months of December and June to determine if a surf and ice cream shop business is sustainable in both summer and winter months.  Using jupyter notebook, sqlalchemy, and pandas functions, summary statistics for June and December temperatures in degrees Farhenheit were calculated for comparison after placing the queries of the hawaii.sqlite database into pandas DataFrames. The hawaii.sqlite database contained weather data for all months from the years 2010 to 2017. Weather data included the weather station id, weather station name, precipitation in inches(prcp), temperature observation in degrees Farhenheit(tobs), and date of observation.


link to hawaii.sqlite: https://github.com/cmhume/surfs_up/blob/5386659b70a6c3c7c63edc8d738204e85705ed27/hawaii.sqlite


link to jupyter notebook: https://github.com/cmhume/surfs_up/blob/0368d9150dcf2aae21aea212a374eca80f43fc53/SurfsUp_Challenge.ipynb


## Results:


### Key differences between June and December Temperatures


* December temps are more variable then June temps, with a standard deviation(std) value of about 3.75, compared to a std of 3.26 for June temps.
* December minimum temperature of 56 F is colder than the June minimum temperature of 64 F, a difference of 8 degrees F.  The percent quartile differences in temperature are less extreme, December being 3 to 4 degrees cooler than June temps for each percent quartile.
* The mean temperature in June is warmer, about 74.9 F compared with a mean of 71.0 F for December
* June maximum temperature of 85.0 F is warmer than the December maximum temperature of 83.0 F
* There are more June temperature observations, a total of 1,700, than December temperature observations, with a total of 1,517.


#### June temperature summary statistics:

![june_temp_stats](https://user-images.githubusercontent.com/78699521/118415238-27739780-b65e-11eb-921a-a275468a0d48.png)


#### December temperature summary statistics:


![dec_temp_stats](https://user-images.githubusercontent.com/78699521/118415248-31959600-b65e-11eb-8138-e5897d13aaed.png)


## Summary:


On average, June temps are close to 4 degrees F warmer than December temps.  However, mean temperatures in both December and June are over 70 degrees Farhenheit.  Both months also have maximum temperatures over 80 F, temperatures warm enough to eat icecream.  December minimum temperature can be about 8 degrees cooler than June minimum temperatures at 56 F.  Having information on the time of day the temperature was taken would give insight weather these minimum temperatures would decrease the success of the icecream and surf shop business.  If minimum temperatures occur when the icecream and surf shop are closed, they will not impact icecream sales.  The surf shop may want to change its hours depending on the season, closing earlier in December when night time temperatures are cooler.  Histograms of temperature observations from the weather station with the most readings show temperature frequencies during the months of December and June.  Summary statistics on precipitation during the months of December and June could also inform the year-round success of the surf shop.  Rain may make surfing less likely and lead to less customers. The summary statistics of precipitation in June show an average rainfall of 0.14 inches, a maximum rainfall of 4.43 inches, a minimum of 0.0 inches, and a 75% percentile of 0.12 inches of rainfall.  This means most days in June have less than 0.12 inches of rainfall, with some days of heavy rain.  The summary statistics of precipitation in December are similar to those of June when looking at the percentiles, the 75% percentile being 0.15 inches of precipitation.  December maximum precipitation is higher than June at 6.42 inches. The average rainfall is also slightly higher rounded to 0.22 inches.  Histograms from the weather station with the most readings for precipitation during June and December both show the greatest frequency of readings being 0.0 inches of rain, with higher rainfall occuring less often.  This information suggests the temperature and precipitation should allow for both surfing and icecream year-round.


### Precipitation Summary Statistics for June


![june_precip_stats](https://user-images.githubusercontent.com/78699521/118415255-3e19ee80-b65e-11eb-8d16-760ab8cd5d05.png)


### Precipitation Summary Statistics for December


![dec_precip_stats](https://user-images.githubusercontent.com/78699521/118415269-4540fc80-b65e-11eb-8857-ae1ff3c264bc.png)


### Temperature Histograms from weather station 'USC00519281'


#### June:
![june_temp_histogram](https://user-images.githubusercontent.com/78699521/118415286-5558dc00-b65e-11eb-8d75-e6a21b5e075c.png)


#### December:
![dec_temp_histogram](https://user-images.githubusercontent.com/78699521/118415297-66a1e880-b65e-11eb-99f2-e1ee7e053fae.png)


### Precipitation Histograms from weather station 'USC00519281'


#### June:
![june_precip_histogram](https://user-images.githubusercontent.com/78699521/118415310-77eaf500-b65e-11eb-9d3c-25cea51e75ff.png)


#### December:
![dec_precip_histogram](https://user-images.githubusercontent.com/78699521/118415319-81745d00-b65e-11eb-8d3f-dcd98b14660a.png)

