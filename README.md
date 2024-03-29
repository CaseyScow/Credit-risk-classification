# Credit-risk-classification Analysis and References
***Analysis***
The purpose of this machine learning model is to identify the creditworthiness of borrowers. This analysis will be going over the results of the model and contain a recommendation to the bank for use or not. In the data, a 0 for the loan_status means a loan is healthy and a value of 1 means it is high risk. 

The points of the machine learning model to be examined are the accuracy, precision, and recall. 

- Accuracy: The accuracy is a ratio of correctly predicted loans to the total observations. The overall accuracy in this instance was 0.992 (99%). This means the model correctly classified 99% of the total loans between high risk and healthy. 

- Precision: The precision is the ratio of correctly predicted positive loans to the total predicted positive. The precision for class 0 was 1.00 (100%), meaning that all the loans that were predicted to be creditworthy were predicted correctly. The precision for class 1 was 0.85 (85%) meaning out of all the high risk loans, the model only predicted 85% of them to be high risk.  

- Recall: Recall is the ratio of correctly predicted positive loans to all loans observed in the respected class (0 or 1). Recall for class 0 was 0.99 (99%), meaning the model correctly identified 99% of all instances that belonged to class 0 (healthy loans). The recall for class 1 was 0.91 (91%), meaning the model correctly identified 91% of the loans that actually belonged to class 1 (high risk).

In summary the accuracy (99%), precision (100%/ 85%), and recall (99%, 91%) all performed well in general. When looking at these scores it is key to remember what they are rating as the score for a good rating may vary depending on what you are evaluating. In this case, where we are determining high risk loans or not, all these scores can be argued to be good scores. Something else to now is there was a 100% mark in the precision. To some surprise, this may be a bad sign for your model as it can mean it is overfitted, meaning it was overtrained on the data and isn't giving accurate predictions anymore. However, considering the other scores I don't feel being overfitted was the issue here and I believe the 100% is a positive sign for this model in this circumstances. Overall, I believe this is a good model and I would for certain recommend the bank to use it. 

***References*** 
No references used outside of classroom activities. 