# Bikesharing

## Tableu dashboard 
The Tableau can be seen here [link to dashboard](https://public.tableau.com/app/profile/santiago.cifuentes/viz/CitiBikeAnalysis_16641300532160/NYCCitiBikeAnalysis?publish=yes) 

## Overview
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Results: 
This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.
![alt text](https://github.com/santiagocy6/Bikesharing/blob/main/Trip%20duration%20by%20usage.png)
This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.
![alt text](https://github.com/santiagocy6/Bikesharing/blob/main/Trip%20duration%20by%20gender.png)

![alt text](https://github.com/santiagocy6/Bikesharing/blob/main/Number%20of%20trips.png)
![alt text](https://github.com/santiagocy6/Bikesharing/blob/main/Number%20of%20trips%20by%20gender.png)
Lastly, this heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.
![alt text](https://github.com/santiagocy6/Bikesharing/blob/main/Number%20of%20trips%20by%20usertype.png)

## Summary

In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

