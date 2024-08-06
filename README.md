# Google Data Analytics Capstone Project
This is my code for the Google Advanced Data Analytics Course Capstone Project.
    
**Capstone Project Background:**
The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They refer to you as a data analytics professional and ask you to provide data-driven suggestions based on your understanding of the data. They have the following question: what’s likely to make the employee leave the company?

**Project Goal:** 
The goal is to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.

**What I Did:**
I utilized two model approaches for the problem. First, I used binomial logistic regression predict whether an employee would leave the company based on tenure, work evaluation, number of projects, satisfaction level, and several other categories included in the dataset. The logistic regression model achieved a precision of 79%, recall of 82%, f1-score of 80% (all weighted averages), and accuracy of 82%. Next, I implemented a random forest model utilizing hyperparameter tuning using GridSearchCV. The entire model was saved using Pickle so it didn't have to be trained again during testing. After conducting feature engineering, the decision tree model achieved AUC of 93.8%, precision of 87.0%, recall of 90.4%, f1-score of 88.7%, and accuracy of 96.2%, on the test set. The random forest  outperformed the decision tree model. 

**Modules Used**
Numpy, Pandas, Seaborn, XGBoost, Sci-Py, Pickle

**Logistic Regression Confusion Matrix**:

![image](https://github.com/user-attachments/assets/72073f9f-8634-4e96-87e7-dbf821385193)

 **Final Decision Tree:**
![image](https://github.com/user-attachments/assets/d1d91bdd-fca4-45f1-929d-c28319d3b7eb)

