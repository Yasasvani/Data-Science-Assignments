# PCA
# Wine Clustering Analysis

This Project explores clustering techniques applied to a wine dataset. The primary goals are to:

1. Perform Exploratory Data Analysis (EDA) to understand the dataset's characteristics.
2. Apply Principal Component Analysis (PCA) for dimensionality reduction.
3. Implement K-means clustering on both the original and PCA-transformed data.
4. Compare the clustering results and analyze the impact of dimensionality reduction.

## Dataset

The dataset used is the Wine dataset, which contains information about various chemical properties of wines derived from three different cultivars. The features include alcohol content, malic acid, ash, alcalinity of ash, magnesium, total phenols, flavanoids, nonflavanoid phenols, proanthocyanins, color intensity, hue, OD280/OD315 of diluted wines, and proline.

## Methodology

1. **EDA:** The dataset is explored using descriptive statistics, visualizations (box plots, histograms, heatmaps, density plots), and checks for missing values and duplicates.

2. **PCA:** PCA is applied to reduce the dimensionality of the dataset while retaining most of the variance. The optimal number of principal components is determined using a scree plot and cumulative explained variance analysis.

3. **Clustering:** K-means clustering is performed on both the original (scaled) and PCA-transformed datasets. The number of clusters is set to 3, corresponding to the known wine types.

4. **Evaluation:** Clustering performance is evaluated using the Silhouette Score and Davies-Bouldin Index. These metrics assess the quality of clusters based on intra-cluster similarity and inter-cluster separation.

## Results

The clustering results are compared and analyzed to understand the impact of PCA on clustering performance. The analysis includes:

- **Comparison of Evaluation Metrics:** Silhouette Scores and Davies-Bouldin Indices are compared for both clustering scenarios.
- **Observed Similarities and Differences:** Similarities and differences in cluster formations are identified between the original and PCA-transformed datasets.
- **Impact of Dimensionality Reduction:** The effect of PCA on clustering accuracy and cluster separation is discussed.

## Conclusion

The Project concludes with key findings and insights derived from the analysis. It summarizes the performance of clustering on both datasets and highlights the trade-offs between dimensionality reduction and clustering accuracy.

## Dependencies

- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

## Usage

1. Ensure all dependencies are installed.
2. Load the wine dataset (`wine.csv`).
3. Run the provided Python code in a Jupyter Notebook or Google Colab environment.
4. Review the generated outputs, including visualizations and evaluation metrics.

## Contributing

Contributions to this project are welcome. You can contribute by:

- Improving the EDA or clustering analysis.
- Experimenting with different clustering algorithms or evaluation metrics.
- Extending the project to explore other datasets or applications of clustering.

## License

This project is licensed under the MIT License.
