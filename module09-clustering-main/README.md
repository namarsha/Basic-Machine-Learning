# Cluster Analysis

## Instructions
This module introduces unsupervised learning -- which involves various techniques to identify patterns in unlabeled data. There are two parts to this assignment.
1. You will first use `kmeans-dbscan.py` to explore two algorithms on a fictitious dataset. Try experimenting with the algorithms to see the pros and cons of each algorithm with the data. You can also experiment with other clustering algorithms in the scikit-learn library.
   - Load the notebook `kmeans-dbscan.ipynb` and provide suitable values for the k-means and DBSCAN algorithms; `TODO:` require that you either provide a value or line of code.
2. Select an appropriate clustering algorithm and use it to identify patterns in a real dataset. The data was released by the National Highway Traffic Safety Administration and it contains information on fatal collisions in the US. The [CSV data](https://github.com/fivethirtyeight/data/blob/master/bad-drivers/bad-drivers.csv) can be obtained from [Five Thirty Eight](https://github.com/fivethirtyeight/data/tree/master/bad-drivers) GitHub repository. Here is a direct link to the raw data https://raw.githubusercontent.com/fivethirtyeight/data/master/bad-drivers/bad-drivers.csv. 
   - Load `Clustering.ipynb` and follow the steps in the assignment. Explore the data and identify useful features to provide as input to your clustering algorithm. Explain your process and remember that you are working with unlabeled data (so there is no predicted output).

**If you have any questions about the assignment, create a GitHub issue and `@mention` the instructor.**

### Reference
Here is more information on:
- Clustering in scikit-learn: https://scikit-learn.org/stable/modules/clustering.html
- Principal component analysis (PCA) in scikit-learn: https://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca
- Unsupervised dimensionality reduction: https://scikit-learn.org/stable/modules/unsupervised_reduction.html`
