# Supervised Learning Challenge
### A homework assignment from the University of Birmingham Data Analytics Bootcamp (April 2022)

The aim of this project was to create a series of machine learning models in order to predict the likelihood of a loan becoming high risk. Two models were used for this example:

 - Logistic Regression
 - Random Forest Classifier

After the preliminary models were created, the data was scaled & the models ran once more.

#### Predictions

 - Random forest models are better suited to categorical data, rather than the numeric data included in this dataset. Therefore, the logistic regression model is expected to perform better in this scenario. 
 - The logistic model should also perform better than the random forest model once scaled as it is more receptive to this method.

#### Results

Overall, none of the models were as accurate as expected. In this example, the scaling method used did not improve the results enough to warrant using it. Perhaps using a different scaling method, such as MinMaxScaler in the sklearn library, would provide better results. However, with relatively low & untrustworthy scores presented in the file, a completely different model may need to be used altogether. 
