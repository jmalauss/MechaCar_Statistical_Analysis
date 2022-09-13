# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Linear Model](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/linear_model.png)

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The two variables that provided a non-random amount of variance were vehicle_weight and the ground_clearance. The p-value for ground_clearance was 5.77e-08, which converts to 0.0000000577. In other words, a p-value of 0.0001 means the probability of being wrong is 1 in 10,000. Therefor, ground_clearance is a variable that we can use to make predictions mpg. Although vehicle_weight has a p-value > 0.05, we can still consider it when making predictions about mpg - there is just a better chance that we are incorrect in our predictions.

#### Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered to be zero. The "Estimate" column in the output displays slopes that (if plotted) will display a line of best fit for each independent variable.

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The linear model is an effective predictor of prototypes. In other words, when designing prototypes we understand (from the linear regression) that vehicle_weight and ground_clearance are effective predictors of mpg. Therefore, when designing prototypes, we can be conscious of the effects that vehicle_weight and ground_clearance may have on the car's mpg.

## Summary Statistics on Suspension Coils

![total_summary](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/total_summary.png)
![lot_summary](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/lot_summary.png)

#### Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
*The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 
pounds per square inch.*

Lot 3 does not meet the design specification of the variance of the suspension being less than or equal to 100 pounds per square inch. The variance for Lot 3 is about 170. Across all manufacturing lots, the variance is within compliance of the design specifications.

## T-Tests on Suspension Coils
#### Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

1. All Manufacturing Lots vs. Population (Population Mean = 1500)
![All Lots vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lots_vs_Population.png)

The mean across all Manufacturing Lots is 1498.78. The p-value of 0.4533 indicates that there is not a significant difference between all Manufacturing Lot means and the Population mean.

2. Lot 1 vs. Population
![Lot 1 vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lot1_vs_pop.png)

The mean for Lot 1 is 1500. There is no difference between Lot 1 and the population mean as indicated by the p-value of 1.

3. Lot 2 vs. Population
![Lot 2 vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lot2_vs_pop.png)

The mean for Lot 2 is 1500.2 The p-value of 0.6072 indicates no significant difference between Lot 2 and the population mean of 1500.

4. Lot 3 vs. Population
![Lot 3 vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lot3_vs_pop.png)

The mean for Lot 3 is 1496.14. There is a significant difference between the mean of Lot 3 and the population mean. The p-value is 0.04168 which is less than 0.05. 

## Study Design: MechaCar vs Competition
#### *Write a short description of a statistical study that can quantify how the MechaCar performs against the competition.*

**What metric or metrics are you going to test?** - For this research study, I would like to understand the relationship between safety rating and cost.

**What is the null hypothesis or alternative hypothesis?** - Null: If a car does not have a high safety rating, then it will not be expensive. Alternative: If a car has a high safety rating, then the price will be more expensive.

**What statistical test would you use to test the hypothesis? And why?** - I would use a Linear Regression to see if each x-value (safety rating) is related to each y-value (price). We can produce a line of best fit to understand what happens to price as safety ratings increase.

**What data is needed to run the statistical test?** - We would need safety rating data and price data for cars.
