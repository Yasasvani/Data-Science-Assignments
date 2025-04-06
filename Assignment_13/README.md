# Decision Tree
# Heart Disease Prediction

## Overview

This assignment aims to predict the presence of heart disease using a machine learning model trained on a dataset of patient characteristics and medical history. It utilizes a Decision Tree Classifier to classify patients based on risk factors and predicts the likelihood of heart disease. The project includes data exploration, preprocessing, model training, evaluation, and hyperparameter tuning.

## Dataset

The dataset used for this assignment is the "Heart Disease Dataset" and it contains the following features:

- **age:** Age of the patient
- **sex:** Sex of the patient (Male/Female)
- **cp:** Chest pain type (typical angina, atypical angina, non-anginal pain, asymptomatic)
- **trestbps:** Resting blood pressure (in mm Hg on admission to the hospital)
- **chol:** Serum cholesterol in mg/dl
- **fbs:** Fasting blood sugar > 120 mg/dl (True/False)
- **restecg:** Resting electrocardiographic results (normal, having ST-T wave abnormality, showing probable or definite left ventricular hypertrophy)
- **thalach:** Maximum heart rate achieved
- **exang:** Exercise induced angina (Yes/No)
- **oldpeak:** ST depression induced by exercise relative to rest
- **slope:** The slope of the peak exercise ST segment (upsloping, flat, downsloping)
- **thal:** Thalassemia (normal, fixed defect, reversible defect)
- **num:** Diagnosis of heart disease (angiographic disease status) (0-4, where 0 indicates no disease and 4 indicates severe disease)

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- IPython

## Usage

1. Upload the dataset file (`heart_disease.xlsx`) to Google Colab.
2. Run the Colab notebook (`heart_disease_prediction.ipynb`) to execute the code.

## Model Evaluation

The model is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC AUC

## Hyperparameter Tuning

The model's hyperparameters are tuned using GridSearchCV to find the optimal settings for improved performance.

## Results

The model achieved an accuracy of [insert accuracy score] on the test set.

## Conclusion

This assignment demonstrates the application of machine learning in predicting heart disease. The Decision Tree Classifier, after hyperparameter tuning, provided promising results. Further improvements could be explored by using other algorithms, feature engineering, and larger datasets.

## Contributing

Contributions to this assignment are welcome! Feel free to submit pull requests for bug fixes, improvements, or new features.

## License

This project is licensed under the MIT License.
