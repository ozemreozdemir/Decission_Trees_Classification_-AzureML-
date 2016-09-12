Targeted Marketing Campaign
======================================
In this problem we will use historical data from past customer responses
to build a classification model.
We will apply the trained model to a new set of prospects to whom we
may want extend an offer for a PEP. Rather than doing a mass marketing
campaign to all new prospects, we would like to target those that are
likely to respond positively to our offer (according to our classification
model).
Use the dataset provided (comma delimited, and the first row contains
the field names) - bank-data.csv
A. Open the .CSV file and inspect the attributes, is there one or more
attributes that should be removed? If so, do it now.
B. Optional - You can choose to use the ARFF format or use CSV,
- Save the file in .ARFF format
- Load the .ARFF formatted data file
C. Use Azure Machine Learning or a machine learning tool of your
choice to build a classification model. You can choose to use any of
the classification algorithms provided.
1. Evaluate your model accuracy. 
2. Spend time experimenting with different setting for the treebasses
algorithms - such as pruning, binary branching, etc. to
see if you can improve the performance of your model.
Consider performing parameter sweeping to optimize for
specific evaluation metrics.
3. Review the structure of the tree
 4. Identify the more important feature information.
5. Generate the ROC curve for your final model.
6. Show a screenshot of the final decision tree and model
accuracy statistics obtained from your
model.
Be sure to indicate the parameters you use in building your
classification model. (Note: Take a screenshot if there are too
many parameters)