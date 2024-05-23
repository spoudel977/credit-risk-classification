**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** WRITE YOUR ANSWER HERE!
The classification report provides metrics for performance evaluation of the logistic regression model. 

A.  Class Specific Performance 
    
    Class 0 (Healthy loan)
    * Precision 1.00 which is 100% - All predicted positives for class 0, 100% were correct
    * Recall comes as 99% - out of all actual positives for class 0, 99% were correctly identified by the model
    * F1-Score - 100% showing very high balance between precision and recall. 


    Class 1 (High-risk loan)
    * Precision 86%, recall 94% and F1 Score 90%  were correctly identified by the model. 

B.  Average Metrics
    
    Macro Average 
    * Precision 93%, reall 97% and F1-score 95% - noted as average over both classes, treating each class equally. 

    Weightage Agerage 
    *  Precision 99%, recall 99% and F1 score 99% - noted as average over the both classes, weighted by the number of instances in both classes.

In summary, the logistic regression model shows excellent overall performance with an accuracy of 99%.  The model performs exceptionally well in predicting class 0 (Healthy loan) with perfect precision and very high recall. For class 1 (High-risk loan), the model also performs well however there are some rooms for improvement in precision. Finally the high weighted average metrics indicate that the model is reliable across the dataset though slight drop in precision for class 1 suggesting model occasionally misclassifies some loan approvals. 



