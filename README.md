# cryptocurrency_clusters_ml
Processing cryptocurrency data to fit machine learning models.

## Code work can be found:
- Jupyter Notebook: cryptocurrency_clusters_ml.ipynb (main code)
- CSV: Resources/crypto_data (original data)
- PNG: Images/elbow.png and Images/tsne.png (images for README)

## Process
- Data Preperation: Filter for cryptocurrencies actively being traded and that have been mined, remove all null value rows, remove unneeded columns, convert non-numeric data to numeric, and standardize the dataset.
- Dimensionality Reduction: First using PCA then using t-SNE

![tsne](/Images/tsne.png)

- Cluster Analysis: k-Means

![elbow](/Images/elbow.png)

## Recommendation
As visualized, the cryptocurrencies can be clustered together. The optimal number of clusters, according to the elbow plot, is 4.

## Contact:
Joseph March: josephmarch@gmail.com
