# MechaCar_Statistical_Analysis
Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes Collect summary statistics on the pounds per square inch (PSI) of thesuspension coils from the manufacturing lots Run t-tests to determine if the manufacturing lots are statisticallydifferent from the mean population Design a statistical study to compare vehicle performance of theMechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG
![LM() Function](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/lm()%20function.jpg?raw=true)
![Summary() Function](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/summary()function.jpg?raw=true)

### Deliverable 1 Statistical Summary
- Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance to the mpg values in the dataset. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.

- The slope is not zero.  The p-value is less than 0.05. There is enough evidence to reject our null hypothesis, which further provides that the slope of the linear model is not zero.

- The R-squared value is 71%, estimated ~71% of the time the model will predict mpg values correctly.  Removal of independent variables such as vehicle weight, spoiler angle, and All Wheel Drive, the predictability decreases by the r-squared value lowering from 0.71 to 0.67.

## Summary Statistics on Suspension Coils
![Total Summary Screenshot](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/total_summary_screenshot.jpg)
![Lot Summary Screenshot](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/Lot%20Summary%20Image.jpg)

### Deliverable 2 Statistical Summary
- Lot 1 and Lot 2 are within design specifications and have close to the same mean and median. The variance of coils are 0.98 and 7.47 respectively, which is within the 100 PSI variance requirement.  Lot 3 shows the most variance and exceeds the manufacturers specs with a variance of 170.29.

## T-Tests on Suspension Coils
![SuspensionPSI Screenshot](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/Suspension%24PSI_Screenshot.jpg)
![Subset Lot 1 Screenshot](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/Subset_Lot_1_Screenshot.jpg)
![Subset Lot 2 Screenshot](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/Subset_Lot_2_Screenshot.jpg)
![Subset Lot 3 Screenshot](https://github.com/mayowill303/MechaCar_Statistical_Analysis/blob/main/subset_Lot_3_Screenshot.jpg)

### Deliverable 3 Statistical Summary
- The true mean of the sample is 1498.78 with a p-value 0.06.  Not enough evidence to reject the null hypothesis.
- Lot 1 and Lot 3 the PSI values are no different from the population mean.  
- Lot 2 sample mean is 1496.14 and p-Value is .347.  There is evidence that the suspension coil is different from the population mean.  Enough evidence to reject the null hypothesis. 

## Design a Study Comparing the MechaCar to the Competition
- The possible metrics we can test against are length/height/width of car, horsepower, MPG and pricing.  Seeking to find out if size/mpg/price correlate. 
#### Hypothesis
- Null Hypothesis (Ho): MechaCar is priced correctly based on its size and mpg.
- Alternative Hypothesis (Ha): MechaCar is NOT priced correctly based on size and mpg.  
#### Statistical Test
- To confirm or deny correlation, employing multiple linear regression testing would be best solution.
- This test would help determine competitive review of makes/models based on size/mpg do determine which element has substantial impact on price of vehicles.
- We would need to determine this data for competitors to establish baseline.
