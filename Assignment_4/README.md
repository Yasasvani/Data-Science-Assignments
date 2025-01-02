# Hypothesis Testing and Chi-Square Test

# Bombay Hospitality Ltd. Operating Cost Analysis

## Background

This project investigates the claim made by restaurant owners of Bombay Hospitality Ltd. that their weekly operating costs are higher than the current cost model suggests. Bombay Hospitality Ltd. operates a franchise model for producing exotic Norwegian dinners throughout New England. The existing cost model is given by the equation W = $1,000 + $5X, where X represents the number of units produced in a week.

## Objective

The objective of this analysis is to use hypothesis testing to determine if there is strong evidence to support the restaurant owners' claim about the increase in weekly operating costs.

## Data

The following data was used in the analysis:

* Theoretical weekly operating cost model: W = $1,000 + $5X
* Sample of 25 restaurants with a mean weekly cost of Rs. 3,050
* Number of units produced in a week (X) follows a normal distribution with a mean (μ) of 600 units and a standard deviation (σ) of 25 units

## Hypothesis Testing

1. **Hypotheses Statement:**
    * Null Hypothesis: The weekly operating costs are not higher than the model suggests.
    * Alternative Hypothesis: The weekly operating costs are higher than the model suggests.

2. **Test Statistic:**
    * The test statistic (t) was calculated using the following formula: `t = (x̄ - μ) / (σ / √n)`
    where:
       * `x̄` = sample mean weekly cost (Rs. 3,050)
        * `μ` = theoretical mean weekly cost according to the cost model (W = $1,000 + $5X for X = 600 units)
        * `σ` = 5 * 25 units (standard deviation of weekly cost)
        * `n` = sample size (25 restaurants)

3. **Critical Value:**
    * The critical value was determined using the alpha level of 5% (α = 0.05) from the standard normal (Z) distribution table.

4. **Decision:**
    * The test statistic was compared with the critical value to decide whether to reject the null hypothesis.

5. **Conclusion:**
    * Based on the decision in step 4, a conclusion was drawn about whether there is strong evidence to support the restaurant owners' claim that the weekly operating costs are higher than the model suggests.


## Results

The analysis revealed that the test statistic was significantly lower than the critical value. Therefore, the null hypothesis was not rejected. This means there is no strong evidence to support the restaurant owners' claim that the weekly operating costs are higher than the model suggests.

# Chi-Square Test for Independence: Smart Home Device Customer Satisfaction

## Overview

This project investigates the association between the type of smart home device purchased (Smart Thermostat vs. Smart Light) and customer satisfaction levels using the Chi-Square Test for Independence.

## Background

Mizzare Corporation aims to understand if there's a significant relationship between the type of device and customer satisfaction. This analysis uses a contingency table summarizing customer satisfaction levels for both device types.

## Data

The data represents the counts of customers in each satisfaction level category for both Smart Thermostats and Smart Lights. It is structured as a contingency table:

| Satisfaction Level | Smart Thermostat | Smart Light | Total |
|---|---|---|---|
| Very Satisfied | 50 | 70 | 120 |
| Satisfied | 80 | 100 | 180 |
| Neutral | 60 | 90 | 150 |
| Unsatisfied | 30 | 50 | 80 |
| Very Unsatisfied | 20 | 50 | 70 |
| Total | 240 | 360 | 600 |

## Methodology

1. **State the Hypotheses:**
   - Null Hypothesis: There is no association between device type and customer satisfaction.
   - Alternative Hypothesis: There is an association between device type and customer satisfaction.

2. **Compute the Chi-Square Statistic:**
   - Calculate the expected frequencies for each cell in the contingency table.
   - Use the formula: `chi_square_statistic = ((observed_data - expected_data) ** 2 / expected_data).sum()`

3. **Determine the Critical Value:**
   - Set the significance level (alpha) to 0.05.
   - Calculate the degrees of freedom: `(number of rows - 1) * (number of columns - 1)`
   - Use the chi-square distribution to find the critical value.

4. **Make a Decision:**
   - Compare the calculated Chi-Square statistic with the critical value.
   - If the Chi-Square statistic is greater than the critical value, reject the null hypothesis. Otherwise, fail to reject the null hypothesis.

## Results

- Chi-Square Statistic: 5.64
- Critical Value: 9.49
- Degrees of Freedom: 4
- P-value: 0.227

## Conclusion

Since the Chi-Square statistic is less than the critical value, we fail to reject the null hypothesis. Therefore, there is no significant association between the type of smart home device and customer satisfaction levels at the 5% significance level. Customer satisfaction appears to be independent of the type of device purchased.


## Code

The Python code used for this analysis can be found in the accompanying Jupyter Notebook files.

## Dependencies

The following libraries are required to run the code:

* `scipy.stats`
* `numpy`
