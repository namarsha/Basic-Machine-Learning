# Decision Trees — Model Development

## Instructions

You have been asked to build a predictive model that can classify the cab driver's tip i.e. based on the trip data, will they receive a tip or not. If they receive a tip, will it be low, standard or good. You are required to build a [decision tree](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier), using the scikit-learn library to make the predictions. 

The trip data has been preprocessed and is stored in 'trip_data.csv.zip'. 


Create a Jupyter notebook (or Python script) and load the data in 'trip_data.csv.zip' and perform the following steps:

1. Extract the following features that will be used to build the model: 
    'VendorID', 'RatecodeID', 'PULocationID', 'DOLocationID', 'passenger_count', 
    'trip_distance', 'fare_amount', 'extra', 'mta_tax', 'tolls_amount', 
    'improvement_surcharge', 'total_amount', 'trip_type', 'congestion_surcharge', 'tip'
        
   - Note: The column 'tip' contains the labels (i.e. the predicted output). The labels are: no-tip, low, standard or good.


2. Split the dataset into a training set and a test set; The test set should comprise 30% of the dataset. Ensure the data is randomized and that stratified samples are obtained. Scikit-learn has a module that is useful to [split the data](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) according to this criteria.


3. Create a decision tree to classify the cab driver's tip. Ensure that you perform these steps:
 
   3.1 Instantiate the [Decision Tree Classifier](https://scikit-learn.org/stable/modules/tree.html#classification) object and set the parameter for `criterion` to either 'gini' or 'entropy'. Also set the `max_depth` to 5.
 
   3.2 Build the Decision Tree model using the training set. 
 
   3.3 Use the model to make predictions with the test set.
 
   3.4 Evaluate the accuracy of the predictions, using the [accuracy score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html#sklearn.metrics.accuracy_score), and display the accuracy that was achieved. 

     NOTE: If the prediction accuracy is less than 80%, increase or decrease the value of `max_depth` in 3.1 above. Run the code for steps 3.1 to 3.4 to retrain the classifier and evaluate the predictions. Did the accuracy improve? If not, choose a value for `max_depth` to improve the accuracy.

4. Visualize the decision tree using the graphviz library (or your preferred library/tool).
   - Inspect the visualization and summarize the results using 2-5 sentences. What are your thoughts on the way the decision tree split the data to make the predictions and the accuracy that was obtained?
 
**If you have any questions about the assignment, create a GitHub issue and `@mention` the instructor.**

<span style="color:red">NOTE: The jupyter notebook `DecisionTreePt1.ipynb` contains starter code. Follow the instructions in each step. Also read the python comments which contain additional information. Comments that are prefaced by `TODO:` require that you either provide a value or line of code. You may use the starter code, or create your own script from scratch.</span>


### Reference
Here is more information on:
- Parameters for the Decision Tree Classifier: https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier
- Buidling decision trees using scikit-learn which includes sample code: https://scikit-learn.org/stable/modules/tree.html
- Metrics in the scikit learn library: https://scikit-learn.org/stable/modules/model_evaluation.html.
- Splitting the data using scikit learn: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
