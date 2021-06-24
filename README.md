# Clear-Water-State-University-Attrition-Analysis
Analyzing the Attrition trend among the students of ClearWater State University.
The observed attrition rate is nearly 25%. There are 56 parameters given in the data set, out of which we have to find the prominent ones affecting the attrition.
In the begining after loading data, basic sanity checks are done. What does different parameters mean. number of observations are checked.
Primary study of Data is done. Necessary cleaning is done.
Unnecessary data such as untreatable missing values, least important parametes are removed and a new clean data set is made.
Different visualizations are used to study the data relations within themselves and there effects on attrition.
Model building predictions are done.
After that data is split among training and test datasets in 70:30 ratio respectively.
Building Machine learning models. Random forest and XGboost is selected after comparision of different models using accuracy mean and AUC/ROC curve.
Using feature importance top ten factors affecting Rate of student attrition are selected.
Confusion matrix is used to measure the performance accuracy of the machine learning model.
Random Forest Accuracy score = 92.5%
XG boost Accuracy score = 88%
