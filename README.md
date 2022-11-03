# Supervised Machine Learning - Predicting Credit Risk

I created and compared two models using the `lending_data.csv`: a logistic regression, and a random forests classifier. 

## Prediction

I predict that the logistic regression model will perform better against this data because much of the data is not categorical and may have some outliers.  The random forest classifier tends to work better with categorical data than logistic regression, but does not handle outliers in the data as well.  This data contains multiple fields that can contain a large array of numerical values (ie rate, total debt, borrower income) instead of categorical data.  Additionally, I feel that the data set is prone to having some outliers because it is .

## Results

My findings show that the two models were virtually equal in performance against the test data set after being trained.  This is likely because the training data set closely matched the testing data set.  The random forest model would have had issues if the test data had some values that were outliers, but apparently there were not many outliers or they were equally distriuted in the training/test data sets.

As a lending agent/company/bank, I would prefer to use the Logisitc Regression because it would allow for adjustments to the threshold probability so that it could be fine tuned to fit the appetite for risk in lending practices.