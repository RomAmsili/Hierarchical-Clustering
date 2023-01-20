# Hierarchical-Clustering

This notebook is a demonstration of using Hierarchical Clustering Algorithm on a dataset of customers' information. Hierarchical Clustering is a method of cluster analysis which seeks to build a hierarchy of clusters.

## Getting Started

To run the notebook, you will need to have the following installed:
* Jupyter Notebook
* Python 3
* Numpy
* Pandas
* Matplotlib
* Sklearn
* Scipy

The notebook is divided into the following sections:
1. Data Preparation
2. Data Exploration
3. Dendrograms
4. Hierarchical Clustering
5. Evaluation

You can run the code by executing each cell in order.

## Data

The dataset used in this notebook contains information about customers' spending score and annual income. Preprocess the articles using Doc2Vec embedding model.
Fit doc2vec on the data and infer the vector for each article. 

## Results

The Hierarchical Clustering algorithm is able to segment the data into different groups of customers based on their spending score and annual income. The algorithm generated 5 clusters which can be used for further analysis or to personalize marketing campaigns.

## Conclusion

The Hierarchical-Clustering notebook provides a glimpse into how Hierarchical Clustering algorithm can be used to segment data into different clusters. Additionally, this notebook can be used as a starting point for experimenting with different architectures, hyperparameters, or datasets to improve the quality of the model.

## Acknowledgements

This notebook is inspired by the work of [RomAmsili](https://github.com/RomAmsili) and the dataset used is also from the same source.

Preprocess the articles using Doc2Vec embedding model with the parametes:

vector_size=100, window=5, min_count=1, workers=4

Fit doc2vec on the data and infer the vector for each article. 

documentation of doc2vec model : https://radimrehurek.com/gensim/models/doc2vec.html
