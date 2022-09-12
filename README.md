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

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 
pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and 
each lot individually? Why or why not?

## T-Tests on Suspension Coils
briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

## Study Design: MechaCar vs Competition (use the stats cheat sheet)
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?

The statistical study design has the following:
A metric to be tested is mentioned (5 pt)
A null hypothesis or an alternative hypothesis is described (5 pt)
A statistical test is described to test the hypothesis (5 pt)
The data for the statistical test is described (5 pt)




Pictures:



![All Lots vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lots_vs_Population.png)
![Lot 1 vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lot1_vs_pop.png)
![Lot 2 vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lot2_vs_pop.png)
![Lot 3 vs Pop](https://github.com/jmalauss/MechaCar_Statistical_Analysis/blob/main/Pictures/Lot3_vs_pop.png)
