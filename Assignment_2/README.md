# Basic Stats-2

# Print-Head Durability Analysis

## Overview

This project analyzes the durability of print-heads, measured in millions of characters printed before failure. The analysis involves constructing confidence intervals for the mean number of characters printed before failure, using both sample and population standard deviations.

## Data

The dataset consists of durability measurements (in millions of characters) for 15 randomly selected print-heads:

1.13, 1.55, 1.43, 0.92, 1.25, 1.36, 1.32, 0.85, 1.07, 1.48, 1.20, 1.33, 1.18, 1.22, 1.29

## Analysis

### Confidence Interval with Sample Standard Deviation

A 99% confidence interval for the mean number of characters printed before failure is constructed using the sample standard deviation. The t-distribution is used due to the small sample size (n=15) and the unknown population standard deviation.

**Steps:**

1. Calculate the sample mean and standard deviation.
2. Determine the degrees of freedom (df = n-1).
3. Calculate the t-critical value.
4. Calculate the margin of error.
5. Calculate the confidence interval.

**Results:**

The 99% confidence interval using the sample standard deviation is approximately (1.09 million, 1.38 million) characters.

### Confidence Interval with Population Standard Deviation

A 99% confidence interval is also constructed using a known population standard deviation of 0.2 million characters. The z-distribution is used in this case.

**Steps:**

1. Calculate the z-critical value.
2. Calculate the margin of error.
3. Calculate the confidence interval.

**Results:**

The 99% confidence interval using the population standard deviation is approximately (1.10 million, 1.37 million) characters.

## Dependencies

- Python 3.x
- NumPy
- SciPy

## Usage

1. Install the required dependencies.
2. Run the Python code provided in the notebook.
3. The results will be displayed in the output.


## Conclusion

The analysis provides confidence intervals for the mean durability of print-heads, offering insights into their expected lifespan. The results can be used for quality control and product improvement purposes.


