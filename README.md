
## Overview of the Analysis

The Purpose of the analysis is that 

* Explain the purpose of the analysis.
  
 The purpose of the analysis is to predict the creditworthiness of the borrower.Here we used a lending dataset which has values from peer to peer lending services.
  
* Explain what financial information the data was on, and what you needed to predict.
  
 We utilized a dataset containing historical lending transactions from a peer-to-peer lending platform to construct a 
 predictive model capable of assessing the creditworthiness of loan applicants.
  
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

Logistic Regression is a statistical model used for binary classification tasks, where the goal is to predict one of two possible outcomes (e.g., yes/no, true/false, 1/0). It's called "logistic" because it employs the logistic function to model the probability of a data point belonging to one of the two classes.


## Results

* Machine Learning Model 1:

**Precision**: 

1.For class 0 (the negative class), the precision is 1.00. This means that when the model predicted an instance to be in class 0 (negative), it was correct 100% of the time.

2.For class 1 (the positive class), the precision is 0.87. This means that when the model predicted an instance to be in class 1 (positive), it was correct about 87% of the time.


**Recall**:

1.For class 0, the recall is 1.00. This means that the model correctly identified all (100%) of the actual negative instances.

2.For class 1, the recall is 0.89. This indicates that the model correctly identified about 89% of the actual positive instances.

**Accuracy**:  In this case, the overall accuracy is 99%, which means that the model correctly predicted the class label for 99% of the total instances. This high accuracy suggests that the model is performing very well.



**Machine Learning Model 2:**
  * Description of Model 2 Accuracy, Precision, and Recall scores.
 
**Accuracy:**

Accuracy measures the overall correct predictions made by the model, regardless of class. In this case, the overall accuracy is 100%, indicating that the model correctly predicted the class label for 100% of the total instances.

**Precision**:
1. For class 0 (the negative class), the precision is 1.00, which means that when the model predicted an instance to be in class 0 (negative), it was correct 100% of the time.
2. 
3. For class 1 (the positive class), the precision is 0.87, indicating that when the model predicted an instance to be in class 1 (positive), it was correct about 87% of the time.

**Recall** :

For class 0, the recall is 1.00, meaning that the model correctly identified all (100%) of the actual negative instances.
For class 1, the recall is 1.00, indicating that the model correctly identified all (100%) of the actual positive instances.



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

 In summary, the Machine learning model appears to have a higher recall and overall accuracy for class 1, indicating improved performance in correctly identifying positive instances. However, both models show excellent performance, with high precision and overall accuracy. The choice between the two models depends on the specific objectives and the importance of recall in the application. The Machine learning model 2 may be preferred if correctly identifying all positive instances is of high importance. 
