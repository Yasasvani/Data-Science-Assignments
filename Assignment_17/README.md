# Support Vector Machine
# Mushroom Classification

This assignment aims to classify mushrooms as edible or poisonous using machine learning. It utilizes a Support Vector Machine (SVM) model trained on a dataset of mushroom features.

## Dataset

The dataset used in this assignment contains information about various characteristics of mushrooms, including cap shape, cap surface, cap color, odor, and more. It can be found in the file 'mushroom.csv'.

## Preprocessing

- **Handling Missing Values:** The dataset is checked for missing values, and appropriate imputation techniques are applied if necessary.
- **Encoding Categorical Features:** Categorical features are converted into numerical representations using one-hot encoding.
- **Scaling Numerical Features:** Numerical features are scaled using StandardScaler to ensure that they have a similar range of values.

## Model Building

- **Support Vector Machine (SVM):** An SVM model is trained on the preprocessed data to classify mushrooms as edible or poisonous.
- **Hyperparameter Tuning:** GridSearchCV is used to find the optimal hyperparameters for the SVM model, ensuring the best performance.

## Evaluation

- **Accuracy Score:** The accuracy of the model is evaluated using the accuracy_score metric.
- **Classification Report:** A classification report is generated to provide detailed information about the model's performance, including precision, recall, and F1-score.
- **Confusion Matrix:** A confusion matrix is visualized to understand the model's predictions and identify potential areas for improvement.

## Results

The SVM model achieved high accuracy in classifying mushrooms as edible or poisonous. The classification report and confusion matrix provide further insights into the model's performance.

## Usage

To run this assignment:

1. Upload the 'mushroom.csv' file to your Google Colab environment.
2. Execute the code cells in the provided notebook.
3. The results of the model evaluation will be displayed.

## Dependencies

- Python 3
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Contributing

Contributions to this assignment are welcome. Please feel free to submit pull requests or open issues.

## License

This project is licensed under the MIT License.
