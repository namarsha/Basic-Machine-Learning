# Ensemble Learning

## Instructions

Create a [random forest](https://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees) classifier to predict cab driver's tip; based on the trip data, will they receive a tip or not. If they receive a tip, will it be low, standard or good. 

Create a Jupyter notebook (or Python script) and perform the following steps:
1. Load the data and select the salient features.

2. Split the data into training and test sets.

3. Create the random forest classifier and optimize the model to achieve a prediction accuracy of 95% (or higher).
    
    Note: at a minimum, you should identify suitable values for the following: `criterion`, `max_depth`, `max_features`, `min_samples_split`, `n_estimators`. The `max_depth` should not exceed 15.

4. Make predictions with the unseen data in `new_trips.csv`.

5. Summarize the results.

Note: You may reuse code from previous exercises (where applicable) and specify a seed for the `random_state` to ensure that your code is reproducible.


**If you have any questions about the assignment, create a GitHub issue and `@mention` the instructor.**

<span style="color:red">NOTE: The jupyter notebook `RandomForest.ipynb` contains starter code. Follow the instructions in each step. Also read the python comments which contain additional information. Comments that are prefaced by `TODO:` require that you either provide a value or line of code. You may use the starter code, or create your own script from scratch.</span>


### Reference
Here is more information on:
- Ensemble methods in scikit-learn:https://scikit-learn.org/stable/modules/ensemble.html
- Random Forests in scikit learn: https://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees
- Random search with cross validation: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html
- Grid Search with cross validation: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html#sklearn.model_selection.GridSearchCV
- Metrics in the scikit learn library: https://scikit-learn.org/stable/modules/model_evaluation.html.
- Splitting the data using scikit learn: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
