# Clustering
# EastWestAirlines Customer Segmentation

This Assignment aims to perform customer segmentation for EastWestAirlines using clustering techniques in Python. We use the K-Means, Hierarchical, and DBSCAN algorithms to group customers based on their characteristics and behaviors.

## Dataset

The dataset used in this Assignment is "EastWestAirlines.xlsx," which contains information about airline customers, including their flight miles, bonus points, and other relevant features.

## Libraries Used

The following libraries are used in this Assignment:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn (for clustering and preprocessing)
- scipy (for hierarchical clustering)

## Methodology

1. **Data Loading and Preprocessing:**
   - The dataset is loaded using pandas.
   - Outliers are handled using the IQR method.
   - Features are scaled using StandardScaler.

2. **Clustering:**
   - **K-Means:** The optimal number of clusters is determined using the elbow method and silhouette score. Customers are then clustered using K-Means.
   - **Hierarchical Clustering:** A dendrogram is created to visualize the hierarchical structure of clusters. Agglomerative clustering is then performed.
   - **DBSCAN:** The optimal `eps` and `min_samples` parameters are determined for DBSCAN clustering. Customers are then clustered using DBSCAN.

3. **Visualization:**
   - Scatter plots and pair plots are used to visualize the clusters and their relationships with different features.

## Results

The Assignment identifies distinct customer segments based on their behavior and characteristics. The clusters can be used to understand customer preferences and tailor marketing strategies accordingly.

## Usage

1. Upload the "EastWestAirlines.xlsx" file to your Google Colab environment.
2. Run the code cells sequentially to perform the analysis.
3. Explore the visualizations and results to understand the customer segments.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
