# Server-hacking-predicton-using-machine-learning

Prediction model for Server Hacking

Contents:
•	Importing Libraries
•	Dataset Reading
•	Exploratory Data Analysis (EDA)
•	Train Test Split
•	Model  Building
•	Confusion Matrix
•	Classification Report / Accuracy 
•	K-FOLD Cross Validation

Importing Libraries

	Listing out the Libraries which I used in this model
•	Pandas - Open source Library for Data Frame which is used to read dataset and handle dataframe etc,
•	Numpy  -  Open source and It is mathematical library which is most used to array functions.
•	Scikit learn  - also known as sklearn, it is Open source and helps to pre processing,  importing algorithms  , evaluating the model etc.
•	Matplotlib and Seaborn  - These Both libraries are use to Visualize the data.

Data Set Reading

	Reading the Train and Test Comma Separated Values (CSV) file.


Exploratory Data Analysis (EDA) 
	
Exploratory Data Analysis is the one of the Important steps in making the prediction and classification model  

•	Understanding the Data
  o	Categorical or Numerical
•	Checking for the missing values
  o	In the case we have 182 missing values in train.csv data and 127 missing values in test.csv data.
  o	Replaced the data with Median value
Data Splitting 

•	Data Splitting for Train and Test set to Evaluate our model.
•	Here we take 75 % of Train data and 25% of test .

Model Building

	We done with Two Ensemble Methods which is Random Forest and Gradient Boosting Model. We get 99.07 % accuracy for Random Forest Classifier and 99.94 %accuracy for Gradient Boosting classifier model.

Confusion Matrix
	
	Confusion matrix is also known as Error matrix which is used to check the performance of a classification problem.
	Confusion matrix has to side which is Actual and Prediction and it is gives the results of True Positive, True Negative, False Positive and False Negative.

Classification Report

	Classification Report also used to Checking the Accuracy and performance of the Classification model, it give a detail report which contains Accuracy, Recall Score, Precision Score, F1 Score, Weighted Average etc.


K-FOLD Cross Validation

	Since our model gives accuracy of 99.94,we need to check whether our model overfitted or not.
	K-Fold Cross Validation is prevents overfitting. It splits the data set into N numbers and change the train and test set in each sets.

Conclusion

	After the K-FOLD Cross Validation Gradient Boosting Classifier gets a accuracy of 99.89 % which is near to 1.00 %, so Gradient Boosting  Classifier is the best model to predict if the server will hacked or not.
  


  

