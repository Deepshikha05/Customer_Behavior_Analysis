# Customer Behavior Classifier #



# README #

This project uses different classification techniques like Logistic Regression, SVM, Random Forest and Decision Trees on customer behavior data to predict if a particular customer will churn or not. 

### The Working ###

* The data is first read using pandas from a csv file.
* Then Lable Encoding is done on all the variables containing string type values.
* Now, using the label encoded data, the variables are one hot encoded.
* Float values are then converted to integers for easy computation.
* Data is then divided into test and training data.
* Feature Scaling of all the features is done.
* Classification model is fit using the training data.
* Finally, evaluation of the model is done.

### Steps To Run ###

* Jupyter notebook needs to be run in sequence.

### Dependencies ###
`pandas`
`numpy`
`sklearn`
`matplotlib`

 The exact dependencies can be downloaded by running `pip install -r requirements.txt`

* install requests using `pip install requests`


### Common Issues ###

* The most common issue seems to be right encoding of the feature variables. If the faetures are not correctly encoded, the classifier would be trained with faulty data and the precision of the classifier would be less.
* It is very important to perform feature scaling of all the feature variables. 
* There are many parameters in different classifiers that needs to be understood and applied carefully in order to obtain the right result.
