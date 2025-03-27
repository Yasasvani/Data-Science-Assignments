# Exploratory Data Analysis 2
# Adult Income Prediction

This Assignment aims to predict whether an individual's income exceeds $50,000 per year based on various demographic and socioeconomic factors. The dataset used is the "Adult" dataset, also known as the "Census Income" dataset.

## Project Structure

* `adult_with_headers.csv`: The dataset file containing the features and target variable.
* `notebook.ipynb`: Jupyter Notebook containing the code for data exploration, preprocessing, feature engineering, and model building.

## Steps

1. **Data Exploration and Preprocessing:**
    * Load the dataset using pandas.
    * Explore the data using descriptive statistics, data types, and missing values.
    * Preprocess the data by handling missing values, scaling numerical features, and encoding categorical features.

2. **Feature Engineering:**
    * Create new features to improve model performance, such as age groups and capital income.
    * Apply transformations to address skewness in features like capital gain.

3. **Feature Selection:**
    * Use techniques like Predictive Power Score (PPS) and correlation analysis to select relevant features.

## Libraries Used

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* PPScore

## Usage

1. Upload the `adult_with_headers.csv` file to your Google Colab environment.
2. Open the `notebook.ipynb` file in Colab.
3. Run the cells in the notebook to execute the code.

## Results

The notebook provides insights into the dataset, including data distributions, feature relationships, and model performance. You can further extend this project by experimenting with different models and hyperparameters.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
