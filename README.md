# MechaCar Statistical Analysis





## Linear Regression to Predict MPG

* The Vehicle Length and the Ground Clearance coefficients provides a non-random amount of variance to the MPG values in the dataset. The variables above have a significant impact on the MPG 
* The slope of the model is not considered to be zero and why it is is because the null hypothesis has been rejected.
* It does not predict the mpg effectively because even though the R-Squared value of the model is 0.71 there are still some significant variables that it lacks. Overfitting is taking place.



## Summary Statistics on Suspension Coils

The current manufacturing data meets the design specifications for all manufacturing Lots in total including Lot1 and Lot 2.

Lot3 has a variance above the design specification of 100 PSI 

## T-Tests on Suspension Coils

The mean of the population is 1500 PSI and we are assuming a significance level of 0.05

When the p-value is above the significance level that was set and we do not have enough evidence to reject the null hypothesis.

The two means are statistically similar 

#### All Lots

The p-value is above the significance level and so the mean of the total lot PSI is statistically similar to the population mean

![T-Test for All Three Lots](images\t-test_all_lots.png)

#### Lot 1

The p-value is above the significance level and so the mean of the lot1 PSI is statistically similar to the population mean

![T-Test for Lot 1](images\t-test_lot_1.png)

#### Lot 2

The p-value is above the significance level and so the mean of the lot2 PSI is statistically similar to the population mean

![T-Test for Lot 2](images\t-test_lot_2.png)

#### Lot 3

The p-value is below the significance level and so the mean of the lot3 PSI is not statistically similar to the population mean

![T-Test for Lot 3](images\t-test_lot_3.png)



## Study Design: MechaCar vs Competition

