# Gender_classifier

## Requirement
	* Python3

## Required Library
	* gensim
	* nltk
	* re
## Walk through the code
	1)Importing DatasetUsing the pandas library read the CSV data from the source
	2) Check for NULL values
	3)Remove those rows with NULL values
	4)Convert all coloumn data into list 
	5)Clean the data from every cell of the dataframe
	6)Find Unique values from the label column (gender)
	7)Map each to a number
	8)Use the CountVectorizer function to convert the text data into vectors
	9)Using the XGBOOST classifier, train the model with the training set and find the accuracy using the test data.
	10)Confusion matrix is also found for the same.
## Note
 	Check for the data, if its in 'int' then it  need to be converted as 'str' in order to find the null/NaN values. 
	The Gender clasifier trained here is for the respective data style alone.

