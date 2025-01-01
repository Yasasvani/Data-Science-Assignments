# Basic Statistics_level 1
# Sales Data Analysis

This Assignment analyzes sales data to understand patterns, trends, and outliers. It involves data cleaning, preprocessing, exploratory data analysis (EDA), and visualization.

## Assignment Overview

The Assignment aims to gain insights from a sales dataset (`sales_data_with_discounts.csv`). It performs the following steps:

1. **Data Loading and Initial Exploration:** Loads the dataset using Pandas, checks its dimensions, and displays basic information.
2. **Descriptive Analytics:** Calculates descriptive statistics (mean, median, mode, standard deviation) for numerical columns to understand the data distribution.
3. **Data Visualization:** Creates histograms and box plots to visualize the distribution and identify potential outliers. Bar charts are used to analyze categorical columns.
4. **Standardization:** Applies standardization (z-score normalization) to numerical columns to scale them and reduce the impact of outliers.
5. **One-Hot Encoding:** Converts categorical columns into numerical format using one-hot encoding for machine learning compatibility.
6. **Conclusion:** Summarizes the key findings and insights from the analysis, emphasizing the importance of data preprocessing steps like standardization and one-hot encoding for accurate modeling.


## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage

1. Make sure you have the necessary libraries installed. If not, install them using pip
2. Upload the `sales_data_with_discounts.csv` file to your Colab environment.
3. Run the provided code in a Colab notebook.


## Findings

- Numerical columns like 'Volume', 'Net Sales Value', 'Avg Price', and 'Total Sales Value' have potential outliers.
- Most numerical columns are right-skewed, except for 'Discount Rate (%)'.
- Sales activity is relatively consistent across days of the week but varies by city, brand, and model.
- Standardization and one-hot encoding are crucial for preparing data for machine learning models.


