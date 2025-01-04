# MLR
# Toyota Corolla Price Prediction

## Assignment Overview

This assignment aims to predict the price of used Toyota Corolla cars based on various features such as age, mileage, horsepower, and fuel type. It utilizes a Multiple Linear Regression (MLR) model trained on a dataset of Toyota Corolla sales. The assignment involves data exploration, preprocessing, model building, evaluation, and the application of regularization techniques like Lasso and Ridge regression.

## Dataset

The dataset used for this assignment is named "ToyotaCorolla - MLR.csv" and contains information about used Toyota Corolla cars, including their price and various features.

## Methodology

1. **Exploratory Data Analysis (EDA):** The dataset is analyzed to understand its structure, identify missing values, outliers, and relationships between features. Visualizations such as box plots, histograms, and scatter plots are used to gain insights into the data.

2. **Data Preprocessing:**
    - Missing values are handled (if any).
    - Categorical features are encoded using one-hot encoding.
    - Outliers are detected and treated.

3. **Model Building:**
    - The dataset is split into training and testing sets.
    - A Multiple Linear Regression (MLR) model is trained using the training data.
    - Several variations of the MLR model are explored, including using a subset of features and applying polynomial features.

4. **Model Evaluation:**
    - The trained models are evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
    - The performance of different models is compared to select the best one.

5. **Regularization:**
    - Lasso and Ridge regression techniques are applied to the models to address potential overfitting and improve generalization.

## Results

The performance of the models is evaluated and compared based on the chosen metrics. The results demonstrate the effectiveness of the MLR model in predicting Toyota Corolla prices. Regularization techniques are shown to further improve model performance.

## Conclusion

This assignment demonstrates the application of machine learning techniques to predict car prices. The MLR model, along with regularization, provides a reliable approach for estimating the price of used Toyota Corolla cars based on their features.

## Future Work

Possible future improvements include exploring other machine learning algorithms, such as Random Forest or Gradient Boosting, and incorporating more relevant features into the model.

## Usage

To run this assignment:

1. Upload the "ToyotaCorolla - MLR.csv" dataset to your Google Colab environment.
2. Execute the provided Python code in the notebook.
3. The code will perform the steps outlined in the methodology section and display the results.
