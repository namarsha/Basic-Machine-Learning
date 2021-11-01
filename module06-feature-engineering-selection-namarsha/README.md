# Feature Engineering

## Instructions

This assignment focusses on feature engineering and evaluating the importance of features on the model's predictions. In this exercise, you will:
- Create a new feature.
- Encode categorical features and standardize numeric data.
- Use feature selection techniques to identify salient features.
    NOTE: Feature selection techniques include filter methods, wrapper methods, embedded and hybrid methods. This exercise will focus on filter and wrapper methods.


Create a Jupyter notebook (or Python script) and perform the following steps:

1. Load 'trip_data.csv' and extract a sample of the data. Ensure that the data is not imbalanced (i.e. obtain equal samples of data from each class).

2. Create a new feature called `trip_duration` which is the time elapsed (i.e. the difference) between the pickup and dropoff times, `lpep_pickup_datetime` and `lpep_dropoff_datetime` respectively. The `trip_duration` should be represented in seconds. 

3. Encode class labels in the 'tip' field using the `LabelEncoder`. After which, assign the input features (in the dataframe) to a variable 'X' and the encoded labels to a variable 'y'.

4. Implement the following feature selection algorithms:
   - Select K Best, and
   - Recursive Feature Elimination
    
    Each algorithm should identify the top seven features and display the feature names. Are the top features, from each algorithm, consistent? How did the algorithms rank the new feature `trip_duration`?

5. Standardize the input features, and perform the above feature selection algorithms again. Display the feature names. Did the results change?

6. Explain the effect of standardizing the data.

7. Based on your observations about the features, did the algorithm identify meaningful features and did they align with your previous intuition about the data (Recall the data wrangling exercise)? Did it identify any features that you would not have considered?
 
**If you have any questions about the assignment, create a GitHub issue and `@mention` the instructor.**

<span style="color:red">NOTE: The jupyter notebook `FeatureEng.ipynb` contains starter code. Follow the instructions in each step. Also read the python comments which contain additional information. Comments that are prefaced by `TODO:` require that you either provide a value or line of code. You may use the starter code, or create your own script from scratch.</span>


### Reference
Here is more information on:
- Feature selection: https://scikit-learn.org/stable/modules/feature_selection.html
- Univariate feature selection: https://scikit-learn.org/stable/modules/feature_selection.html#univariate-feature-selection
- Recursive feature elemination: https://scikit-learn.org/stable/modules/feature_selection.html#recursive-feature-elimination
- Support Vector Machines: https://www.youtube.com/watch?v=N1vOgolbjSc
- Support Vector Machines in scikit-learn: https://scikit-learn.org/stable/modules/svm.html
- How to create new columns in a pandas dataframe: https://pandas.pydata.org/docs/getting_started/intro_tutorials/05_add_columns.html
