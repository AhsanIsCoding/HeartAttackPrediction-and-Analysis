# HeartAttackPrediction-and-Analysis
Mahcine Learning model for prediction of chances of Heart Attack
The data used for building this model consists of heart paitients data and comprises of columns like their age,sex,chest pain type, cholestrol, heart rate, etc.
After analyzing all the columns and capping the outliers a few basic models were run like random forest, Adaboost, Knn, Naive bayes and logistic model and XGBoost
However, XGBboost after performing some hyperparameter tuning with the help gridsearchCV gave the best results and were able to make predictions with 85% accuracy. Hence, considered as final model.
