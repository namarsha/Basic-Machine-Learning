# Module 03: Data-Wrangling

## Overview
You are hired as a Machine Learning Engineer, on the Data Insights and Analytics Team, for the NYC Taxi and Limousine Commission (TLC). Your first assignment is to identify the factors that contribute toward cab drivers' being incentivized (i.e. what determines whether or not they receive a tip).

Your supervisor has requested that you conduct your analysis for December 2019 and would like for you to present your findings during the next team meeting. Use a Jupyter notebook to demonstrate the data wrangling and exploratory analysis.

The TLC trip record data and a description of the initiative can be found at the following link: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
For a description of the fields, here is the link to the [Green Trips Data Dictionary](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf).


## Instructions

#### Use the notebook: `DataWrangling.ipynb` to perform the following steps:
- Step 1 – Programmatically download the required data for December 2019.
- Step 2 – Report the number of rows and columns in the data.
- Step 3 – Gather summary/descriptive statistics. State your initial observations (no more than 1 paragraph) and identify any inconsistencies. HINT: you can use the **describe** function
- Step 4 –  Examine the data for missing observations and duplicate records. Suggest what methods are appropriate to handle them.
- Step 5 –  Plot a histogram showing the distribution of the trip distance. Discuss your observations (no more than 1 paragraph).
- Step 6 –  Did you detect any outliers in step 5? If so, perform a suitable method to handle them?
- Step 7 –  Show the frequency of trips for each date. Do you see any interesting patterns or do you detect the need for additional data prep. rules.
- Step 8 
  - (a) Create a visualization that shows how people pay for their cab rides (e.g. credit card, cash, etc.). Can you say what is the most popular mode of payment?
  - (b) Filter the data to only include customers who paid via credit card.
- Step 9 –  Create a compelling visualization, based on your intuition, about the data and any useful insights on what factors contribute to cab driver's gratuity. 
  For example: 
  - Is there any correlation between the pickup/drop-off location and the gratuity? 
  - Does the trip distance or duration influence gratuity?

**Post questions about the assignment as GitHub issues.**
