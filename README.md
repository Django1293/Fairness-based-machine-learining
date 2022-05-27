# Fairness-based-machine-learining
This report consists of
the study of model selection that considers accuracy and
fairness metrics together so that the machine learning model
can be used for fruitful predictions without being too much
biased against any of the sensitive attributes.
The standard Logistic Regression model is used to train
aif360 adult data set and German data set separately
with 5-fold cross-validation along with tuning the hyperparameter
‘C’. The ‘C’ values corresponding to the highest
accuracy and highest fairness metric (True Positive Rate
Difference) are taken and used to train and test the
corresponding data set (Task 1). Then the experiment is
repeated by also noting the effect of reweighing training
data in the change in accuracy and fairness values (Task 2).
An extra analysis is also done using the Random Forest
Classifier which is mentioned at the end of this report
