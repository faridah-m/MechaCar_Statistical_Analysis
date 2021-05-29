# MechaCar_Statistical_Analysis
In this project, our aim is to work with AutosRU's to provide analysis on AutosRUs’ newest prototype, the MechaCar, which is suffering from production troubles that are blocking the manufacturing team’s progress.

The team has been asked to do the following:
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

# Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

When we look at the p-values of each variable ,Vehicle_length and ground_angle (as well as intercept)have a p-value of less than 5% meaning they have non-random amounts of variance to the mpg values..

- Is the slope of the linear model considered to be zero? Why or why not?

When we look at the p-valueof our linear regression(5.35e-11) which is much smaller than 5% , Therefore there is sufficient evidence to reject Null Hypothesys, which means that the slope of our linear model is not zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

According to R-Squared value of over 0.7 , we can say the probability metric of the linear model is 70% .Having said that we have an intercept that is statistically significant and that means there are other variables and factors that contribute to the variation in MPG.

