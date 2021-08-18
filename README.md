# surfs_up

Analyzing weather data in jupyter notebook and making an app

## Overview of analysis

The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

## Results

- In June we had a total count of 1700, mean of 74.9, min of 64.0 and max of 85.0

![June Temps](https://github.com/alesandelmoral/surfs_up/blob/main/Challenge/June_Temps.PNG)

- In December we had a total count of 1517, mean of 71.0, min of 56.0 and max of 83.0
- Standard deviation is 3.25 in June and 3.75 -- making a .5 difference in the two different seasons

![December Temps](https://github.com/alesandelmoral/surfs_up/blob/main/Challenge/December_Temps.PNG)

## Summary

We can notice that most of our tempetures in june and december are mostly good for starting our business, because more than 50% of the tempetures are greater than 71°, as we know there are another factors that will afect our business because of this we made another research to take a more informed decision, the results of the precipitation that this two monts have are the following, as we can notice the the probability of having rains in this two monts is very low, with this two factors we can say partially that the business may be feasible:

- June Precipitation

![June Precipitation](https://github.com/alesandelmoral/surfs_up/blob/main/Challenge/June_Prec.PNG)

- December Precipitation

![December Precipitation](https://github.com/alesandelmoral/surfs_up/blob/main/Challenge/December_Prec.PNG)