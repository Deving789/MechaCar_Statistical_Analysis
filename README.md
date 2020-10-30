# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance     and vehicle_length.

- Is the slope of the linear model considered to be zero? Why or why not?

  Our slope is not zero just be looking at the p-value, which is less than 0.05.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  Our R-squared value is 71%, which means roughly ~71% of the time the model will predict mpg values correctly. There are probably other factors that were not captured in the datasaet that contribute to the mpg variability of the MechaCar prototypes.
  
## Summary Statistics on Suspension Coils,
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

  All lots meet the current design because the variance for each lot does not go above or below 75. 

## T-Tests on Suspension Coils

- Since our P-value is above the standard .05 we do not have enough evidence to reject our null hypothesis. The two means are statistically similar. Our 3rd lot shows the most variance which shows that there is something fishy going on.

## Study Design: MechaCar vs Competition

- 
