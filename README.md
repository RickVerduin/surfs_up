# Surf's Up!

## Overview
This project analyzes temperature trends for the months of June and December on the Hawaiian islang Oahu, in order to determine the feasibility of opening an surfshop/ice creamshop. The data to be analyzed is located in a sqlite file, and the queries for the required data are made using Python, Pandas functions and methods, and SQLAlchemy.

## Results
The results of the queries are as follows:

![image](https://user-images.githubusercontent.com/93882635/151738404-fea5d408-e251-4939-8630-a6b30ac5b417.png)![image](https://user-images.githubusercontent.com/93882635/151738420-e68b13da-e461-46fa-a431-7b70b1334487.png)

Based on this data, we can determine that:

- Average temperature in June (75 degrees Fahrenheit) is slightly higher than the average temperature in December (71 degrees).
- The minimum temperature in December (56 degrees) is significantly lower than the minimum temperature in June (64 degrees)
- The standard deviation for the December temperatures is higher than the standard deviation for the June temperatures.

## Summary
Our data shows that temperatures are not an issue for surfing in Oahu. 56 degrees generally does not stop surfers from hitting the waves. Ice Cream sales will most likely be higher in June than in December, so it may be smart to supplement the business' income with some other food or drink items when winter comes around.

Other queries that would be helpful when considering the feasibility of this business:

- Looking at the amount of precipitation in summer versus rainy season (mid-November through late March).
- Looking at temperature trends at different times of the day, so that decisions can be made about opening hours in summer versus winter et cetera.
