# XGBM & LGBM

# Titanic Survival Prediction

This project aims to predict the survival of passengers on the Titanic using machine learning models. It utilizes the Titanic dataset, which contains information about passengers such as age, gender, class, and whether they survived.

## Dataset

The dataset used in this project is the Titanic dataset, which is publicly available. It is divided into two parts:

*   **train.csv:** Used to train the machine learning models.
*   **test.csv:** Used to evaluate the performance of the trained models.


## Methodology

The following steps were taken to build the prediction model:

1.  **Data Loading and Preprocessing:** The dataset was loaded into a Pandas DataFrame. Data cleaning and preprocessing steps were performed, including handling missing values, converting categorical features to numerical representations, and scaling numerical features.

2.  **Exploratory Data Analysis:** Exploratory data analysis was conducted to gain insights into the data, identify patterns, and visualize relationships between features and survival.

3.  **Feature Engineering:** New features were engineered from existing ones to potentially improve model performance, such as creating a "FamilySize" feature.

4.  **Model Selection and Training:** LightGBM and XGBoost models were selected for prediction. These models were trained using the training dataset, and their performance was compared. Hyperparameter tuning was performed to optimize the models.

5.  **Model Evaluation:** The trained models were evaluated using various performance metrics, including accuracy, precision, recall, and F1-score.

6.  **Prediction:** The best-performing model was used to make predictions on the test dataset.


## Results

The performance of the LightGBM and XGBoost models was compared, and the results were visualized. The best-performing model achieved an accuracy of [insert accuracy score].

## Conclusion

This project demonstrates the application of machine learning to predict survival on the Titanic. The results show that LightGBM and XGBoost models are effective in predicting survival outcomes.


## Usage

1.  Download the Titanic dataset (train.csv and test.csv).
2.  Run the provided code in a Google Colab environment.
3.  The trained model will predict the survival of passengers in the test dataset. The predictions will be saved to a CSV file.



## Dependencies

The following libraries are required to run the code:

*   NumPy
*   Pandas
*   Matplotlib
*   Seaborn
*   Scikit-learn
*   XGBoost
*   LightGBM

You can install these libraries using `pip`:
bash pip install numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm
