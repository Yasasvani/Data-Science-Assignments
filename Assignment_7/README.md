# Titanic Survival Prediction

## Overview

This Assignment aims to predict the survival of passengers on the Titanic using machine learning. It utilizes a Logistic Regression model trained on the Titanic dataset.

## Dataset

The Assignment uses the Titanic dataset, which contains information about passengers aboard the Titanic, including their demographics, travel details, and survival status.

## Methodology

1. **Data Exploration and Preprocessing:** The dataset is loaded, explored, and preprocessed to handle missing values and convert categorical variables into numerical representations.
2. **Model Building:** A Logistic Regression model is trained using the preprocessed data to predict survival based on passenger features.
3. **Model Evaluation:** The model's performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC AUC score.
4. **Deployment:** The trained model is deployed using Streamlit, allowing users to input passenger information and receive survival predictions.

## Usage

1. **Install necessary libraries.**

2. **Run the Streamlit app.**
   
3. **Enter passenger details in the app to receive a survival prediction.**


## Results

The trained model achieved an accuracy of [insert accuracy score] on the test dataset. The ROC AUC score of [insert ROC AUC score] indicates good performance in distinguishing between survivors and non-survivors.


## Interpretation

The model's coefficients reveal the importance of various features in predicting survival. 

* **Passenger Class (Pclass):** Higher passenger classes (e.g., first class) had a higher survival rate.
* **Sex:** Gender was a significant factor, with females having much higher survival odds.
* **Fare:** Passengers who paid higher fares were more likely to survive.
* **Age:** Younger passengers had a slightly higher chance of survival.



## Deployment

The model is deployed as a Streamlit web application, allowing users to interact with it and make predictions easily. This enables real-time and accessible use of the prediction model.


## Future Work

* Explore other machine learning models to potentially improve prediction accuracy.
* Investigate feature engineering techniques to create more informative features.
* Develop a user interface for easier data input and prediction visualization.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.


## License

This project is licensed under the MIT License.
