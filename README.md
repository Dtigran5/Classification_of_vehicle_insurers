Classification of vehicle insurers by risk level

Description

For 151,406 vehicle insurance contracts, the values ​​of a number of characteristics are known, including gender, age, driving experience and the bonus-malus coefficient of the driver, type, brand, model, year of manufacture, country of origin, power and engine size, as well as the target characteristic, equal to 1 if concluding a contract with a client is risky, and 0 otherwise (file insclass_train.csv) and a sample submission file in the correct format(insclass_sample.csv).
It is required to build a model that predicts the value of the target attribute for 22,624 contracts from the test data set (file insclass_test.csv).

The quality metric is the area under the ROC curve (AUC).

One of the features of this task is that for almost all brands there are different models representing them.
