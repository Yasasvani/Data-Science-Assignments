# Recommendation System
# Anime Recommendation System

This project implements an anime recommendation system using collaborative filtering in Python. It leverages the cosine similarity metric to identify similar animes based on user ratings and preferences.

## Dataset

The system utilizes the "anime.csv" dataset, which contains information about various animes, including their names, genres, ratings, and number of members.

## Methodology

1. **Data Loading and Preprocessing:** The dataset is loaded using Pandas, and missing values are handled.
2. **Feature Engineering:** Relevant features like ratings, members, genres, and types are extracted and encoded using Multi-Hot Encoding.
3. **Cosine Similarity:** The cosine similarity metric is applied to calculate the similarity between animes based on their features.
4. **Recommendation Generation:** A function is defined to recommend similar animes based on the calculated similarities.
5. **Evaluation:** The system is evaluated using precision, recall, and F1-score metrics.

## Usage

1. **Install Dependencies:** Make sure you have the necessary libraries installed:bash pip install numpy pandas matplotlib seaborn scikit-learn scipy.
2. **Upload Dataset:** Upload the "anime.csv" file to your Colab environment.
3. **Run the Code:** Execute the provided Python code in a Colab notebook.
4. **Get Recommendations:** Call the `recommended_anime` function with the name of an anime to get recommendations.

## Evaluation Results

The system's performance is evaluated using precision, recall, and F1-score. The results are printed in the Colab output.

## Potential Improvements

- Exploring different similarity metrics (e.g., adjusted cosine similarity)
- Feature engineering: Include additional relevant features
- Tuning hyperparameters
- Trying different recommendation algorithms

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
