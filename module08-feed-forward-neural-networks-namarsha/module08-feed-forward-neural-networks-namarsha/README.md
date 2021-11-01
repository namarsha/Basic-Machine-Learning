# Feed Forward Neural Network

## Instructions
This exercise explores the use of artificial neural networks to perform a *regression* task. Also, you have been working on various concepts that make up the machine learning pipeline. So we will put it all together and build a machine learning pipeline that does the following: prepare the data, detect the relevant features, develop, train and evaluate a neural network. *You can optionally use random search to find the best hyper-parameters for the neural network*. 

This exercise will introduce you to [Keras](https://keras.io/), which is a deep learning library and the code structure is minimal and easy to follow. You will use the Ames Housing dataset that was published on [Kaggle][https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview]; however, you will find all the relevant data in the GitHub repository.


Create a Jupyter notebook (or Python script) and perform the following steps:

1. Load the training data `house_prices_train.csv` into a dataframe. Explore the data to get a better understanding of its structure and any data preparation steps that you need to perform.

2. Explore the data.
   - Gather summary/descriptive statistics and inspect all the fields.
   - View the frequency of missing values.

#### Building the pipeline
3. Prepare and transform the data.
   - Perform data imputation for the missing values (where necessary)
   - Perform feature scaling for continuous fields and encode categorical fields

4. Select the relevant features.

5. Build a Feed Forward Neural Network to predict house prices.

 
**If you have any questions about the assignment, create a GitHub issue and `@mention` the instructor.**

NOTE: The jupyter notebook `MLP.ipynb` contains starter code. Follow the instructions in each step; however, keep in mind that the code that is provided is not complete and many steps are required of you to finish it. Also read the python comments which contain additional information. Comments that are prefaced by `TODO:` require that you either provide a value or line of code. You may use the starter code, or create your own script from scratch.

<span style="color:red"> I recommend that you upload your notebook to [Google Colab](https://colab.research.google.com/) which is a free cloud-based service that allows you to run your Python script without the need to install Keras or any additional dependencies to configure your machine.</span>


### Reference
Here is more information on:
- Feature selection - https://scikit-learn.org/stable/modules/feature_selection.html
- Cross-validation - evaluating estimator performance: https://scikit-learn.org/stable/modules/cross_validation.html
- Keras - https://keras.io/
- Getting Started with Google colab - https://youtu.be/inN8seMm7UI
- Ames Housing dataset on Kaggle - https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview
- Preprocessing and feature extraction pipelines - https://scikit-learn.org/stable/auto_examples/compose/plot_column_transformer_mixed_types.html 
- Feature selection as part of a pipeline - https://scikit-learn.org/stable/modules/feature_selection.html#feature-selection-as-part-of-a-pipeline)
