# Random Forest
# Glass Classification

This project aims to classify different types of glass using machine learning models. The dataset used is the Glass Identification Database, which contains various physical and chemical properties of glass samples.

## Dataset

The dataset is stored in an Excel file named `glass.xlsx` with two sheets:

- **Sheet 1 (description_df):** Contains descriptions of the features in the dataset.
- **Sheet 2 (data_df):** Contains the actual data with features and the target variable 'Type'.

## Features

The features used for classification include:

- RI: Refractive index
- Na: Sodium
- Mg: Magnesium
- Al: Aluminum
- Si: Silicon
- K: Potassium
- Ca: Calcium
- Ba: Barium
- Fe: Iron

## Target Variable

The target variable is 'Type', which represents the type of glass.

## Methodology

1. **Data Loading and Preprocessing:**
   - The data is loaded from the Excel file using pandas.
   - Data cleaning is performed, including handling missing values and duplicates.
   - The data is scaled using StandardScaler.

2. **Exploratory Data Analysis:**
   - Box plots, histograms, correlation matrices, pair plots, and violin plots are used to visualize the data and identify patterns.

3. **Model Selection and Training:**
   - Random Forest, Bagging, and Boosting models are trained and evaluated.
   - Hyperparameter tuning is performed to optimize model performance.

4. **Evaluation:**
   - Accuracy, precision, recall, and F1-score are used to evaluate the models.

## Results

The results of the different models are compared, and Boosting is found to outperform Bagging on this dataset.

## Conclusion

This project demonstrates the application of machine learning for glass classification. The results show that Boosting is a promising approach for this task.

## Additional Resources

- [Glass Identification Database](https://archive.ics.uci.edu/ml/datasets/glass+identification)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

## Usage

1. Upload the `glass.xlsx` file to your Google Colab environment.
2. Run the code cells in the notebook to load the data, train the models, and evaluate the results.

## Contributing

Contributions to this project are welcome. Please submit pull requests with any improvements or bug fixes.

## License

This project is licensed under the MIT License.
