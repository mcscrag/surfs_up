# Module 9 Challenge - Temperature Analysis for Surf Shop

## Overview

### The purpose of this analysis was to determine if the proposed surf shop could expect to run under favorable weather year-round on Oahu in Hawaii.

## Method

### To determine the viability of the surf shop year-round, the temperature data for the last several years was gathered. Specifically, the months of June and December were aggregated to see how different the weather was between summer and winter.

## Results

### June Temperature Data:

[June Temps](/june_temps.png)

### December Temperature Data:

[June Temps](/december_temps.png)

### Analysis

#### - The months of June and December differe by only 3 degrees F on average. This is a positive result for the viability of the surf shop year round.

#### - However, it should be noted that the minimum for december can get all the way down to 56 degrees F. Any day that reaches this minimum would expect significantly less business. Therefore, it is resonable to expect some number of lost business days in december anytime the temperature gets below 60 degrees.

#### - The standard deviation for the month of December is also significantly higher, supporting the idea that despite having a similar average, the temperatures in December can swing further from the mean, meaning more lows.

## Summary

#### Based on this analyis, I think the surf shop would be able to sustain business year-round. The main concern is if the weather would be good enough in the winter months to expect reliable business. Considering the average temperatures in December and June are very similar, it can safely be said that the shop would still get business in December.

#### However, as seen in the analysis above, the temperatures in December can swing further from the mean and drop significantly lower than in June. These days of below 60 degree weather should expect significantly less business and may even call for shop closure. A query should be run to determine the number of days in December that the temperature dropped below 60 degrees in order to determine how many dead business days to expect in the winter months.

#### Additionally, another query could be run to find the precipitation on these "dead" business days in the winter months in order to see if there is a correlation between the low temperatures and rainy weather. This would further support the expectation that these "dead" business days would potentially call for shop closure as the overhead costs of keeping the shop open would likely outweigh any revenue.