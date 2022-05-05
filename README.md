# Surfs Up

## Overview
For this analysis, I was tasked with analyzing weather patterns on the Hawaiian island of Oahu.  W. Avy wants to open a surf and ice cream shop on the island, and asked me to look at the temperature data for Oahu during the months of June and December, in order to determine if the surf and ice cream shop business is sustainable year round.  For this analysis, I used Python to access a SQLite database and ran statistical analysis on the temprature data for those two months.

## Results
### June Temperature Statistics
<img width="143" alt="June_Statistics" src="https://user-images.githubusercontent.com/99417460/166932204-664b9bae-8300-4f02-a15e-959c9e6fb7c7.png">

### December Temperature Statistics
<img width="136" alt="December_Statistics" src="https://user-images.githubusercontent.com/99417460/166932406-7c8a7857-a5ea-440b-b368-842a0b6f86aa.png">

### Differences
* June's recorded temperatures where from the year 2010 to 2017, while December's recorded temperatures where from 2010 to 2016.
  * The database did not have December temperature's for the year 2017.
  * June had 1700 data points.
  * December has 1517 data points (183 fewer counts than June).
* June's average temperature is approximately 75 degrees, while December's average temperature is 71 degrees.
  * This is only a four (4) degree temperature change.
* June and December's maximum temperature were only a two degree difference
  * June's maximum temperature was 85 degrees.
  * December's maximum temperature was 83 degrees.
* The biggest difference in temperature was each month's low temperature, which was an eight (8) degree difference.
  * June's lowest temperature was 64 degrees.
  * December's lowest temperature was 56 degrees.

## Summary
In summary, the weather data for the Hawaiian Island of Oahu in June and December is very similar.  With the two months being six months apart, one could assume that the weather for the entire year is very simialr.  To get a better understanding of the data for the entire year, I would recommend running an analysis for the months of March and September.

Following the same coding as the June and December queries, I analyzed the temperature data for those two months (see SurfsUp_Challenge.ipynb).  
* The average temperature for March is approximately 70 degrees, with the lowest temperature being 56 degrees and the highest temperature being 82 degrees.
* The average temperature for September is approximately 76 degrees, with the lowest tempteraure being 64 degrees and the highest temperature being 87 degrees.
Based on the temperature data for the four months queried, I would highly recommend establishing a surf and ice cream shop on the Island of Oahu.  The temperature does not seem to vary much throughout the year, and the average high is in the 70's, which is perfect weather to surf and enjoy ice cream.

To optamize the analysis, I would recommend analyzing the folowing:
* Precipitation data for the months of June and December.  
* Analyze the data for each reporting weather station to determine the best area of the island to locate the surf and ice cream shop




