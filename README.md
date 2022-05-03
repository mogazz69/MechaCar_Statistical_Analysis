# MechaCar_Statistical_Analysis

## Overview

AutosRUs' new MechaCar is "suffering from production troubles" and the company is hoping that an analytical review may help provide some insight. To do this we will:

* discover which variables predict the MPG for vehicle prototypes;
* collect summary stats on the PSI of suspension coils;
* determine if manufacturing lots are statistically different from the mean population;
* design a study to compare the MechaCar performance against vehicles from other manufacturers.

## Linear Regression to Predict MPG

> The most significant variables in our dataset which show a non-random effect on the MPG of the MechaCar are the **Vehicle Length** and the **Ground Clearance**. The linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10<sup>-12</sup> and 5.21x10<sup>-8</sup>, respectively. The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG.

## Summary Statistics on Suspension Coils

> While the overall variance, as shown in the Total Summary data above, is under 100 psi and meets specifications, there is a problem with one of the individual lots. As shown in the Lot Summary stats, the variance for Lot 3 is well over the acceptable threshold, at 170.28. linear regression model shows  p-values of 2.6x10<sup>-12</sup> and 5.21x10<sup>-8</sup>, respectively. This means that the relationship between our variables and the miles per gallon is subject to more than random chance. The r-squared value of 0.7149 indicates that the model is 71.49% accurate.

## T-Tests on Suspension Coils

> A review of the results of the T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough (0.0603) for us to reject the null hypothesis.

## Study Design: MechaCar vs Competition

> There are many factors that consumers take into consideration when evaluating a car to purchase. However, in a world where ridesharing is becoming more ubiquitous and it's easy and cheap to get around in other people's vehicles, customers looking to purchase a car are looking for more than just a conveyance. They will be looking to buy a car that is an economical means to regularly transport themselves and their items on a reliable, regular basis.

### Metric to test

> To narrow down our test, we should evaluate MechaCar's carrying capacity, in cubic meters, in comparison to various competitors' vehicles.

### Null and Alternate Hypothesis

> H<sub>0</sub>: MechaCar prototypes' average carrying capacity is similar to competitor's vehicles in the same vehicle class
> H<sub>a</sub>: MechaCar prototypes' average carrying capacity is statistically above or below that of competitor vehicles.

### Statistical Test Used

> The best statistical test for this would be two-sample t-tests.

### What data is needed

> We would need to gather cubic space data from the carrying compartments of all MechaCar prototypes, as well as from all major competitor vehicles.



