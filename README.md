


# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Used R for Statistics.

<img width="712" alt="Screen Shot 2021-08-26 at 1 45 44 PM" src="https://user-images.githubusercontent.com/14239715/131011083-6ca7892a-cd8b-4a7d-b788-c831f51caf19.png">

<img width="503" alt="Screen Shot 2021-08-26 at 2 37 48 PM" src="https://user-images.githubusercontent.com/14239715/131017858-9259a17c-50ef-4693-b320-f7787a038518.png">

The vehicle_weight, spoiler_angle and AWD provided a non-random amount of variance to the mpg values in the dataset. 
Is the slope of the linear model is not considered to be zero because the ocefficient if the Intercept has a p value of 5.35 e-11 which is not zero.
This linear model predicts mpg of MechaCar prototypes around 71% of the time based on the R-squared value of 0.7149. This is an accurate model predictor. 


# T-Tests on Suspension Coils

## Summary of the t-test results for all manufacturing lots

<img width="533" alt="Screen Shot 2021-08-31 at 5 09 07 AM" src="https://user-images.githubusercontent.com/14239715/131477358-c8a8001a-c62f-4596-833d-a318844619bc.png">
The mean is 1498 which correspondes and the p-value is 0.06, we can therefore not reject our null hypothesis. 

<img width="636" alt="Screen Shot 2021-08-31 at 5 09 47 AM" src="https://user-images.githubusercontent.com/14239715/131477398-74bc7640-449a-4fca-8b42-98a40d5a92d9.png">

Lot 1 has p-value of 1 so we can not reject our null hypothesis. The two means are similar.
Lot 2 has a p-value of 0.61 so we can not reject our null hypothesis. The two means are similar.
Lot 3 has a p-value of 0.04. We CAN reject our null hypothesis because the p-value is lower than 0.05. the means are NOT statistically similar. 

# Conclusion

The null hypothesis would claim that If MechaCar's vehicles are not more fuel efficient than the competition, we would not see a difference in city and highway fuel efficiency. We would then compare the competitor's cars to MechCar's using a linear regression model and the same factors: Vehicle length, vehicle width, spoiler angle, ground clearence and AWD. 

