# Credit Risk Analysis

## Overview of the analysis: 
   - Use Machine learning to solve the challenge of predicting credit card risk.     
  
### Dataset:  
    - LoanStats_2019Q1.csv

### Technologies:  
    - Python
    - Jupyter Notebook
    - Visual Studio
    - Pandas

## Results: 
   - Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
### Naive Random Oversampling: 
    - Balanced Accuracy Score is 67%
    - Precision for High Risk is 1%
    - Sensitivity or Recall for High Risk is 70% 
![](/Images/Naive_Random_Oversampling.png)
### SMOTE Oversampling:
    - Balanced Accuracy Score is 65%
    - Precision for High Risk is 1%
    - Sensitivity or Recall for High Risk is 61%
![](/Images/SMOTE_Oversampling.png)
### Undersampling:
    - Balanced Accuracy Score is 52%
    - Precision for High Risk is 1%
    - Sensitivity or Recall for High Risk is 65%
![](/Images/Undersampling.png)
### Combination (Oversampling and Undersampling):
    - Balanced Accuracy Score is 66%
    - Precision for High Risk is 1%
    - Sensitivity or Recall for High Risk is 74%
![](/Images/Combination_Over_Under_Sampling.png)
### Balanced Random Forest Classifier: 
    - Balanced Accuracy Score is 78%
    - Precision for High Risk is 3%
    - Sensitivity or Recall for High Risk is 68%
![](/Images/Balanced_Random_Forest_Classifier.png)
### Easy Ensemble AdaBoost Classifier: 
    - Balanced Accuracy Score is 93%
    - Precision for High Risk is 9%
    - Sensitivity or Recall for High Risk is 92%
![](/Images/Easy_Ensemble_AdaBoost_Classifier.png)

## Summary: 
   - Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination (Over and Under) Sampling, and Balanced Random Forest Classifier all demonstrated low predictability based on their respective Balanced Accuracy Scores - the precision and Sensitivity/Recall scores supported these results for each of the models.  
   -  **Easy Ensemble AdaBoost Classifier** demonstrated a high Balanced Accuracy Score of 93%, and a high Sensitivity/Recall Score of 92%, making it the recommended model.  