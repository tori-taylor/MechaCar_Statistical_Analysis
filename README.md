# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
The image below shows the results of a linear regression on variables in relation to mpg. The varables were vehicle length, vehicle weight, spoiler_angle, ground clearance and AWD.

![dev1](https://github.com/tori-taylor/MechaCar_Statistical_Analysis/blob/main/dev1.PNG)

Both vehicle_length and ground_clearence provide a non-random amount of variance to the mpg, this is assumed because the p-values are less than 0.05
The linear model does do predict mpg of MechaCar prototypes effectively as the R squared value is 0.71, or 71% of predicitions will be accurate.

## Summary Statistics on Suspension Coils
Below are images of the total_summary and lot_summary. Each identifying the suspensions coil PSI's mean, median, variance and SD. The total_summary is for the complete data set, and the lot summary is for each of the three lots. 

![total_summary](https://github.com/tori-taylor/MechaCar_Statistical_Analysis/blob/main/total_summary.PNG)

![Lot_summary](https://github.com/tori-taylor/MechaCar_Statistical_Analysis/blob/main/Lot_summary.PNG)

In the lot summary we can see that lot 3 does not meet the design specification that variance of suspension coils must not exceed 100 pounds per square inch, as the variance is 170

## T-Tests on Suspension Coils

The results of the T-Tests preformed are all below.

![t_test](https://github.com/tori-taylor/MechaCar_Statistical_Analysis/blob/main/t_test.PNG)
![lot1](https://github.com/tori-taylor/MechaCar_Statistical_Analysis/blob/main/lot1.PNG)
![lot2](https://github.com/tori-taylor/MechaCar_Statistical_Analysis/blob/main/lot2.PNG)
![lot3](https://github.com/tori-taylor/MechaCar_Statistical_Analysis/blob/main/lot3.PNG)

T-test for all lots = p-value is greater than 0.05 which means there is not enough evidence to support rejecting the null hypothesis, meaning that all lots are presumed to be similar to the populations mean

Lot 1 - the p-value is 1, and therefore the null hypothesis is not rejected and it is assumed that Lot 1 is similar to the population
Lot 2 - the p-value is 0.61, and therefore the null hypothesis is not rejected and it is assumed that Lot 1 is similar to the population
Lot 3 - the p-value is 0.04, and therefore the null hypothesis is rejected and it is assumed that Lot 3 mean is different than the population

## Study Design: MechaCar vs Competition
The first step in the analysis would be to collect information from a competitor similar to the data we have on Mecha Car. One of the most important metrics consumers would be interested in is difference in mpg, for this you could preform a t-test to see if there is a difference between MechaCar and a competitors mean mpg, the null hypothesis being that their is no difference. You could run a similar test comparing horse power and maintenance costs. 
