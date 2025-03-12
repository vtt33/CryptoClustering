Objectives

Load and preprocess cryptocurrency market data.

Normalize the dataset using StandardScaler.

Perform K-Means clustering on the full dataset and the PCA-reduced dataset.

Visualize the Elbow Curve to determine the optimal number of clusters.

Compare clustering performance and visual results before and after PCA.

Dataset Description

The dataset contains various cryptocurrency performance metrics, including:

price_change_percentage_24h

price_change_percentage_7d

price_change_percentage_14d

price_change_percentage_30d

price_change_percentage_60d

price_change_percentage_200d

price_change_percentage_1y



Data Preprocessing:

Normalize the data using StandardScaler().

K-Means Clustering (Original Data):

Use the Elbow method to determine the optimal number of clusters.

Fit the K-Means model and assign cluster labels.

PCA Transformation:

Reduce the dataset to three principal components using PCA().

Fit the K-Means model to the PCA-transformed data.

Visualization:

Plot Elbow Curves for both the original and PCA data.

Visualize cluster distributions using scatter plots.


Conclusion

Reducing the dataset's dimensionality using PCA improved the K-Means clustering performance by enhancing cluster separation and simplifying the dataset. This approach effectively retains meaningful patterns while reducing noise and redundancy.
