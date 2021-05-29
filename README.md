# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 
    Vechicle_weight, Spoiler_angle, and AWD variables provided a non-random amount of variance to the mpg values in the dataset.
 
- Is the slope of the linear model considered to be zero? Why or why not?
  
   The slope of this linear model is not Zero becasue p-value of this model is 5.35e-11 which is smaller than 0.05.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 
   Yes, this linear model predicts the mpg of MechaCar prototypes effectively because the r-squared value of this model is 0.7149 which means approx. 71% of mpg prediction is        determined by this model.
 
 The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight,    spoiler angle, drivetrain, and ground clearance, were collected for each vehicle. By, using R we design a linear model that predicts the mpg of MechaCar prototypes.
  
  ![first image](/Resources/image2.PNG
   )
  ![first image](/Resources/image3.PNG
   )
   
   ## Summary Statistics on Suspension Coils
   
   - The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
   
   As per the manufacturing lot, the variance of the coils is 62.29356 PSI which does not exceed 100 PSI. Similarly, Lot1 and Lot2 are also do not exceed 100 PSI which variance is 0.98 and 7.47 respectively. However, Lot3 has exceeded 100 PSI which variance is 170.29. So, except lot3 others are meet this design specification. As we can see below.
   
   ![first image](/Resources/image5.PNG
   )
   ![first image](/Resources/image6.PNG
   )
   
   ## T-Tests on Suspension Coils
   Lot1 and lot2 have similar to the sample estimates mean 1500 however lot3 is less than the sample estimates mean. 
   All t-tests can be seen below:

   
   ![first image](/Resources/image7.PNG
   )
   
   ![first image](/Resources/image8.PNG
   )
   ![first image](/Resources/image9.PNG
   )
   ![first image](/Resources/image10.PNG
   )
   
   ## Study Design: MechaCar vs Competition
   
   In my view I think people are interested in when buying a car is how much safety rating and horsepower the car has. We can use our test to see if our MechaCar is different from the competition. The null hypothesis is that MechaCar is not different from the competition and the alternative hypothesis is the opposite. t-test to compare our dataset with the competitors. The t-test has already been used for this current analysis and provided the predictions needed to take the next steps for improvement. I would need safety rating and horsepower data from 50 individual cars to create a sample size of data for each car in the class type.
   
