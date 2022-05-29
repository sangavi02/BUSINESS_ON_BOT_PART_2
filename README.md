## BUSINESS_ON_BOT_PART_2

In this task I have analysed the given data set and prformed the sentimental analysis.In this tweet has been pulled from twitter and manual tagging is done .I had preprocessed the data , And the dataset has been spiltted into train and test datasets.

# STEP-1:
Here we need to import the necessary libraries that be required for our model. In the above code, we have imported libraries such as pandas to deal with data 
> frames/datasets, 
> re for regular expression,
> nltk is a natural language tool kit 
> hfrom that, we have imported module – stopwords which are nothing but ‘dictionary’

# STEP-2
 Here we have read the file named
“Coronatweetscentimentanaysis” in CSV(comma-separated value) format. And have checked for the top 5 values in the dataset using head()

# STEP 3:-
Further, I have performed some data visualizations using matplotlib and sea born libraries which are really the best visualization libraries in Python. I have plotted only one graph, you can plot more graphs to see how your data is.

# STEP4:-
 In this step, we are able to see how the summary of our data like No. of columns with their data types.
 
# STEP-5
Here we will perform a regular expression function to remove any symbols and special characters, etc to get pure data.

# STEP-6
By using vectorization, we have performed normalization of test data and stored it into x_test & y_test. We have also predicted actual and predicted values

# STEP-7
So, at last, we have performed the accuracy of our model in the form of an AUC curve plotted using the matplotlib library.
