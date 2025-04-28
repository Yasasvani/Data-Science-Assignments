# Neural Networks

# Alphabet Recognition using Deep Learning

This assignment aims to build a deep learning model to recognize alphabets (letters) using a dataset of letter features.

## Dataset

The assignment uses the "Alphabets_data.csv" dataset. This dataset contains features extracted from images of alphabets, such as the position and size of the letter within the image. Each row represents a different alphabet sample, and the columns represent the features and the corresponding letter label.

## Model

A sequential deep learning model is built using Keras. The model consists of:

* An input layer with the shape matching the number of features in the dataset.
* One or more hidden layers with a specified number of neurons and activation functions (ReLU or tanh).
* An output layer with a softmax activation function to predict the probability of each letter.

The model is compiled with an optimizer (Adam, RMSprop, or SGD), a loss function (categorical cross-entropy), and metrics (accuracy).

## Hyperparameter Tuning

GridSearchCV is used to find the best hyperparameters for the model, including:

* The number of neurons in hidden layers.
* Activation functions for hidden layers.
* Optimizer and learning rate.

## Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results for both the default model and the tuned model are compared.

## Usage

1. **Data Preparation:**
   - Load the "Alphabets_data.csv" dataset into a Pandas DataFrame.
   - Preprocess the data by scaling numerical features using MinMaxScaler.
   - Encode the target variable (letter) using LabelEncoder and one-hot encoding.
   - Split the data into training and testing sets.

2. **Model Building:**
   - Create a sequential model using Keras.
   - Compile the model with an optimizer, loss function, and metrics.

3. **Model Training:**
   - Train the model using the training data.

4. **Hyperparameter Tuning (Optional):**
   - Use GridSearchCV to find the best hyperparameters.

5. **Model Evaluation:**
   - Evaluate the model's performance on the testing data using accuracy, precision, recall, and F1-score.

## Conclusion

The assignment demonstrates the application of deep learning for alphabet recognition. By analyzing the results, we can understand the model's performance and potentially improve it by further tuning or exploring different architectures.

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
