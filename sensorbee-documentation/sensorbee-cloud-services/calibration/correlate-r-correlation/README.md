# Correlate (R² Correlation)

The coefficient of determination, often referred to as R² correlation or R-squared, is a statistical measure that assesses the goodness-of-fit of a regression model to the observed data. It quantifies the proportion of the variance in the dependent variable that can be explained by the independent variables in the model.

This document will describe how this tool can help assess the linear relationship between the data collected by a Sensorbee Device and the data collected by a reference station / device, by using the Pearson’s correlation coefficient (R²).

#### Steps: <a href="#id-26cb23f7e774403fbcbcc2ad08543255" id="id-26cb23f7e774403fbcbcc2ad08543255"></a>

**Step 1: Select Sensor**&#x20;

Choose the specific sensor from the device that you want to assess. This will be the sensor that the correlation will be based on.

**Step 2: Interval/Resolution**&#x20;

Determine the time interval or resolution that you want to use for the correlation. This could be every minute, every hour, or another interval that makes sense based on the data and the situation.

**Step 3: Action - Correlate**&#x20;

Choose the "Correlate" action. This will initiate the process of calculating the R-squared correlation between the sensor data and the reference data.

**Step 4: Select reference data**&#x20;

Choose the reference data that you will compare the sensor data against. This could be data from a different sensor, a different device, or a known standard or benchmark.

**Step 5: Select installation**&#x20;

Choose the specific installation that the device is part of. This could be a specific location, project, or other grouping of devices.

5. **The graph includes the following details:**

* **R² value**

| **Pearson correlation coefficient (**_**r**_**) value** | **Strength** | **Direction** |
| ------------------------------------------------------- | ------------ | ------------- |
| Greater than .5                                         | Strong       | Positive      |
| Between .3 and .5                                       | Moderate     | Positive      |
| Between 0 and .3                                        | Weak         | Positive      |
| 0                                                       | None         | None          |
| Between 0 and –.3                                       | Weak         | Negative      |
| Between –.3 and –.5                                     | Moderate     | Negative      |
| Less than –.5                                           | Strong       | Negative      |

* **The linear equation**

Technical note: Linear regression is represented by an equation Y= BX + A. The B is the slope that is equal to r(Sy/Sx) where r is the correlation coefficient, Sy is the standard deviation of y values and Sx is the standard deviation of x value. The equation of A (the intercept) is equal to the meanY-(B\*meanX), where meanY and meanX are the means of the y values and x values, respectively.

* **Significance of the Result**

Using the Significance level of 0.001

p < 0.001 means the relationship is statistically significant.

p > 0.001 means the relationship is not statistically significant.

[**Calibrate**](./#calibrate)\

