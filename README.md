# MechaCar_Statistical_Analysis
Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes Collect summary statistics on the pounds per square inch (PSI) of thesuspension coils from the manufacturing lots Run t-tests to determine if the manufacturing lots are statisticallydifferent from the mean population Design a statistical study to compare vehicle performance of theMechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.
## Linear Regression to Predict MPG
![LM() Function](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/lm()%20function.jpg?raw=true)
![Summary() Function](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/summary()function.jpg?raw=true)

### Statistical Summary
- Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance to the mpg values in the dataset. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.

- The slope is not zero.  The p-value is less than 0.05. There is enough evidence to reject our null hypothesis, which further provides that the slope of the linear model is not zero.

- The R-squared value is 71%, estimated ~71% of the time the model will predict mpg values correctly.  Removal of independent variables such as vehicle weight, spoiler angle, and All Wheel Drive, the predictability decreases by the r-squared value lowering from 0.71 to 0.67.
