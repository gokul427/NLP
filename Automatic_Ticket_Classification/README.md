
# Automatic Ticket Classification

Model that is able to classify customer complaints.  

Used NMF to analyse patterns and classify tickets into the following five clusters.  
a) Credit card / Prepaid card.  
b) Bank account services.  
c) Theft/Dispute reporting.  
d) Mortgages/loans.  
e) Others.  

After mapping using NMP topic modelling, used this data to train any supervised model such as logistic regression, decision tree or random forest.   
Using this trained model, you can classify any new customer complaint support ticket into its relevant department.
## Problem statement

Customer complaints are unstructured text data.  
Companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. 
This becomes tedious as the company grows and has a large customer base.  
Need to create a model that can automatically classify customer complaints based on the products and services that the ticket mentions.
## Results

Created four supervised models (Logistic Regression, Naive Bayes, Decision Tree Classifier and Random Forest Classifier) to predict any new complaints to the relevant Topics.  


### Logistic Regression

The overall accuracy of the Logistic Regression model is 91%.  
Precision and Recall of the model are 91% and 91% respectively.

### Naive Bayes

The overall accuracy of the Decision Tree model is 76%. 
Precision and Recall are 77% and 74% respectively.

### Decision Tree

The overall accuracy of the Decision Tree model is 78%. 
Precision and Recall are 77% and 76% respectively.

### Random Forest

The overall accuracy of the Random Forest model is 82%. 
Precision and Recall are 83% and 80% respectively.

## Conclusion
Based on the above results, Logistic Regression is the best model with an accuracy of 91% with Precision and Recall as 91% and 91% respectively.  
The model is able to inference pretty well using logistic regression.
