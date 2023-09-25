# credit-risk-classification

So with this analysis, we are looking to see if there is a way for us to predict who will be a high risk loan or if the person will be able to payback the loan. 
We were trying to use the loan_status from the dataset for our 'y' value, which is what was requested in the starter code. 
What I did through this process was to separate the labels and the features, split the data into training and testing variables. I ran a logistic regression model on the data to teach the machine with the training and testing data.


MLM 1:
-Accuracy: 99%
-Precision: 86%
-Recall: 90%
--The accuracy is very high which is a great thing to see. The precision was 86% which a good result for the initial run on the training data. Recall was at 90% which again is hgih for an initial training run

MLM 2:
-Accuracy: 99%
-Precision: 85%
-Recall: 91%
--The testing matrix shows about the same levels as the training data. It is a good thing as a start. We should be concious of overfitting the model to the data so we might want to adjust how we go about training and testing the model

MLM 2 is better, while it does flag more people as a high risk who arent actually high risk. It still misses some people who are hgih risk but ultimately its better to be over cautious than over zealous in giving loans.
It is more important to predict 0's than 1's. Why, because the 0 is the high risk classification and we want to make sure we are more accurate with those people to make sure we do not give out loans to those who might default on their loans. 
