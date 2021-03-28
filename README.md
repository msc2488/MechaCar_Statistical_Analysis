# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  Vehicle weight, spoiler angle and AWD all provide a non-random amount of variance. The primary sources of random variance were ground clearance and vehicle length.

- Is the slope of the linear model considered to be zero? Why or why not?

  The slope is not zero. Illustrated by the p-value, which is less than 0.05.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  The R-squared value is 71%, meaning roughly 71% of the time the model predicts MPG values correctly. There are other harder to quantify factors not captured in the datasaet that contribute to MPG variability of the MechaCar prototypes.
  
## Summary Statistics on Suspension Coils,
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

  Lot 1 and Lot 2 are both within design specifications and have hnearly the same exact mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

## T-Tests on Suspension Coils

- Lot 1 and Lot 3 the PSI values are not different from the population mean. However lot 2 the p-value is .347 which means there is evidence that the suspension coil is different from the population mean. All t-tests can be seen below:

## Across all lots:
<img width="783" alt="mean" src="https://github.com/msc2488/MechaCar_Statistical_Analysis/blob/fd785c65be0b7f95e51e1a79d96715cb68c587e5/All%20Lots.PNG">
## Lot 1:
<img width="729" alt="lot1" src="https://github.com/msc2488/MechaCar_Statistical_Analysis/blob/fd785c65be0b7f95e51e1a79d96715cb68c587e5/Lot%201.PNG">
## Lot 2:
<img width="793" alt="lot2" src="https://github.com/msc2488/MechaCar_Statistical_Analysis/blob/fd785c65be0b7f95e51e1a79d96715cb68c587e5/Lot%202.PNG">
## Lot 3:
<img width="729" alt="lot3" src="https://github.com/msc2488/MechaCar_Statistical_Analysis/blob/fd785c65be0b7f95e51e1a79d96715cb68c587e5/Lot%203.PNG">

## Study Design: MechaCar vs Competition

- Most people are interested in the horsepower when purchasing a vehicle. Horsepower, MPG and engine capacity are three variables that factor into consumer decisions. Our tests allow us to see if MechaCar is differientiated from the competiton. Our null hypothesis is: it is not different from the competition and the alternative of the opposite. We will use tje t-test after collecting data from various competitor. The t-test is comparing the population of all types of competitor vehicles.
