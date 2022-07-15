# PyBer_Analysis
Mod 5
## Overview of PyBer Data Analysis
-	In this module, I am performing an exploratory analysis on (2) large CSV 
	files that I merged into one combined file. Then I devided the combined
	file into smaller data frames such as:
1) Total Rides
2) Total Drivers
3) Total Fares
	And used those data frames to create desciptive statistics such as:
4) Average Fare per Ride
5) Average Fare per Driver
### Purpose
-	After resetting, turning the "date" column into an index, restricting 
	the index to a specific time range (Jan. 2019 to April 2019), and
	resampling the data frame so that it accumulates values weekly (instead
	of by the second), I plotted my results in a line graph showing total
	fares by sity type.	
## City Type Results
### Breakdown
-	Rural: 6.8% of the total fares but only 0.8% of the total drivers (see analysis folder)
-	Suburban: 30.5% of the total fares but only 12.5% of the total drivers (see analysis folder)
-	Urban: 62.7% of the total fares and 86.7% of the total drivers (see analysis folder)
### Observations
-	Rural: The least amount of rides, drivers and fares but the highest fare averages
-	Urban: The highest amount of rides, drivers and fares but the least fare averages
## Summary
### Recommendations
1) In Rural communities, Increasing the number of drivers and adjusting the fares  
could offer an opportunity. I recommend increasing the number of drivers from 78 to 
108. This increase will incentivize customers to use Pyber more often. Since driver 
availability is currently limited, the average fare discourages ride use.
2) In Urban communities, shorter rides happen more frequently. I recommend increasing
fares on shorter rides. This will bump up the average fare but the difference in price
won't be high enough to discourage customers.
3) Suburban numbers look good but with more work from home work opportunities available,
this could be a segment to re-focus on. I recommend expanding advertising targeted to 
suburban communities. 