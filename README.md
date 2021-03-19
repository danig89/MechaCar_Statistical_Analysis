# MechaCar_Statistical_Analysis

## Purpose
The purpose of this project was to analyze data for AutosRUs’ newest prototype, the MechaCar, and review the production data for insights that may help the manufacturing team address production problems. The objectives were to:

- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

## Linear Regression to Predict MPG
### Figure 1: Linear Regression
![Linear Regression](Resources/linear_regression.png)
<br>

### Figure 2: Summary of Linear Regression
![Summary of Linear Regression](Resources/linear_regression_summary.png)
<br>

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables that provided a non-random amount of variance are vehicle length and ground clearance, as the p-values for these variables are less than 0.05. A p-value less than or equal to 0.05 is a strong indication of a non-random sample and provides evidence that the null hypothesis should be rejected. This would mean that there is a relationship between mpg and vehicle length, and mpg and ground clearance.

#### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not zero, but it is close. This can be determined by examining the estimated values, none of which equal zero, and the p-value, which is less than 0.05 at 5.35e-11 (Figure 2).

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear model does predict the mpg of prototype effectively, but it can be improved. An adjusted R-squared value that is closer to 1 indicates that a large proportion of the variability in the outcome has been explained by the regression model.(1) The adjusted R-squared value is 0.6825 (Figure 2), demonstrating that the model is somewhat effective.

## Summary Statistics on Suspension Coils
### Figure 3: Total Summary
![Total Summary](Resources/total_summary.png)
<br>

### Figure 4: Lot Summary
![Lot Summary](Resources/lot_summary.png)
<br>

#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 

##### Does the current manufacturing data meet this design specification for all manufacturing lots in total? Why or why not?
The current manufacturing data does meet design specifications for all manufacturing lots in total. In Figure 3, we can see that the variance is 62.29, which is less than 100.

##### Does the current manufacturing data meet this design specification for each lot individually? Why or why not?
The current manufacturing data meets the design specifications in Lot 1 and Lot 2, as the variance is 0.97 for Lot 1 and 7.47 for Lot 2 (Figure 4). The manufacturing data for Lot 3 does not meet design specifications, with a variance of 170 (Figure 4).

## T-Tests on Suspension Coils
### Figure 5: T-test for All Lots
![T-test All Lots](Resources/t_test_all.png)
<br>

### Figure 6: T-test for Lot 1
![T-test Lot 1](Resources/t_test_lot1.png)
<br>

### Figure 7: T-test for Lot 2
![T-test Lot 2](Resources/t_test_lot2.png)
<br>

### Figure 8: T-test for Lot 3
![T-test Lot 3](Resources/t_test_lot3.png)
<br>

## Study Design: MechaCar vs Competition
