# Bayesian parameter estimation and hypothesis testing

## Scenario
The e-commerce company has recorded data from its website, tracking the number of visits and corresponding revenue figures. Your task is to analyze how the number of visits impacts revenue generation, using Bayesian methodologies.

## Solution:

### Import the libraries
![image](https://github.com/user-attachments/assets/c36ad0b2-363c-4dd4-ac14-80f0084e41b4)

### Load data and conduct exploratory analysis to understand the structure and distribution of the data.
![image](https://github.com/user-attachments/assets/39997f95-0881-4161-b143-8a4be734cc9e)

### Define predictor (number of visits) and the response variable (revenue)
![image](https://github.com/user-attachments/assets/6c0429cc-93e8-4048-9cab-372abf5e96db)

### Visualise the relationship between the predictor and the response variable.
![image](https://github.com/user-attachments/assets/a655f346-e647-4de2-8380-77adfac3a419)

### Construct a Bayesian linear regression model using PyMC to estimate the effects of the predictor on the revenue.
![image](https://github.com/user-attachments/assets/9ec0e450-0eef-4a3f-bfd4-a9a644138153)

### Draw samples from the posterior distribution using PyMC and visualize the results to understand the variability and uncertainty in the estimates.
![image](https://github.com/user-attachments/assets/032c4276-4c05-4032-ae76-ffd822a58f78)

![image](https://github.com/user-attachments/assets/cd457c21-67a0-4e27-b7e2-bf08708a3986)

## Conclusion
The mean of alpha, beta and sigma all fall between 3% amd 97% of their high density interval. Furthermore, r_hat are all 1, indicating the simulations converge to the same distribution. Therefore they confirm the validity of the model.

From the model, we infer that since (mu = alpha + beta * X),

mu = 144.97 + 0.23 X

The expected value of Y when X is 0 is 144.97. For each unit of X increase, Y increases by 0.23.


